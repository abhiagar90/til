# Import MySQL Dump from terminal

1. Create the database in which you want to import the .sql file using the command `create database <database-name>`.
2. Now use the command `mysql -u root -p <database-name> < <sql-file-name>.sql`

Note: You will have to have an existing database before the import.
