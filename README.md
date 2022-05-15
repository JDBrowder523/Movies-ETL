# Movies-ETL

## Purpose

The purpose of this analysis is to take movie data from Wikipedia and Kaggle and perform data cleaning in order to Extract, Transform, and Load (ETL) the data into a single table that can be loaded into PostgreSQL.

## Results

Extract: The raw data files were imported using Pandas and Python.  This was performed by creating a function that read each data source file and created DataFrames for each movie data file.

Transform: The data was then cleaned up by removing duplicates, unnecessary columns of data, renaming the remaining columns, and merging the DataFrames into a single DataFrame.

Load: The merged DataFrame was loaded directly into PostgreSQL and a query was performed to make sure all of the data had been loaded.

##Summary

Using ETL is crucial to being able to manipulate large datasets.  It allows for more readable data through the cleaning process where unnecessary information can be removed and column names can be updated to provide a clearer description of the data.