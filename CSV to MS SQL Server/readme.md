Through this exercise I would like to move the flat file( csv) to the destination source i.e MS SQL server using SSIS toolbox attributes.

When we execute the package, we need to provide server and database to store the flat file data. So in **connection manager** we need to provide the details.
![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/ed05836132b8b5203c0eb9b38e5285d954b72b07/CSV%20to%20MS%20SQL%20Server/Screenshot%202024-12-12%20170629.png)
As I am using SQL Server 2019
[**NOTE**]: provider should be changed [Native OLE DB\ Microsoft OLE DB Provider for SQL Server]
![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/ed05836132b8b5203c0eb9b38e5285d954b72b07/CSV%20to%20MS%20SQL%20Server/Screenshot%202024-12-12%20170617.png)

![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/ed05836132b8b5203c0eb9b38e5285d954b72b07/CSV%20to%20MS%20SQL%20Server/Screenshot%202024-12-12%20171212.png)

Final result 
![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/f6d9a814977fa695f1eb38f51c3dfc40382a0a0b/CSV%20to%20MS%20SQL%20Server/Screenshot%202024-12-12%20172728.png)
