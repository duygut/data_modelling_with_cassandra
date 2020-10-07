# data_modelling_with_cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app, particularly interested in understanding what songs users are listening to.

In that project below steps implemented:

1. Created denormalized dataset 
2. Model the data tables keeping in mind the queries that needed to run
3. Loaded the data into tables that created in Apache Cassandra


Below python libraries have been used.

* pandas
* cassandra
* re
* glob
* numpy
* json
* csv


The event_datafile_new.csv contains the following columns:

* artist
* firstName of user
* gender of user
* item number in session
* last name of user
* length of the song
* level (paid or free song)
* location of the user
* sessionId
* song title
* userId


### Project Steps
1. Designed tables
2. Create Apache Cassandra Keyspace 
3. Create table based on the provided queries
4. Load data for each tables
5. Test with `Where` clause
