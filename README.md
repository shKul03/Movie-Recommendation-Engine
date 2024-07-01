# Movie Recommendation System

## Overview
This project implements a movie recommendation system using the MovieLens 25M dataset. The system allows users to search for movies by title and provides recommendations based on the preferences of users who liked similar movies.

## Installation
1. Download the MovieLens 25M dataset from [here](https://files.grouplens.org/datasets/movielens/ml-25m.zip) and extract the `movies.csv` and `ratings.csv` files.
2. Install the necessary Python libraries:
    ```sh
    pip install pandas scikit-learn numpy ipywidgets
    ```

## Usage

### Input
- **Movie Titles**: The dataset consists of movie titles that are cleaned by removing special characters to standardize them for the search function.
- **User Ratings**: User ratings are used to identify similar users who liked the same movie, which helps in generating movie recommendations.

### Interactive UI
The system features an interactive widget that allows users to type in a movie title and receive recommendations in real-time. As the user types, the system searches for movies with similar titles and displays the top recommendations based on the preferences of users who liked the same movie.

### Output
- **Search Results**: When a movie title is entered, the system returns the top 5 movies with similar titles.
- **Recommendations**: Based on the selected movie, the system provides the top 10 movie recommendations. These recommendations are based on the ratings of users who liked similar movies. The output includes the recommendation score, movie titles, and genres.

## Author
Implemented by Shloka Kulkarni.
