In the procedure folder  have to setup 'numara' sql database


Stored Procedure is considered that Like SQL statement stored to database server. Stored Procedure is take parameter like programming language and According to this parameter is called and sends value. Stored Procedure is work too fast because It is stored to database server. Stored procedure is compiled when first time it run. afterwards It is not compiled while running. For Example;If to the data server is tied by Sql statement of anyone programming language This is waste of time . For example SQL DATABASE There are two tables.

personnel table. personnelD departmentID Name Surname department table. departmentID department We will add new a personnelnow. CREATE PROCEDURE addpersonnel( @newdepartmentID INT, @newName varchar(50) @newSurname varchar(50) ) AS Insert into personnel(departmentID,Name,Surname) Values(newdepartmentID,newName,newSurname) Declare @newpersonnelID INT SET @newdepartmentID = SCOPE_IDENTITY() "return last value.##

EXECUTE...

USE[database name] GO EXEC addpersonnel '1','tom','tom'
