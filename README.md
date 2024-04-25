# Movie Recommendation System
## Overview
This project implements a movie recommendation system using content-based filtering. The system recommends movies similar to a given movie based on textual metadata such as movie overview, genres, keywords, cast, and crew. It leverages natural language processing techniques to process and vectorize the text data and calculates similarity scores between movies using cosine similarity.

## Dataset
The dataset used in this project consists of two CSV files:

* tmdb_5000_movies.csv: Contains metadata for over 5000 movies, including movie ID, title, overview, genres, keywords, etc.
* tmdb_5000_credits.csv: Contains credits information for the movies, including cast and crew details.
## Dependencies
This project is implemented in Python and requires the following dependencies:

* numpy: For numerical computations
* pandas: For data manipulation
* scikit-learn: For text processing and cosine similarity calculation
* nltk: For text stemming
* You can install the dependencies using pip:

Copy code
```python
pip install numpy pandas scikit-learn nltk
```
## Usage
Clone the repository to your local machine:
bash
Copy code
```python
git clone https://github.com/your_username/movie-recommendation-system.git
```
Navigate to the project directory:
bash
Copy code
```python
cd movie-recommendation-system
```
Ensure that you have the movie dataset files (tmdb_5000_movies.csv and tmdb_5000_credits.csv) in the project directory.
Run the Python script recommendation_system.py to generate movie recommendations:
Copy code
```python
python recommendation_system.py
```
Follow the prompts to input a movie title and receive recommendations based on content similarity.
## References
* SciKit-Learn Documentation
* NLTK Documentation
* TMDb API
## Acknowledgments
The dataset used in this project is sourced from The Movie Database (TMDb).








