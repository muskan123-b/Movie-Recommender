# Recommendation System
Recommendation System is a system that seeks to predict or filter preferences according to the user’s choices. Recommendation systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general. Netflix, Amazon, and other companies use recommendation systems to help their users find the right product or movie for them.

<img src="https://user-images.githubusercontent.com/73715927/152067346-488ca9f4-58dc-4e10-8625-f7d90dc18bed.png" width=70% height=40%>

There are mainly 2 types of recommendation systems:
1. **Content-based Filtering:** These suggest recommendations based on the item metadata (movie, product, song, etc). Here, the main idea is if a user likes an item, then the user will also like items similar to it.
2. **Collaboration-based Filtering:** These systems make recommendations by grouping the users with similar interests. For this system, metadata of the item is not required.

**In this project, we are building a Content-based recommendation engine for movies.**

### Source of Dataset
https://www.kaggle.com/tmdb/tmdb-movie-metadata

### About Dataset
--The first dataset, **'tmdb_5000_credits.csv'** contains the following features:

movie_id - A unique identifier for each movie.

title - The title of the movie.

cast - The name of lead and supporting actors.

crew - The name of Director, Editor, Composer, Writer etc.

--The second dataset, **'tmdb_5000_movies.csv'** has the following features:

budget - The budget in which the movie was made.

genre - The genre of the movie, Action, Comedy ,Thriller etc.

homepage - A link to the homepage of the movie.

id - This is infact the movie_id as in the first dataset.

keywords - The keywords or tags related to the movie.

original_language - The language in which the movie was made.

original_title - The title of the movie before translation or adaptation.

overview - A brief description of the movie.

popularity - A numeric quantity specifying the movie popularity.

production_companies - The production house of the movie.

production_countries - The country in which it was produced.

release_date - The date on which it was released.

revenue - The worldwide revenue generated by the movie.

runtime - The running time of the movie in minutes.

status - "Released" or "Rumored".

tagline - Movie's tagline.

title - Title of the movie.

vote_average - average ratings the movie recieved.

vote_count - the count of votes recieved.

