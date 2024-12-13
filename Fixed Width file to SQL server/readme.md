
A **fixed-width file** is a type of plain text file where each field in a record has a fixed, predefined width, measured in characters. This format is commonly used for data exchange in older systems or between systems that require consistent column alignment.

So for fixed with files we need layout.

At source (Data flow) you need to configure the flat file in configre manager, where change format from delimter to fixed width and "in advance" configure columns with input and output width.
![image](https://github.com/SivaKarthik711/SQL_Server_Integration_Services/blob/27e57a2a0999f8810bab0d52ab0c4b8d722c997d/Fixed%20Width%20file%20to%20SQL%20server/Screenshot%202024-12-13%20011231.png)


At destination (ODE) select the table in which data need to be stored in the default server and execute package.
