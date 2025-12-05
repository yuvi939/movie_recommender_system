The Movie Recommendation System is a Python-based application that suggests movies to users based on their preferences. It uses advanced algorithms to analyze movie similarities, genres, and ratings, providing personalized recommendations to enhance your movie-watching experience.

This system can be integrated with a user interface using Streamlit or other web frameworks for an interactive experience.

Features

Personalized Recommendations: Suggests movies similar to the one selected by the user.

Poster Fetching: Displays movie posters alongside recommended titles.

Easy Integration: Can be integrated into web apps using Streamlit.

Scalable Dataset: Supports large datasets with multiple movie attributes.

User-friendly Interface: Simple and intuitive for users of all ages.

Technologies Used

Python – Programming language for backend logic.

Pandas – Data manipulation and analysis.

NumPy – Efficient numerical computations.

Scikit-learn – For building recommendation models (e.g., cosine similarity).

Requests – Fetch movie posters from external APIs (like TMDb).

Streamlit – Web framework for creating interactive applications.

How It Works

The system loads a dataset of movies containing titles, genres, and other metadata.

Features are processed to compute similarity scores between movies using algorithms like cosine similarity.

When a user selects a movie, the system finds the top similar movies.

The corresponding movie posters are fetched using APIs (e.g., TMDb).

Recommendations are displayed with titles and posters in an interactive format.
Installation

Clone the repository:

git clone https://github.com/yuvi939/movie_recommender_system.git


Navigate to the project directory:

cd movie-recommendation-system


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py

Dataset

The system uses a dataset containing:

Movie titles

Genres

Ratings

Poster URLs (fetched dynamically from TMDb API)

You can use your own dataset or the provided sample CSV file.

Usage

Launch the app using Streamlit.

Select a movie from the dropdown menu.

The system displays 5–10 recommended movies with their posters.

Click on a recommended movie to explore more recommendations.

Future Enhancements

Implement user-based collaborative filtering for personalized recommendations.

Add support for watchlists and user ratings.

Enhance UI with advanced filtering by genre, year, or rating.

Deploy as a full-fledged web app for global access.

License

This project is licensed under the MIT License.
