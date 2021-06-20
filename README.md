# C# MVC application

This project uses .Net Core MVC 5 to illustrate the basic skeleton of an e-commerce site

Files:
LaptopStoreDB.zip - contains a database backup; extract the files and use ATTACH from SQL Server Mgmt Studio to create the database
ProductTable.SQL - contains a SQL script to create the table needed for the project to run (this is an alternative to attaching the DB)
LaptopStore.sln - C# project
LaptopStore folder - project files

Before running:
1. create the database either using the backup provided or manually using the ProductTable.sql script
2. Edit the connection string in the LaptopStore\appsettings.json file as needed
