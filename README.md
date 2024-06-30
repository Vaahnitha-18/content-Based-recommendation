# Movie Recommendation Engines

This repository contains data and Jupyter notebooks for building content-based and collaborative-based recommendation engines using the TMDB 5000 Movies dataset.

## Files in this Repository

1. **Datasets:**
   - `tmdb_5000_movies.csv`: Contains metadata about 5000 movies from The Movie Database (TMDB).
   - `tmdb_5000_credits.csv`: Contains cast and crew information for the same set of movies.

2. **Jupyter Notebooks:**
   - `Content Based Recommendation Engines using Python.ipynb`: A notebook demonstrating how to build a content-based recommendation engine.
   - `Collaborative Based Recommendation Engines using Python.ipynb`: A notebook demonstrating how to build a collaborative-based recommendation engine.

## Project Structure


Movie-Recommendation-Engines/
│
├── data/
│   ├── tmdb_5000_movies.csv
│   ├── tmdb_5000_credits.csv
│
├── notebooks/
│   ├── Content Based Recommendation Engines using Python.ipynb
│   ├── Collaborative Based Recommendation Engines using Python.ipynb
│
├── README.md
│


## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- Jupyter Notebook or Jupyter Lab
- The following Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - ast

### Installation

1. Clone the repository to your local machine:
   
   git clone https://github.com/Vaahnitha-18/recommendation-system.git
  

2. Navigate to the project directory:
   
   cd recommendation-system
   
3. (Optional) Create and activate a virtual environment:
   
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   

4. Install the required packages:
   
   pip install pandas numpy scikit-learn
  

### Running the Notebooks

1. Start Jupyter Notebook or Jupyter Lab:
   
   jupyter notebook
   

2. Open and run the notebooks located in the `notebooks` directory.

## Project Overview

### Content-Based Recommendation Engine

The content-based recommendation engine analyzes the metadata of movies to recommend similar movies to the user. This approach leverages features such as genres, keywords, and movie descriptions.

### Collaborative-Based Recommendation Engine

The collaborative-based recommendation engine uses user data to recommend movies. This method relies on user ratings and behavior to find patterns and suggest movies that similar users have enjoyed.

## Acknowledgments

- The Movie Database (TMDB) for providing the datasets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
