# WindowsFormsApp6

This a tutorial on how to instal the needed SQL server
first, you add a new item
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/b74f6f96-9e72-4f57-bf60-13b64bbef40b)
Then you create a server-based database
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/2a8a06a7-17ac-4004-b693-099c9e8fef9f)
after the database is created in Server Explorer add a new table
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/5a6a3a8f-0bac-4bce-9c7a-84bba82f0eb6)
copy and paste this into the query:

CREATE TABLE [dbo].[tbl_users]
(
	[Id] INT NOT NULL IDENTITY, 
    [username] NCHAR(50) NULL, 
    [password] NCHAR(50) NULL, 
    [ReactScore] INT NULL, 
    [AimScore] INT NULL, 
    CONSTRAINT [PK_tbl_users] PRIMARY KEY ([Id])
)

and press update
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/749cf253-1d96-494b-9470-266880896b41)
after the table have been updated go to the database's properties and copy the path
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/2da02254-1b33-4b36-8005-e41dd8eeb8a9)
paste in path into where it says Data Source. Each location can be seen below
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/2a442538-63dc-431f-98a8-c866c4e9222c)
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/595786f5-2eb9-44c3-bf5a-d05d117d2fdd)
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/7cf984ff-fecc-44a6-920c-d77e3322887b)
![image](https://github.com/Squidnugi/WindowsFormsApp6/assets/77162027/332de59d-12c8-4ad8-b717-d84bf2f07426)

