# Movies-ETL

Extract. Transform, Load

Create an automated pipeline that takes in new data, performs

## Step 1:
In Step 1, create a function to read in the three files and give it a name.

In Step 2, read in the Kaggle metadata and MovieLens ratings CSV files as Pandas DataFrames.

In Step 3, open the Wikipedia JSON file and use the json.load() function to convert the JSON data to raw data.

In Step 4, read in the raw Wikipedia movie data as a Pandas DataFrame.

In Step 5, use the code provided to return the three DataFrames.

In Step 6, use the variables provided to create a path to the Wikipedia data, the Kaggle metadata, and the MovieLens rating data files.

In Step 7, set the three variables in Step 6 equal to the function created in Step 1.

In Step 8, set the DataFrames from the return statement equal to the file names in Step 6. In this step, you are reassigning the variables created in Step 6 to the variables in the return statement.

In Steps 9-11, check that all three files are converted to a DataFrame. 
The wiki_movies_df DataFrame

![image](https://user-images.githubusercontent.com/95730183/155902843-5ffd6bb0-a66a-4422-83eb-3dec085b2c23.png)



## Step 2: 
In Step 1, add the code from this module for the clean movie function that takes in the argument "movie".
In Step 2, add the function you created in Deliverable 1 that reads in the three data files.
In Step 3, inside the function you created in Deliverable 1, remove the code that creates the wiki_movies_df DataFrame from the wiki_movies_raw file, then write a list comprehension that filters out TV shows from the wiki_movies_raw file.
In Step 4, write a list comprehension to iterate through the cleaned wiki movies list that you created in Step 3.
In Step 5, read in the cleaned movies list from Step 4 as a DataFrame.
In Step 6, write a try-except block that will catch errors while extracting the IMDb IDs with a regular expression string and dropping any imdb_id duplicates. If there is an error, capture and print the exception.
In Step 7, write a list comprehension to keep the columns that have non-null values from the DataFrame created in Step 5, then create a wiki_movies_df DataFrame from the list.
In Step 8, create a variable that will hold all the non-null values from the "Box office" column.
In Step 9, convert the box office data created in Step 8 to string values using the lambda and join functions.
In Step 10, write a regular expression to match the six elements of form_one of the box office data.
In Step 11, write a regular expression to match the three elements of form_two of the box office data.
In Step 12, add the parse_dollars() function.
In Step 13, add the code that cleans the box office column in the wiki_movies_df DataFrame using the form_one and form_two lists created in Steps 10 and 11, respectively.
In Step 14, add code that cleans the budget column in the wiki_movies_df DataFrame.
In Step 15, add code that cleans the release date column in the wiki_movies_df DataFrame.
In Step 16, add code that cleans the running time column in the wiki_movies_df DataFrame.
In Step 17, use the variables provided to create a path to the Wikipedia data, the Kaggle metadata, and the MovieLens rating data files.
In Step 18, set the three variables in Step 17 equal to the function created in Deliverable 1.
In Step 19, set the wiki_movies_df equal to the wiki_file variable.
In Step 20, check that your wiki_movies_df DataFrame looks like this image:
The ratings DataFrame:

![image](https://user-images.githubusercontent.com/95730183/155902959-4d0bafeb-df27-4525-968d-cc0a420a8e43.png)


In Step 21, add the columns from wiki_movies_df DataFrame to a list:

 ![image](https://user-images.githubusercontent.com/95730183/155902949-0977dff7-fb8a-4738-ad09-05b699e2fefb.png)


## Step 3


## Step 4

