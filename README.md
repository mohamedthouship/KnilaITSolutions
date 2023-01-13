# KnilaITSolutions

Knila IT Solutions
Interview Technical assessment -  .NET core 6.0 - WEB API and Angular

.NET CORE
=========
pre-requiesticts

nuget-packages: Microsoft.EntityFrameworkCore.SqlServer v7.0.1 Microsoft.EntityFrameworkCore.Tools v7.0.1

Database and table generation:

1) Change connectionString in appsettings.json file
2) Open Package Manager Console and execute - a) Add-Migration createdatabase -o Data/Migrations b) update-database
3) Connect MS-SqlServer database and execute "Data/DB_data.sql" for data populate.


Angular
=======

1) Change the 'baseURL' in contact-details.service.ts
2) Please upgrade Angular CLI: 15.1.0 if Angular is lower version
3) Run -- npm install
