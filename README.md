# Test data for databases

You can find here test data to fill your database.
You can use it for learning.

## Command to import data:

- Sqlite

`sqlite3 <your database file> < test_sqlite.sql`

- MySQL

`mysql -p <your database name> <mysql_test.sql`

- Postgres

`psql -U <your user> -d <your database name> -f postgres_test.sql`
