# Movies ETL
## Overview of the Project
In this project movie data was gathered from Wikipedia and Kaggle, cleaned and combined, and then and saved into a SQL database. In order to ensure clean, usable data was created, it was necessary to follow the ETL process: extract, transform and load.  Specifically, the Wikipedia and Kaggle data were extracted separately and had to be loaded using different methods.  Each was of the datasets was transformed by deleting or re-shaping the data and ultimately joining them together.  Finally, the cleaned dataset was loaded into a SQL database where it can be easily queried.  The idea behind ETL is straightforward. Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. ETL breaks this problem into three steps, or phases: Extract, Transform, and Load.

## Coding Examples
A good deal of code was created in Python to perform the ETL on the movie data.  Below is an example of the code where alternative titles in the Wikipedia data set were combined to lessen the amount of columns in the overall data set.  

![python example code #1](screenshots/python_coding_ex1.png)

![python example code #1](screenshots/python_coding_ex1.png)

## Data Table Examples
![Table showing cleaned movie data](screenshots/movie_data.png)

![Table showing cleaned movie data](screenshots/merged_movie_data.png)

![Table showing movie ratings](screenshots/movie_ratings.png)
