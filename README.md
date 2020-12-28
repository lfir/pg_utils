Generic queries and commands for PostgreSQL.
Compiled (some written) and tested by Asta1986 on PostgreSQL 13.

##### Contents:
###### [CSV:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L2)
* [Import table/column from CSV file.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L4)
* [Import with header (if the first row contains column names).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L7)
* [Export table/query result to CSV.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L10)

###### [FUNCTIONS](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L15)
* [Erase all schemas (except system ones) and contained objects in the current db.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L17)
* [Set cell values of text columns in a table to lower case.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L31)
* [Transform a string with google maps point coordinates to WGS84 WKT.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L49)

###### [DUPLICATE ROWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L62)
* [Compare rows according to values in certain columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L64)

###### [PIVOT TABLES:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L70)
* [Using crosstab.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L72)
* [Using aggregate_function(case).](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L88)

###### [TABLE INFO:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L98)
* [Get table names.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L100)
* [Get information of columns.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L105)
* [Get name and type of PK column.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L110)

###### [TEMPORARY TABLE:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L126)
* [Create a temporary table from the result of query.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L128)

###### [TRANSACTIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L133)
* [Create a transaction block.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L135)
* [Abort current transaction.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L141)

###### [USERS & PERMISSIONS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L146)
* [Create a read only user manually.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L148)
* [Add privileges to read only user automatically upon creation of new schemas.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L156)

###### [VIEWS:](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L181)
* [Display user created views.](https://github.com/Asta1986/pg_utils/blob/master/postgresql-generic-utils.sql#L183)
