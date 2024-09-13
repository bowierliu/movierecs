# Movie Recommendation System

## Project Overview
This project builds a **Content-Based Movie Recommendation System** using movie metadata such as genres. The goal is to recommend movies similar to a user-specified movie by calculating the cosine similarity between the TF-IDF vectorized genres. The project uses the **MovieLens dataset** for movie metadata and ratings.

## Features
- **Content-Based Recommendations**: Recommends movies based on their similarity to a given movie’s genres.
- **TF-IDF Vectorization**: Transforms the movie genres into numerical vectors to calculate similarity.
- **Cosine Similarity**: Measures the similarity between the vectorized movie genres to find the closest matches.


## Dataset
This project uses the **MovieLens Dataset** which contains information about movies, their genres, and user ratings. The relevant files used are:
- `movies.csv`: Contains movie titles and genres.
- `ratings.csv`: Contains user ratings for movies.

### Dataset Fields:
- `movieId`: Unique identifier for each movie.
- `title`: The title of the movie (includes release year).
- `genres`: The genres of the movie, separated by `|`.
- `userId`: Unique identifier for each user.
- `rating`: User rating for a movie (on a scale of 0.5 to 5.0).


