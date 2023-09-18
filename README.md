# movies_recommendation_system

## Description:
The "Movies Recommendation System" project is designed to provide movie recommendations to users based on their preferences and movie ratings. This system utilizes a dataset consisting of movie ratings given by users and movie information, such as titles and genres.

## Key Steps and Insights:
**1. Data Preparation:** The project begins with loading and preprocessing two main datasets: movie ratings and movie information. This involves cleaning and structuring the data for further analysis.

**2. Genre Encoding:** The project encodes movie genres into binary columns using the one-hot encoding technique, making it easier to incorporate genre information into the recommendation system.

**3. Year Extraction:** The release year of each movie is extracted from the movie titles, and the titles are cleaned to remove the year information.

**4. Building a Movie-User Rating Matrix:** The project constructs a movie-user rating matrix, where movies are on one axis, users on the other, and each cell represents a user's rating for a specific movie. Missing values are filled with zeros.

**5. Exploratory Data Analysis:** The project includes data visualization to understand the distribution of user votes for movies and the number of votes by users.

**6. Nearest Neighbors Algorithm:** A recommendation model is built using the k-nearest neighbors (KNN) algorithm with a cosine similarity metric. This model identifies similar movies based on user ratings.

**7. Recommendation Function:** The project provides a recommendation function that takes a movie name as input and returns a list of recommended movies based on user preferences and similarity.

**8. User Interaction:** The project demonstrates how users can interact with the system by receiving movie recommendations for a randomly selected movie.

## Results:
The "Movies Recommendation System" successfully generates movie recommendations based on user preferences and movie similarity, enhancing the movie-watching experience by suggesting movies that users are likely to enjoy.
