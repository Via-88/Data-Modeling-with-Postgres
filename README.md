#  Data Modeling with Postgres & ETL Pipeline for Sparkify 
***
## Udacity Data Engineer Nano Degree Project 1
***
### Introduction

Sparkify is a music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, their data resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. However, this cannot provid an easy way to query the data. 

### The goal
***
The purpose of this project is to create a Postgres database and ETL pipeline to optimize queries to help Sparkify's analytics team. 

### Database & ETL pipeline
***
Using the song and log datasets, I create a star schema as shown below, which includes 
* one fact table: **songplays**, and 
* four dimension tables: **users**, **songs**, **artists** and **time**.

<img src="star_schema.jpg" alt="drawing" width="400"/>

### Exmaples queries
***
1. What are the top 10 most popular songs in 2018 for the users on different levels? How long are the songs in general? What is the distribution of their released years?
2. Who are the most popular artists in 2018? And where are they from?
