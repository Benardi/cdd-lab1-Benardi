[![Build Status](https://img.shields.io/badge/R%3E%3D-3.3.3-6666ff.svg)](https://cran.r-project.org/doc/FAQ/R-FAQ.html)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# E.D.A on IMDB series data

Exploratory data analysis on data from IMDB about TV series and Streaming. Original data and variables come from  the repository [imdb-series](https://github.com/nazareno/imdb-series) and emcompasses  around 30 TV series.

## Data

### IMDB Ratings for TV/Streaming Series

A dataset to analyse user ratings given in IMDB to episodes of some popular series. Code is in R. And the code to generate your version of it.

Each line in the dtaset is an episode from a series from a handcrafted list of series. The variables are as follows:

    * series_name <chr> Self explanatory
    * series_ep   <int> Episode index in the series from 1 onwards.
    * season      <int> From 1 onwards
    * season_ep   <int> Episode index in the season
    * url         <chr> IMDB url for the episode (eg "http://www.imdb.com/title/tt5174246/")
    * Episode     <chr> Episode title
    * UserRating  <dbl> IMDB User Rating calculated [as explained in their site](http://www.imdb.com/help/show_leaf?votestopfaq).
    * UserVotes   <dbl> Num of votes for the rating
    * r1          <dbl> Proportion of users who rated this episode with score 1
    * r2          <dbl> Proportion of users who rated this episode with score 2
    * ...
    * r10         <dbl> Proportion of users who rated this episode with score 10

## Prerequisites

* `R >= 3.3.3`
* here
* plotly
* tidyverse

## Execution

The R notebooks reside in the *notebooks* directory, and ideally should be run under the Rstudio IDE.

## Authors

* **Benardi Nunes** - *Exploratory Data Analysis* - [Benardi](https://github.com/Benardi)
* **Nazareno** - *Data Acquisition* - [Nazareno](https://github.com/nazareno)




## License

This project is licensed under the GPL v3.0 License - see the [LICENSE.md](LICENSE.md) file for details
