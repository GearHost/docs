#Connecting to a SQL database using SQL Server Management Studio 2014

This article covers 3 steps needed to connect to your SQL database with GearHost. The steps are:

1. [Install SQL Server Management Studio 2014 (SSMS)](https://www.microsoft.com/en-us/download/details.aspx?id=42299)
2. [Gather your SQL Server database credentials](https://www.gearhost.com/documentation/connecting-to-a-sql-database-using-sql-server-management-studio-2014#user-content-gather-your-sql-server-database-credentials)
3. [Connect to your SQL Server Database using SSMS](https://www.gearhost.com/documentation/connecting-to-a-sql-database-using-sql-server-management-studio-2014#user-content-connect-to-your-sql-server-database-using-ssms)

##Install SQL Server Management Studio 2014 (SSMS)
1. Download and install [SQL Server Management Studio 2014](https://www.microsoft.com/en-us/download/details.aspx?id=42299)

GearHost uses SQL Server 2014 and **older versions of SQL Server Management Studio will not work correctly.** Please ensure you are using SSMS 2014.

##Gather your SQL Server database credentials
1. [Log in to your GearHost Account](https://my.gearhost.com/account/login)
2. Click on the Databases menu
3. Locate the Database you want to connect to and click it to open the database details.
4. Locate the username that is the same name as your database. This is your primary database user that we create for you by default.
5. Toggle the show/hide password "eye" icon to the right of the username to show the password.
6. At the bottom of the page take note of the SQL Server Name which you will use. It's format is *mssqlx.gear.host*.

> Note that ONLY your primary username can connect to the SQL Server database using Microsoft SQL Server Management Studio. While additional users have access to your database in your code they do not have access via SSMS.

##Connect to your SQL Server Database using SSMS
1. Launch Microsoft SQL Server Management Studio 2014
2. The Server type should be *Database Engine*
3. Server name should be *mssqlx.gear.host* (refer to your steps above to the correct SQL Server name)
4. Authentication is *SQL Server Authentication*
5. Login is your primary database username, the same name as your database name
6. Your password is the password as revield above using the show/hide password toggle icon.
7. Click Connect


----------
**Tip:** If you're still having issues, please feel free to open a support ticket.