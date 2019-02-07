# Implementation-of-Hive
IBM Hadoop Project

The project aims to display show-to-channel relationship is Many-to-Many. In other words, each show might appear on many channels, and each channel might broadcast many shows.

The description of the data is as below
1. TV show titles do not have spaces
2. Channels have 3 letters
3. TV show titles can appear multiple times, with different counts
4. A TV show and channel combination might appear multiple times
5. TV shows could appear on multiple channels
6. The output should have no commas or punctuation, only 1 space between the TV show title and number.

Problem statement:
1. What is the total number of viewers for shows on ABC?
2. What is the number of viewers for the BAT channel?
3. What is the most viewed show on ABC channel?
4. What are the aired shows on ZOO,NOX, ABC channels ?



 Hive Commands          |  Functions 
 ------------           |  -------------
 SHOW DATABASES         |  It will show all the databases in Hive
 CREATE EXTERNAL TABLE  |  It creates a table in HDFS directory
 CREATE INTERNAL TABLE  |  It will store the table in warehouse directory i.e /user/hive/warehouse/{db name}/tablename
 LOAD DATA LOCAL INPATH |  Loading a file from the local directory into Hive table
 LOAD DATA INPATH       |  Loading a file from HDFS directory into Hive table
 
 
 
