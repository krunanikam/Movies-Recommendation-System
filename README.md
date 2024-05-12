# Movies-Recommendation-System

This project focuses on building a movie recommendation system using the TMDB 5000 Movies Dataset, which includes essential movie information such as titles, genres, keywords, overviews, cast, and crew details. The system trains on these key features to recommend five similar movies based on a user's input movie.

To achieve this, the project first loads and cleans the dataset, ensuring that only relevant columns are retained. It then combines the movies and credits datasets based on the movie ID to create a comprehensive dataset for training the recommendation model.

The core features used for training the model include the movie's title, ID, genres, keywords, overview, cast, and crew. These features are crucial for identifying similarities between movies and making accurate recommendations.

Users can interact with the recommendation system through a user-friendly interface created using the Streamlit library in Python. The Streamlit interface allows users to input a movie title or ID and receive recommendations for similar movies. The interface enhances the user experience by providing a simple and intuitive way to access the recommendation system's functionality.



