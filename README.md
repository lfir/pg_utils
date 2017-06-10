Generic queries and functions for PostgreSQL. Compiled (and some developed) by Asta1986.
Tested on PostgreSQL 9.5.

##### Contents:
###### BACKUP & RESTORE WITH PSQL:
* Backup all databases in the server.
* Restore all databases from backup file.
* Backup one database.
* Restore one database from file.

###### CSV:
* Import table/column from CSV file.
* Import with header (if the first row contains column names).
* Export table to CSV.

###### DUPLICATE ROWS:
* Compare rows according to values in the columns.

###### PIVOT TABLES:
* Using crosstab.
* Using aggregate_function(case).

###### TABLE INFO:
* Get table names.
* Get information of columns.
* Get name and type of PK column.

###### TEMPORARY TABLE:
* Create a temporary table from the result of query.

###### USERS & PERMISSIONS:
* Create a read only user manually.
* Add privileges to read only user automatically upon creation of new tables, schemas or views.

###### VIEWS:
* Display user created views.
