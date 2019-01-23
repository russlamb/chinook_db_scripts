
# Chinook Database Scripts
This repository contains pre-built SQL scripts to generate all tables and data for an example database called the Chinook database.  

For more information about the Chinook database see the archived [codeplex](https://archive.codeplex.com/?p=chinookdatabase) page or the official [github page](https://github.com/lerocha/chinook-database)

## About
### The Example Database
The Chinook Database is a database used for learning or testing purposes.  It is modeled on a music library and purchase history of music Tracks as well as the Invoices and Customers that bought each track.

![Chinook Object Schema](https://i.imgur.com/dQVcUUg.jpg)

The scripts in this repository are the results of building the [Chinook database project](https://github.com/lerocha/chinook-database) in Visual studio.  These scripts can be run on a database to create a fully populated database.

### Get Started Easily
The official Chinook project requires Visual Studio to build and generate the SQL for several database dialects.  This repository was created to help people who don't have access to Visual Studio but want to use the Chinook sample database.  

By generating and saving the scripts in this repository, anyone can easily download and run this script to have a populated database quickly without having to use Visual Studio.  

The Chinook database is desirable because it is an open-source, easily portable, free example database for multiple database platforms.  It contains logical relationships between objects, e.g. Artist and Track, and is a familiar subject matter.  This makes the Chinook database a good teaching tool for people learning to use databases.  

## Usage

### Choose a Script
Find the SQL dialect for your database.  Current scripts include [MySQL](https://www.mysql.com/), [Oracle](https://www.oracle.com/database/), [SQLite](https://www.sqlite.org/index.html), and [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-editions-express).  

|Database Type|Script|
|--|--|
|MySQL  | Chinook_MySql.sql |
|SQLite  | Chinook_Sqlite.sql |
|Oracle| Chinook_Oracle.sql |
|Microsoft SQL Server| Chinook_SqlServer.sql |

### Run the Script
Once you have selected a script for your database type, run the script on your database.  

For SQL Server, MySQL, and Oracle databases, a new Database called "Chinook" is created on the server instance.  For SQLite, the script creates the tables directly in the database file.  

### Use the Data
Once the script runs and creates the tables and data, you can immediately start using the data to run queries or populate sample projects.
