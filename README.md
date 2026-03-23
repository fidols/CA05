# CA05 – kNN Movie Recommender System
#AI tools (Claude) were used to help guide the implementation and explanations for this project.
## Overview
This project implements a k-Nearest Neighbors (kNN) based recommendation engine to identify movies similar to a given query movie ("The Post").

## Methodology
- Each movie is represented as a numerical vector using:
  - IMDB rating
  - Genre indicators (Biography, Drama, Thriller, etc.)
- The kNN algorithm computes similarity using Euclidean distance.
- The model returns the 5 closest movies to the query.

## Tools Used
- Python
- Pandas
- Scikit-learn

## Key Results
The model successfully identifies movies with similar genre compositions and ratings.

## Limitations
- Does not include features like actors, directors, or themes
- Small dataset size
- No personalization

## Note on AI Usage
This project was completed with assistance from AI tools (ChatGPT) for guidance on structuring code, explanations, and documentation. All implementation and understanding were verified by the author.
