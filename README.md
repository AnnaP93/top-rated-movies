# Movie-Recommender

### **Dataset Details**
The data resources were taken from Kaggle - https://www.kaggle.com/ibtesama/getting-started-with-a-movie-recommendation-system/data

The 'tmdb_5000_credits' dataset contains the following features:

- movie_id - A unique identifier for each movie.
- cast - The name of lead and supporting actors.
- crew - The name of Director, Editor, Composer, Writer etc.

The 'tmdb_5000_movies' dataset has the following features:

- budget - The budget in which the movie was made.
- genre - The genre of the movie, Action, Comedy ,Thriller etc.
- homepage - A link to the homepage of the movie.
- id - This is infact the movie_id as in the first dataset.
- keywords - The keywords or tags related to the movie.
- original_language - The language in which the movie was made.
- original_title - The title of the movie before translation or adaptation.
- overview - A brief description of the movie.
- popularity - A numeric quantity specifying the movie popularity.
- production_companies - The production house of the movie.
- production_countries - The country in which it was produced.
- release_date - The date on which it was released.
- revenue - The worldwide revenue generated by the movie.
- runtime - The running time of the movie in minutes.
- status - "Released" or "Rumored".
- tagline - Movie's tagline.
- title - Title of the movie.
- vote_average - average ratings the movie recieved.
- vote_count - the count of votes recieved.


### **Goal**
The goal of this project is to leverage demographic filtering to the dataset and identify top-10 movies to recommend users with similar demographic features.

In order to identify top-10 movies, IMDB's weighted rating was applied to the dataset. 

The program provides a list of top-10 movies and information about their respective actors, crew memebers, production companies and popularity of each movie.

