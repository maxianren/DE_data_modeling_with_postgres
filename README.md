The purpose of this project is to facilitate analytics and queries by creating a postgre database for the startup, Sparkify.

the data source 2 directories of JSON file, song dataset and log dataset. The task is to create a ETL pipeline and transform the original datasets into 1 fact table, songplays, and 5 dimension tables, users, artists, songs, time. 

this folder has 3 *.py files that contain the core code of this project, 1 notebook that explains the ETL process, and another notebook that tests the code during the compile.
the 3 *.py files are:
- sql_querues.py: it has the sql code about create, drop and insert tables
- create_tables.py:it create the connection and implement the sql code to drop existing tables and create new ones
- etl.py: with preparation of other 2 *.py files, it is ready to extract data from JSON files using Pandas and put them into tables previously created.

the step to implement the code is:
- active the Terminal
- execute: python create_table.py
- execute: python etl.py
after that, you can test the result using notebook test.ipynb
NB make sure to shut down any other running terminals and kernels when executing the process

you can make queries to understand the favorite type of music or artist for certain clients, or the purchase histories of certain clients over a period of time and even make yoy analysis 
# DE_data_modeling_with_postgres
