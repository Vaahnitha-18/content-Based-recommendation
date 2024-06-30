# Content Based Recommendation Engines using Python

This project demonstrates the implementation of content-based recommendation engines using Python. The project leverages movie data from TMDB (The Movie Database) to build a recommendation system that suggests movies based on their content.

## Project Structure

- `Content Based Recommendation Engines using Python.ipynb`: This Jupyter Notebook contains the implementation of the recommendation engines.
- `tmdb_5000_movies.csv`: This dataset contains information about 5000 movies, including their title, genres, overview, and other metadata.
- `tmdb_5000_credits.csv`: This dataset contains information about the cast and crew for the 5000 movies.

## Getting Started

### Prerequisites

To run this project, you need to have Python installed on your machine along with the following libraries:

- pandas
- numpy
- scikit-learn
- nltk

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn nltk
```

### Running the Project

1. **Clone the repository**:

   
   git clone https://github.com/Vaahnitha-18/content-Based-recommendation.git
   

2. **Navigate to the project directory**:

   
   cd content-based-recommendation-engine
  

3. **Open the Jupyter Notebook**:

   
   jupyter notebook "Content Based Recommendation Engines using Python.ipynb"
   

4. **Run the Notebook**: Follow the instructions in the notebook to run the cells and execute the code.

## Project Overview

The project consists of the following key sections:

1. **Data Loading and Preprocessing**: This section involves loading the datasets (`tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`) and performing initial data cleaning and preprocessing.

2. **Feature Extraction**: In this section, features such as the movie overview, genres, and cast are extracted and transformed into numerical representations using techniques like TF-IDF and Count Vectorizer.

3. **Similarity Calculation**: This section calculates the similarity between movies using cosine similarity based on the extracted features.

4. **Recommendation Function**: A function is implemented to provide movie recommendations based on the similarity scores.

5. **Evaluation**: The performance of the recommendation engine is evaluated and visualized.

## Results

The recommendation engine successfully suggests movies that are similar in content to the input movie. The similarity is determined based on the movie overview, genres, and cast information.

## Future Work

- Incorporate additional features such as directors, keywords, and production companies to improve recommendation accuracy.
- Experiment with different similarity measures and machine learning algorithms.
- Build a web application to provide an interactive interface for the recommendation engine.

