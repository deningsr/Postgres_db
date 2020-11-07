## Udacity Data Engineering NanoDegree Project 1: Postgres Database

#### Project rubric can be found here: https://review.udacity.com/#!/rubrics/2500/view

#### This project creates an ETL Pipeline and Postgres database for an imaginary startup named Sparkify.
#### The data contains song and user data the company has collected from its streaming app.

#### The project respository contains three python scripts. They can all be run in the MacOS Terminal or Windows Command Line in the order below:

* <code>create_tables.py</code>: Connects to the Sparkify database, create and drops all tables.

* <code>sql_queries.py</code>: Drops tables if they already exist. Creates all tables in the database and their corresponding INSERT statements.

* <code>etl.py</code>: Contains the ETL Pipeline from processing the raw data to populating the database.
