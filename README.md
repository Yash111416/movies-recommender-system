# Movie Recommender System using Jupyter Notebook

## Introduction

This Jupyter Notebook demonstrates a Movie Recommender System using the TMDB Movies 5000 dataset. The system is built using various Python libraries and tools, including Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, NLTK, and Streamlit. The goal of this project is to provide movie recommendations based on user preferences and movie similarity.

## Libraries and Tools Used

The following libraries and tools are used in this project:

- **Pandas (pd)**: Used for data manipulation and analysis.
- **NumPy (np)**: Used for numerical operations and data handling.
- **Matplotlib (plt)**: Used for data visualization and creating plots.
- **Seaborn (sns)**: Used for enhancing the visual aesthetics of plots.
- **Ast**: Used for handling abstract syntax trees for data processing.
- **CountVectorizer**: A feature extraction method for text data.
- **Cosine Similarity**: A metric to measure similarity between movies.
- **PorterStemmer**: Used for stemming words in text data.
- **NLTK**: Natural Language Toolkit for text processing.

## Dataset

The dataset used for this project is the TMDB Movies 5000 dataset, which contains information about thousands of movies, including their titles, genres, keywords, cast, crew, and user ratings. This dataset is used to build the movie recommendation system.

## Movie Recommender System

The movie recommender system is built using the following steps:

1. **Data Preprocessing**: Data from the TMDB dataset is loaded and preprocessed, including cleaning and feature engineering.

2. **Text Data Processing**: The system processes text data, such as movie titles and keywords, using the CountVectorizer and PorterStemmer to convert text into a format suitable for analysis.

3. **Cosine Similarity**: Cosine similarity is used to calculate the similarity between movies based on their features, such as genres and keywords.

4. **User Input**: Users can input a movie title, and the system will recommend similar movies based on the user's choice.

## Running the Application

To interact with the Movie Recommender System, you can run the associated Streamlit application. To do this:

1. Install Streamlit if you haven't already: `pip install streamlit`.

2. Run the Streamlit app using the following command in your terminal within the project directory:
   ```
   streamlit run movie_recommender_app.py
   ```

3. Follow the instructions in the Streamlit app to input a movie title and receive movie recommendations.

## Conclusion

This Jupyter Notebook and the associated Streamlit app demonstrate a movie recommender system using the TMDB Movies 5000 dataset. The system utilizes various Python libraries and tools for data processing and visualization, providing movie recommendations based on user input. Enjoy exploring and discovering new movies!
