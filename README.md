# Movies-ETL

## Challenge Overview

### Write an ETL function to read the three data files
- Create a function to read the three data files: Wikipedia movie data, Kaggle metadata, and MovieLens ratings. The function was named extract_transform_load.
- Read the Kaggle metadata and MovieLens ratings as Pandas data frames. Open the Wikipedia json file and convert it to raw data before reading the raw data as a Pandas dataframe. 
- Reassign variables to make a path to the data files.
- Check that files have been successfully converted to a data frame.

### Extract and transform the Wikipedia data
- Add module code for cleaning movies (function).
- add function that reads the 3 data files.
- Edit deliverable one function to make a list that filters out movies from the wiki_movies_raw file. Read the cleaned movies as a data frame.
- Write a try-except block to catch errors, drop duplicates, and print exceptions.
- Write a list to keep non-null values, and make a wikipedia movies data frame. 
- Produce a variable to hold non-null values from the box office column. Change box office data to string values. Write expressions to match the six elements of box office data from form one and the three elements from form two.
- Clean the code in the budget, release date, and running time columns. 
- Create a path to the Wikipedia, Kaggle metadata, and MovieLens rating files. Make three variable equal to function created in deliverable one. Set wiki_movies data frame equal to the Wiki_file variable.

### Extract and transform the Kaggle Data
- Add function to read and create kaggle_meta_data and ratings data_frames. Add all the code from deliverable two. Add code to clean kaggle metadata.
- Merge wiki_movies_df and kaggle_metadata. Name the new data frame movies_df. 
- Clean the movies_df data frame, Kaggle, and Wikipedia columns as arguments. Filter the movies_df data frame. 
- Merge the ratings data frame with the movies_df data frame. Rename the data frame to movies_with_ratings_df. 
- Make a file path to Wikipedia data, Kaggle metadata, MovieLens rating data files. set three variables equal to function created in deliverable one. Set data frames equal to file names in step eleeven. Check that wiki_movies_df as the same as in deliverable two. 

### Create the movie database
- Rename ETL_clean_kaggle_data.ipynb to ETL_create_database.ipynb. 
- Add movies_df data frame annd MovieLens rating CSV data to SQL database. 

















