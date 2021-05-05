# Puropse
Project1

# Schema
## songplays
|songplay_id|SERIAL|
|-----------|---------|
|start_time|TIMESTAMP|
|user_id|INT|
|level|VARCHAR|
|song_id|VARCHAR|
|artist_id|VARCHAR|
|session_id|INT|
|location|VARCHAR|
|user_agent|VARCHAR|

## users
|user_id|INT|
|----------|-------|
|first_name|VARCHAR|
|last_name|VARCHAR|
|gender|VARCHAR|
|level|VARCHAR|

## songs
|song_id|VARCHAR|
|---------|-------|
|title|VARCHAR|
|artist_id|VARCHAR|
|year|INT|
|duration|FLOAT8|

## artists
|artist_id|VARCHAR|
|----------|-------|
|name|VARCHAR|
|location|VARCHAR|
|latitude|FLOAT8|
|longtitude|FLOAT8|

## time
|start_time|TIMESTAMP|
|----------|---------|
|hour|INT|
|day|INT|
|week|INT|
|month|INT|
|year|INT|
|weekday|INT|

