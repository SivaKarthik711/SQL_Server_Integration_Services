In this excersie, I would like to demonstrate two operations:-
- 1) Import data from SQL server to excel sheet
  2) When package is executed again, preexisting data in the excel is dropped and new data is overwritten into Excel sheet.
 
While importing data from the SQL, some columns have varchar data type but excel doesn't accept varchar. So we need to change the data format while configuring the data flow task.


![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/a808392eac6a9d2009fe63e594f08b31711fa523/Overwrite%20data%20to%20Excel%20file%20in%20SSIS/Screenshot%202024-12-13%20164559.png)


While overwriting the pre existing data we need to delete the existing data, so we need to run a script top of data flow task
![image]()
