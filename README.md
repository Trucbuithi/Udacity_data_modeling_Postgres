Data Modeling with Postgres & ETL Pipeline for Sparkify


Introduction

Sparkify is a music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, their data resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. However, this cannot provid an easy way to query the data.

The goal

The purpose of this project is to create a Postgres database and ETL pipeline to optimize queries to help Sparkify's analytics team.


Database & ETL pipeline

Using the song and log datasets, I create a star schema as shown below, which includesone fact table: songplays, and four dimension tables: users, songs, artists and time

