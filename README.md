# Movies-ETL

## Challenge Overview

#### Amazing Prime is preparing for a hackathon and have gathered data from both Wikipedia and Kaggle. To prepare the data, we need to use the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them and joining them together, and loading the cleaned dataset into a SQL database.


## Challenge Summary
### Deliverable 1 – Write an ETL Function to Read the Data Files
The ETL_function_test.ipynb file includes:
-	An ETL function that reads in the three primary data files
-	Converts the Wikipedia JSON file to a Pandas DataFrame
-	Converts the Kaggle metadata file to Pandas DataFrame
-	Converts the MovieLens ratings datafile to a PandasDataframe

### Deliverable 2 – Extract and Transform the Wikipedia Data
The cleaned Wikipedia data is converted to a Pandas DataFrame, and the DataFrame is displayed in the ETL_clean_wiki_movies.ipynb file.

### Deliverable 3 – Extract and Transform the Kaggle Data
The Kaggle metadata and MovieLens rating data are then converted into separate DataFrames. The Kaggle metadata DataFrame and Wikipedia DataFrames are then merged to create the movies_df DataFrame. Finally, MovieLens rating data DataFrame and movies_df DataFrame were merged to create the movies_with_ratings_df.

### Deliverable 4 – Create the Movie Database
Finally, the movies_df DataFrame and MovieLens rating CSV data were added to a SQL database.

** Of note, I was unable to upload the movies_metadata.csv due to the large file size.
