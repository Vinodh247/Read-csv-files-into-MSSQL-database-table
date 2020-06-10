# Read-csv-files-into-MSSQL-database-table

Read all the CSV files from a directory, processed it with filtering the keyword and then inserting the required columns only from the pandas dataframe to MSSQL database table using SQLAlchemy library. Set to insert chunksize limits into SQL table, hence there is no issues with the size of the records you are inserting. My 8GB memory system inserted 4,430,0000+ (4.3Crore records) in 53 Mins. The script can be used on any platform like windows or linux.
