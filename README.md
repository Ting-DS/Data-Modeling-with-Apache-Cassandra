# Data-Modeling-with-Apache-Cassandra

## Project Description
Sparkify is a startup in the music streaming industry, aims to analyze the data they have collected regarding songs and user activity on their new music streaming app. The data science team is particularly interested in understanding **what songs users are listening to**. Currently, they face difficulties in querying the data effectively since it is stored in a directory of CSV files, capturing user activity on the app.

The objective of this project is to create an **Apache Cassandra NoSQL database** capable of answering queries about user activity data. The project will leverage data modeling with Apache Cassandra and complete an **ETL pipeline using Python driver**.

## File Overview

- `event_data/` - contains our data for user sessions in the streaming app in csv format. files are partitioned by day. (e.g. `2018-11-02-events.csv`)
- `images` - contains an image of what our data looks like after an ETL process
- `data_modeling_with_cassandra.ipynb` - Has two parts:
  - ETL pipeline for processing the event files and compiling them into a single csv with the desired columns
  - Data modeling examples that show three queries and the creation of three tables to serve those queries

<div align="center">
  <img src="https://github.com/Ting-DS/Data-Modeling-with-Apache -Cassandra/blob/main/images/image_event_datafile_new.jpg" width="60%">
</div>

