# 🎬 Movie Recommendation System

This is a content-based movie recommendation system built using Python and machine learning.

## Features
- Recommends similar movies
- Uses CountVectorizer
- Uses cosine similarity

## How it works
1. Combine features (genres, cast, keywords, overview)
2. Convert text to vectors
3. Compute similarity
4. Recommend top movies

## Tech Stack
- Python
- Pandas
- Scikit-learn

## Usage
Run the notebook and call:
recommend("Batman")

## Limitations
- No user-based recommendations
- Works only on content similarity
  
## 🔍 Example
recommend("Batman")
Output:
- Man of Steel
- Batman Begins
- Thor

![Output](output.png)

