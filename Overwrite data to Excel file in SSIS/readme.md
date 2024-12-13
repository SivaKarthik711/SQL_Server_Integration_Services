In this excersie, I would like to demonstrate two operations:-
- 1) Import data from SQL server to excel sheet
  2) When package is executed again, preexisting data in the excel is dropped and new data is overwritten into Excel sheet.
 
While importing data from the SQL, some columns have varchar data type but excel doesn't accept varchar. So we need to change the data format while configuring the data flow task.
![image]()
While overwriting the pre existing data we need to delete the existing data, so we need to run a script top of data flow task
![image]()
