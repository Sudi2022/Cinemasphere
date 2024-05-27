# Cinemasphere; A movie recommendation Web App

This project aims to develop and implement a personalized movie recommendation system using the comprehensive MovieLens dataset to enhance the user experience by providing tailored movie suggestions based on individual preferences, leveraging advanced machine learning techniques and data analytics.

        The dataset includes movies.csv, which contains unique identifiers (movie ID), titles, and genres, and ratings.csv, which consists of user ratings, user and movie identifiers, numerical rating scores, and timestamps. Each entry in movies.csv represents a distinct movie, categorized into various genres such as action, adventure, comedy, and drama. The dataset comprises 25,000,095 ratings and 1,093,360 tag applications across 62,423 movies.
     
     The recommendation system primarily employs content-based filtering techniques. Content-based filtering analyzes movie titles to generate recommendations based on textual content similarities using TF-IDF vectorization and cosine similarity. By identifying movies with similar titles, the recommendation system provides users with movie recommendations that match their preferences.
     
     The recommendation system primarily employs content-based filtering techniques. Content-based filtering analyzes movie titles to generate recommendations based on textual content similarities using TF-IDF vectorization and cosine similarity. By identifying movies with similar titles, the recommendation system provides users with movie recommendations that match their preferences.    
     
               The web application interacts dynamically with users, incorporating PHP for server-side scripting and Python for executing the recommendation algorithms. The rec.php file handles user requests, communicates with the Python-based recommendation engine, and dynamically updates the web page with movie recommendations. This seamless integration between PHP and Python ensures efficient processing and delivery of personalized recommendations.  
     
     The final project output is a fully functional web application that presents users with the top ten recommended movies. The application features a user-friendly interface (rec.html) styled with CSS (rec.css), which takes the user's input, a movie title. Back-end algorithms for content-based filtering are implemented in Python, with back-end scripting managed by PHP (rec.php). 
     
	In conclusion, the project successfully demonstrates the effectiveness of the recommendation system in improving user engagement and satisfaction through personalized movie recommendations. By integrating advanced machine learning algorithms and data analysis techniques, the system addresses user preferences and optimizes the movie-watching experience.
