# mysql-terminal-cmd

## *Create database*
'''{mysql}
create databse [databasename];
'''

*List of all databases*
show databases;

*Switch to a database*
use [db name];

*To see all the tables in the db*
show tables;

*To see a databse field formats*
describe [tabale name];

*To delete a db*
drop database [database name];

*To delete a tabale*
drop table [table name];

*Show all data in a table*
select * from [table name];

*Returns the columns and columns information pertaining to the designated table*
show columns form [table name];

*Show unique records*
select distinct [column name] from [table name];

*Update database permission / Privileges*
flush privileges;

*Delete a Column*
alter table [table name] drop column [column name];

*Add a new column to db*
alter table [table name] add column [new column name] varchar (255);

*Change column name*
alter table [table name] change [old column name] .[new column name] varchar(255);

*Make a unique column*
alter table [table name] add unique ([column name]);

*Make a column Bigger*
alter table [table name] modify [column name] varchar(255);

*Delete a unique form table*
alter table [table name] drop index [column name];
