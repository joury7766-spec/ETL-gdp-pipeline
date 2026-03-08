# ETL Pipeline for GDP Data

This project implements an ETL (Extract, Transform, Load) pipeline using Python.

## Project Overview
The pipeline extracts GDP data from a Wikipedia page, cleans and transforms the data,
and loads it into both a CSV file and a SQLite database.

## Technologies Used
- Python
- Pandas
- BeautifulSoup
- SQLite
- Requests

## ETL Steps

### Extract
Data is extracted from a Wikipedia page containing GDP information.

### Transform
The GDP values are cleaned and converted from millions to billions.

### Load
The transformed data is stored in:
- CSV file
- SQLite database

### Query
A SQL query is executed to retrieve countries with GDP ≥ 100 billion USD.

## Output
The pipeline outputs a list of countries meeting the query condition.
