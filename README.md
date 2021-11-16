# Amazing Prime - ETL 
## Project Overview
For this projected we partnered with Britta to create and automated pipeline that takes in new data, performs the appropriate transformation, and loads the data into existing tables. 
## Resources
-	Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
-	Software: Python 3.7.6, Anaconda Version 4.10.3, Jupyter Notebook, PostgreSQL, pgAdmin 4

## Results

### Function to Extract Transform and Load data from three files 
We created a function that uses informaiton for a Wikipedia JSON file, Kaggle and a MovieLens csv to create three seperate DataFrames

### Extract and Trasform Wikipedia Data
We needed to filter and clean our data so that it is easy to read

### Extract and Transform the Kaggle and Ratings Data
Using tools we learned in previous excercies we again cleaned up the data from our remaining two data sources. 

### Extract and Transform the Kaggle and Ratings Data
Once the data was clean, we loaded it to a SQL database so that is easy to query. 



## Summary 
Through our activites we were able to create a database that can be easily refresed to find out specific infomraiton on a variety of movies.  
