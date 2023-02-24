# Data-Science-PBL
Implementation of Movie Recommendation System (In Python)

Using the "Movie.csv" dataset and performing various data science steps to build the required Recommendation System.

Steps: 
1. Importing and Analysing the data.
   > Using the read_csv() function available in Python or the upload() function available on the Google Colab platform to read the dataset.
   > Understand the dataset by using the head() and columns.

2. Selecting the features for the System.
   From the available set of data about a movie (column names) select the relevant columns on which the selection will take place.
   Here, we select "**_keywords, cast, genres and director_**" as the features.
   
 3. Pre-processing the data.
    This step is crucial and needs to be performed before any form of decision making is performed. This involves:
    > checking for empty values
    > combining the selected features
    > creating DataFrame with combined features
    > computing cosine similarity: It is the measure of similarity between two non-zero vectors defines in an inner product space. Dot Product divided by product of their lengths. 

4. Performing the actual recommendation
   > Store the movie you want to get recommendations for in a variable
   > find the index of the variable in the dataset
   > find similarities between the movie and the rest in the dataset 
   > arrange the cosine sim in descending order
   > Iterate for how many recommendations you want and print the first n values from the descending list of the sortes movies.
