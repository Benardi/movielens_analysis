# movielens_analysis
####Analysis on MovieLens Datasets

## Data description
Data in the repository has the following attributes, some are derived inside the notebook:

- `Make`: Make of the car;

- `movieId`: The id of the movie       
- `title`:  The title of the movie
- `median_rating` : The median rating of the movie
- `well_rated` :  Whether the movie has more a median rating above 3.5 stars
- `genres`: The genres of the movie, list divide by '|'       
- `year`: The year of the movie  
- `num_genres`: Number of genres the movie has been classified in   
- `homogeneous`: Whethe the movie has only one genre 
- `userId`: The id of the user       
- `rating`: The rating give by the user   
- `timestamp`: The timestamp of the rating made by the user 

## Dependencies

The notebooks inside this project have the following dependecies:

- here
- tidyverse
- resample
- boot