As we know some date files can have millions of records, so performing tasks like index on its multiple columns takes a more time because of its sequential pattern. 
So here by SSIS sequence container we can break this sequential pattern into parllel processing for differemt columns exists in the data file.
Here I have created table in the database using SQL server and connected to the csv data source using data flow task, later prerformed the index task using sequence container.

![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/e43c9ecce81686fb90fd847412ebd77b585bdf9c/Sequence%20Container/Screenshot%202024-12-15%20015258.png)

![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/e43c9ecce81686fb90fd847412ebd77b585bdf9c/Sequence%20Container/Screenshot%202024-12-15%20015607.png)


