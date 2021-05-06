# Puropse
This is project 1 for Udacity course: Data Engineering. This project does ETL process, create a database based on postgreSQL ans insert processed data into database.

# File
`create_tables.py` is to create differernt tables 
`etl.py` is to do ETL process, which reads data from .json file
`sql_queries` contains SQL langauges that create tables, insert values and query tables.

# Usage
Open terminal and `cd` to dictionary of this project, e.g. `...\project1`. Type `python create_tables.py` and then `python etl.py`

# Test
Open `test.ipynb` to run example SQL queries.

# Schema
|songplays||
|-----------|---------|
|songplay_id|SERIAL|
|start_time|TIMESTAMP|
|user_id|INT|
|level|VARCHAR|
|song_id|VARCHAR|
|artist_id|VARCHAR|
|session_id|INT|
|location|VARCHAR|
|user_agent|VARCHAR|

|users||
|----------|-------|
|user_id|INT|
|first_name|VARCHAR|
|last_name|VARCHAR|
|gender|VARCHAR|
|level|VARCHAR|

|songs||
|---------|-------|
|song_id|VARCHAR|
|title|VARCHAR|
|artist_id|VARCHAR|
|year|INT|
|duration|FLOAT8|

|artist||
|----------|-------|
|artist_id|VARCHAR|
|name|VARCHAR|
|location|VARCHAR|
|latitude|FLOAT8|
|longtitude|FLOAT8|

|time||
|----------|---------|
|start_time|TIMESTAMP|
|hour|INT|
|day|INT|
|week|INT|
|month|INT|
|year|INT|
|weekday|INT|
