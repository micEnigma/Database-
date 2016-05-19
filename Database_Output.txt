//Five queries that will work on the database pictured:

SELECT: This selects data from a database and stores it in a results table. The results table's results varies depending on what is being queried and how it is being queried. For instance using the wildcard "*" pulls everything on the queried database to the results table.
// SELECT * FROM table_name -- Selects all data on table_name


DELETE: This deletes specified rows from the specified database. When no row parameters are specified, the whole database table will be deleted.
//DELETE FROM table_name -- Deletes all data from table_name


CREATE TABLE: This creates a new table in a database. The table consists of rows and columns and a table name must be specified.
//CREATE TABLE MatchTable
(
SportID int,
Venue varchar(255),
SportType varchar(255),
City varchar(255)
); 



