# Movies-ETL.

## Purpose
   The purpose of the following project was to take multiple sets of movie data two of them being csv files and one of them being json data type. Then after cleaning, merging, transforming and merging again, then creating a database in the process for movies and ratings, and finally creating a connection between jupyter notebook and PostgreSQL database. First the Wikipedia data needed to be loaded and extracted and then the Kaggle data needed to be extracted. Then the cleaning process for the Wikiedia data begins. We also filter out the non-essentials such as shows and and create a new list of with a better list of what we need in out database to use. With cleaning the Wikipedia data we remove duplicateds and removive null columns and vales, and convert data into string values, and clean the box office, budget, release, and running time data. After we clean the kaggle data, by having a have all the different language movies be under one name. Then creating date forms, and renaming the dataframe names to be more suitable for our final databse. And after merging the Wikipedia and Kaggle dataframes and after transforming those dataframe merge then with the rating data. And for the final step we create and a database and connect that database to PostgreSQL and import that data into a table. Our final product has two different tables first having the imported movies database and then importing the ratings database.


<img width="505" alt="movies_query" src="https://user-images.githubusercontent.com/97326526/165013893-691afe1e-2490-46be-b03a-3b2e256e1101.png">

-----------------------------------------------

<img width="321" alt="ratings_query" src="https://user-images.githubusercontent.com/97326526/165013902-cf50b450-4c10-4290-b55a-12e31f4ecfbb.png">
