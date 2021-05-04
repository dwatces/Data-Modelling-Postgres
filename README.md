This Project entails working with a startup, Sparkify, to create a Postgres database with tables designed to optimize queries on
song play analysis. The role given has been to create a database schema and ETL pipeline for this analysis.


Star Schema with a single fact table being songplays and four dimension tables of users, songs, artists, and time is included in Capture.PNG


File Explaination:
Capture.PNG - Start Schema with fact and dimension tables
create_tables.py - Drops and creates tables
etl.ipynb - Reads and processes a single file from song_data and log_data, loading data into tables
etl.py - Reads and processes files from song_data and log_data, loading data into the tables
README.md - Provides documentation of the project
sql_queries.py - Contains SQL queries to drop, create, and insert into tables
test.ipynb - Tests selecting data from all tables to check all works

Running Scrips:
python scripts.create_tables
python scripts.etl

Example queries:
SELECT COUNT(level) FROM users; Number of users with each membership level
# Data-Modelling-Postgres
