# Movies-ETL
Week 8: Using ETL to Collect, Import and Process Data
## Resources
- Python
- Jupyter Notebook
- SQL
- pgAdmin4
- PostgreSQL
- Data: wikipedia-movies.json, movies_metadata.csv, ratings.csv

## Overview
In this module, I utilized three disparate data sources to create three seperate dataframes using ETL. I learned how to extract, transform and to use ETL to create data pipeines. ETL is vital in Data Analytics due to the fact that it is frequently the first step in general analysis. Therefore, this modules challenge is to create an automated pipeline that takes in new data. To create this pipeline, I will be refactoring the code from this module as seen in Movielens Extract.ipynb to create a function that takes in the three aforementioned data files (Wikipedia Data, Kaggle Metadata, MovieLens rating data). With these three data sources incorporated into my function, I will perform the ETL pipeline process through adding the data to a PostgreSQL database. 

This Module Challenge consists of 4 Deliverables:
- 1. Write an ETL Function to Read Three Data Files
- 2. Extract and Transform the Wikipedia Data
- 3. Extract and Transform the Kaggle Data
- 4. Create the Movie Database

## Results

1.
<img width="1117" alt="ETL 1" src="https://user-images.githubusercontent.com/95828604/154018171-65605a7a-3d84-4902-8f13-95314a2e1eb4.png">

2. 
<img width="1112" alt="ETL 2" src="https://user-images.githubusercontent.com/95828604/154018560-80dc0d29-7e6d-420a-9fc3-2b341c1acdeb.png">

3. 
<img width="1099" alt="ETL 3" src="https://user-images.githubusercontent.com/95828604/154018979-efdc5fc4-9d5f-4c13-99e9-7881aad989de.png">

<img width="1101" alt="ETL 4" src="https://user-images.githubusercontent.com/95828604/154019024-6164771b-f43a-45f0-9473-d8faf6295200.png">

4. 

## Conclusion

The conclusion of this Module 8 Challenge is the creation of a function that collects, cleans and organizes movie data from all three disparate sources into a pipeline that merges and transforms the data. From here, the data is uploaded into a database in PostgreSQL. 
