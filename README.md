# Sparkify Database

## This project creates an ETL Pipeline and Postgres database for an imaginary startup named Sparkify.
## The data contains song and user data the company has collected from its streaming app.

## The project respository contains three python scripts. They can all be run in the MacOS Terminal or Windows Command Line in the order below:

* create_tables.py: Connects to the Sparkify database, create and drops all tables.

* sql_queries.py: Drops tables if they already exist. Creates all tables in the database and their corresponding INSERT statements.

* etl.py: Contains the ETL Pipeline from processing the raw data to populating the database.