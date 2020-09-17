# DataModeling With Apache Cassandra
## Introdcution:
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

In this project, I have performed data modeling with Apache Cassandra and completed an ETL pipeline using Python. To complete the project, I will need to model the data by creating tables in Apache Cassandra to run queries and The ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Data Source: Event Data files
For this project, there is one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
```csv
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```
- The files within this directory will be processed creating a single csv file
- The ouput event data file will contain all data
![fs](Screenshot-event_datafile_new.csv)
## Project Parts:
There are two parts in this project:
* 1. To build an etl pipeline for processing the event data csv files
* 2. To model the database based upon the queries 

### Part I.


