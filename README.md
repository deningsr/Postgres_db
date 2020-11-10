## Udacity Data Engineering NanoDegree Project 1: Postgres Database

#### Project rubric can be found here: https://review.udacity.com/#!/rubrics/2500/view

## Purpose

#### This project creates an ETL Pipeline and Postgres database for an imaginary startup named Sparkify.The data contains song and user data the company has collected from its streaming app. The project is meant to display my understanding of relational databases and data processing.

## Running the Project

#### The project repository contains three python scripts. They should be run in the order below:

* <code>create_tables.py</code>: Connects to the Sparkify database, create and drops all tables.

* <code>sql_queries.py</code>: Drops tables if they already exist. Creates all tables in the database and their corresponding <code>INSERT</code> statements.

* <code>etl.py</code>: Contains the ETL pipeline from processing the raw data to populating the database.
