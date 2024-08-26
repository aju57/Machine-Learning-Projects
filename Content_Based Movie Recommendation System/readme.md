# Movie Recommendation System

## Project Overview

This project involves the creation of a movie recommendation system that suggests similar movies based on a user's input. The system uses the cosine similarity algorithm to compare movie titles, cast, crew, and descriptions to find movies that are most similar to the one specified by the user.

## How It Works

1. **Data Collection**: The dataset contains information about various movies, including their titles, cast, crew, and descriptions.
2. **Data Preprocessing**: Text data is cleaned and processed to create a matrix of movie features.
3. **Cosine Similarity**: The cosine similarity algorithm is applied to calculate the similarity between movies based on their features.
4. **Recommendation**: Given an input movie title, the system retrieves and recommends movies that have the highest similarity scores.

## Key Features

- **Content-Based Filtering**: Recommends movies based on the content such as cast, crew, and movie descriptions.
- **Cosine Similarity**: Measures the similarity between movies by considering the angle between the feature vectors of movies in a multi-dimensional space.
- **User Input**: Allows users to input the name of a movie and receive a list of similar movies as recommendations.
