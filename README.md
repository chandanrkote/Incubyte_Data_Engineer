# Incubyte_Data_Engineer
Assessment-Data Engineer_Role_Chandan R


# My Approach
1. Here I am using CSV File as source system and SQL database as Destination system.
2. Requirements: -Jupyter note book to write python script and ssms for sql storage.
3. Python script includes Object Oriented concept
4. I have created class hospital which includes few methods to perform ETL work
5. Init function will help us to connect to the database and i am passing Servername and database name as parameters.
6. The create_table method table will help us to create new intermediate table/staging table where we load all the data from Source system.
7. The bulk_insert method/function will ingest the data to the created staging table.
8. The Countrytable will perform few operations.
   A. Fetch distinct country names from staging table
   B. Loading country names to the list
   C. Creates the separate table for each country in the list and will insert data of specific country data to the table
