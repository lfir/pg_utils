Generic queries and commands for PostgreSQL.
Compiled (some developed) and tested by Asta1986 on PostgreSQL 9.5 and Fedora 25.

##### Contents:
###### [CSV:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L2)
* [Import table/column from CSV file.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L4)
* [Import with header (if the first row contains column names).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L7)
* [Export table/query result to CSV.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L10)

###### [FUNCTIONS](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L15)
* [Set cell values of text columns in a table to lower case.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L17)
* [Transform a string with google maps point coordinates to WGS84 WKT.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L35)

###### [DUPLICATE ROWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L48)
* [Compare rows according to values in certain columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L50)

###### [PIVOT TABLES:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L56)
* [Using crosstab.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L58)
* [Using aggregate_function(case).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L74)

###### [TABLE INFO:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L84)
* [Get table names.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L86)
* [Get information of columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L91)
* [Get name and type of PK column.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L96)

###### [TEMPORARY TABLE:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L112)
* [Create a temporary table from the result of query.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L114)

###### [TRANSACTIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L119)
* [Create a transaction block.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L121)
* [Abort current transaction.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L127)

###### [USERS & PERMISSIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L132)
* [Create a read only user manually.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L134)
* [Add privileges to read only user automatically upon creation of new tables, schemas or views.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L139)

###### [VIEWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L164)
* [Display user created views.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L166)
