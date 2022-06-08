# Movies-ETL

## Project Overview
Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Resources
- Data Source: movies_metadata.csv, ratings.csv, wikipedia_movies.json
- Software: Jupyter Notebook, PostgreSQL

## Challenge Overview
Consists of four technical analysis deliverables:

Deliverable 1: Write an ETL Function to Read Three Data Files
Deliverable 2: Extract and Transform the Wikipedia Data
Deliverable 3: Extract and Transform the Kaggle data
Deliverable 4: Create the Movie Database

## Results

### Deliverable 1: Write an ETL function to read three data files
ETL_function_test.ipynb
![wiki_movies_df](https://user-images.githubusercontent.com/87085239/172522777-935495e1-e378-4607-98b4-5daf0a250787.png)

![kaggle_metadata](https://user-images.githubusercontent.com/87085239/172522795-b1b74195-86bb-421d-aa9b-f5ef1a3c718a.png)

![ratings](https://user-images.githubusercontent.com/87085239/172522824-23aa3e4b-cee6-4e2c-91df-32178e65b85d.png)

### Deliverable 2: Extract and Transform the Wikipedia Data
ETL_clean_wiki_movies.ipynb
![4_wiki_movies_df](https://user-images.githubusercontent.com/87085239/172522909-9f1b0e8b-ddd5-4619-816b-50121f6252e7.png)

![5_wiki_movies_columns](https://user-images.githubusercontent.com/87085239/172522949-e5b2f9a7-4aca-4ce2-8011-70cf28ac8cdc.png)

### Deliverable 3: Extract and Transform the Kaggle Data
ETL_clean_kaggle_data.ipynb

![7_movies_df](https://user-images.githubusercontent.com/87085239/172523023-cfdbf87d-db61-4e85-b14a-9ceef1bff6de.png)

### Deliverable 4: Create the Movie Database
ETL_create_database.ipynb

![8_etl](https://user-images.githubusercontent.com/87085239/172523057-ea4fece9-f355-4d5c-b5eb-7936eed8de94.png)

## Summary

After loading the movies and ratings data into Postgres, here are the record counts.

![movies_query](https://user-images.githubusercontent.com/87085239/172523125-06ff312a-22ea-46b4-8d32-39132216e751.png)

![ratings_query](https://user-images.githubusercontent.com/87085239/172523138-c6ed9caf-25ed-4649-b3a8-af01a08198e5.png)
