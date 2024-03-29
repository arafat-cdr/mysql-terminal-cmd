# mysql-terminal-cmd

#### *Create database*
```{mysql}
create databse [databasename];
```

#### *List of all databases*
```{mysql}
show databases;
```
#### *Switch to a database*
```{mysql}
use [db name];
```
#### *To see all the tables in the db*
```{mysql}
show tables;
```
#### *To see a databse field formats*
```{mysql}
describe [tabale name];
```
#### *To delete a db*
```{mysql}
drop database [database name];
```
#### *To delete a tabale*
```{mysql}
drop table [table name];
```
#### *Show all data in a table*
```{mysql}
select * from [table name];
```
#### *Returns the columns and columns information pertaining to the designated table*
```{mysql}
show columns form [table name];
```
#### *Show unique records*
```{mysql}
select distinct [column name] from [table name];
```
#### *Update database permission / Privileges*
```{mysql}
flush privileges;
```
#### *Delete a Column*
```{mysql}
alter table [table name] drop column [column name];
```
#### *Add a new column to db*
```{mysql}
alter table [table name] add column [new column name] varchar (255);
```
#### *Change column name*
```{mysql}
alter table [table name] change [old column name] .[new column name] varchar(255);
```
#### *Make a unique column*
```{mysql}
alter table [table name] add unique ([column name]);
```
#### *Make a column Bigger*
```{mysql}
alter table [table name] modify [column name] varchar(255);
```
#### *Delete a unique form table*
```{mysql}
alter table [table name] drop index [column name];
```
