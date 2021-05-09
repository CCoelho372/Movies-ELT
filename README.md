# Movies-ELT

## Purpose

Amazing Prime wants to stay updated daily on data from Wikipedia, Kaggle, and MovieLens. To do this efficiently code has been refractored to run more efficiently. There was one function created that takes in the files from three data sources and is submitted through the ETL process and submitted to a PostgreSql.

## Deliverable 1: Write an ETL Function to Read Three Data Files

This ETL function will read all three data files and create three data frames. 

## Deliverable 2: Extract and Transform the Wikipedia Data

This ETL function will take the Wikipedia data and merge it with the Kaggle data. Try and Except blocks are used to determine if any errors occur during the process,

## Deliverable 3: Extract and Transform the Kaggle data

This ETL function took Kaggle metadata and MovieLens rating data and transformed it into data frames. The kaggle data fram and the wikipedia data frame was merged to create a movies data frame. This was then merged with the MovieLens data frame to assigned ratings to each movie.

## Deliverable 4: Create the Movie Database

This function will put the data into a SQL database.This will allow for easier data Analysis on movie ratings moving forward.


## Summary

The refactored code will allow for a more efficient ETL process in analyzing and summarizing the Wikipedia, Kaggle, and Movie Lens Data. This will lead to Amazing Prime to provide the most up to date movie ratings and information about movies to their customers.
