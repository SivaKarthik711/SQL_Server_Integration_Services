As we know some date files can have millions of records, so performing tasks like index on its multiple columns takes a more time because of its sequential pattern. 
So here by SSIS sequence container we can break this sequential pattern into parllel processing for differemt columns exists in the data file.
Here I have created table in the database using SQL server and connected to the csv data source using data flow task, later prerformed the index task using sequence container.

![image]()

![image]()

![image]()
