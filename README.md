# Flight Delay Analysis (Google Sheets + QUERY)

## Overview

This project analyzes flight delay data using Google Sheets and SQL-like queries (QUERY function).
The focus is on cleaning the data and creating simple aggregated views to compare airlines, airports, and delays over time.

## Data Preparation

- Removed rows with missing delay values  
- Filtered out extreme values (delay > 300 minutes)  
- Selected relevant columns for analysis  

## Analysis

- Calculated average delay per airline and compared performance  
- Identified best and worst performing airports based on average delay  
- Observed that some airports have negative average delays (early arrivals on average)  
- Analyzed delay trends over time  

## Notes

The project uses basic SQL logic (filtering, grouping, aggregation) applied in Google Sheets to explore the dataset and extract simple insights.

## Dataset & Dashboard

Google Sheets file: https://docs.google.com/spreadsheets/d/1pyqLzdTc8zTiu7pnnXn3_0baneHL7kIHTvywgtdRd3I/edit?usp=sharing
