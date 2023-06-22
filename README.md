# Movie Correlation Python

This project is a Python script that analyzes a dataset of movies and calculates the correlation between various movie features such as the year, rating, score, budget, and gross. The script utilizes the Pandas library to read and manipulate the data and the Seaborn library to create visualizations of the correlation matrix.

## Dataset Description

The dataset contains information on several movies, including their name, rating, genre, year, score, votes, director, writer, star, country, budget, gross, company, and runtime. Here's a brief description of each column:

- name: The name of the movie.
- rating: The rating of the movie (G, PG, PG-13, R, etc.).
- genre: The genre of the movie (Comedy, Drama, Action, etc.).
- year: The year the movie was released.
- released: The release date of the movie.
- score: The IMDB rating of the movie.
- votes: The number of votes on the IMDB rating.
- director: The name of the director.
- writer: The name of the writer.
- star: The name of the star.
- country: The country where the movie was produced.
- budget: The budget of the movie.
- gross: The gross earnings of the movie.
- company: The production company of the movie.
- runtime: The runtime of the movie in minutes.

## Project Overview

The script performs the following steps:

1. Data Loading: The dataset is loaded into a Pandas DataFrame for further analysis.

2. Data Cleaning: Data cleaning techniques are applied to handle missing values, remove duplicates, and ensure data consistency.

3. Correlation Calculation: The correlation between movie features is calculated using the Pandas `corr()` function.

4. Correlation Visualization: The correlation matrix is visualized using the Seaborn library to create a heatmap, which provides a visual representation of the correlations between different movie features.

## Project Repository

The project is available on GitHub under the project name [Movie Correlation Python](https://github.com/Pranay62/Movie_Correlation_Python/). You can access the repository for the project's source code, dataset, and additional documentation.
