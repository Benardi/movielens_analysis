[![Build Status](https://img.shields.io/badge/R%3E%3D-3.3.3-6666ff.svg)](https://cran.r-project.org/doc/FAQ/R-FAQ.html)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# MovieLens Analysis

Exploratory data analysis and application of statistical inference on the MovieLens-Dataset. Statistical inference has been applied through two distinct approachs: by means of hypothesis testing and by means of confidence intervals generated using bootstrap.

## Data

This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from [MovieLens](http://movielens.org), a movie recommendation service. It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016. Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

### Data attributes

The final dataset used in the notebooks of this repository has the following attributes:

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
- `xx_century`: Whether the movie is from the XX century, otherwise it's from the XXI century

## Dependencies

The notebooks inside this project have the following dependecies:

- here
- boot
- coin
- resample
- tidyverse

## Execution

The R notebooks reside in the *notebooks* directory, and ideally should be run under the Rstudio IDE.

## Authors

* **Benardi Nunes** - *Initial work* - [Benardi](https://github.com/Benardi)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details