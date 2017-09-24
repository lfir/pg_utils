Generic queries and commands for PostgreSQL.
Compiled (some developed) and tested by Asta1986 on PostgreSQL 9.5 and Fedora 25.

##### Contents:
###### [CSV:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L2)
* [Import table/column from CSV file.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L4)
* [Import with header (if the first row contains column names).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L7)
* [Export table/query result to CSV.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L10)

###### [DUPLICATE ROWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L15)
* [Compare rows according to values in the columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L17)

###### [PIVOT TABLES:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L23)
* [Using crosstab.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L25)
* [Using aggregate_function(case).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L41)

###### [TABLE INFO:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L51)
* [Get table names.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L53)
* [Get information of columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L58)
* [Get name and type of PK column.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L63)

###### [TEMPORARY TABLE:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L79)
* [Create a temporary table from the result of query.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L81)

###### [TRANSACTIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L86)
* [Create a transaction block.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L88)
* [Abort current transaction.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L94)

###### [USERS & PERMISSIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L99)
* [Create a read only user manually.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L101)
* [Add privileges to read only user automatically upon creation of new tables, schemas or views.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L106)

###### [VIEWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L131)
* [Display user created views.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L133)
