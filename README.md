# Netflix
Data downloaded from Kaggle:

   "About this Dataset: Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc. "

link to data: https://www.kaggle.com/datasets/shivamb/netflix-shows

    Data clean-up

Movies that were mislabeled as TV Shows, and TV Shows that were mislabeled as Movies. Changed dates to be consistent in short date form. Removed 'season' and 'min' from Duration column, and changed column format to numeric. Seperated Movies and TV Shows into different Excel Sheets

    Pivot tables

Created Pivot tables using the the from netflix_movies sheet and netflix_tvshows sheets. TV Show pivot tables display information on tv show rating breakdown, number of seasons per TV shows, and year seasons were realeased. Movie pivot tables display breakdown of movies and their ratings, duration of movies, and year movies were released.

    VLookup

Vlookup for movies will return the movie rating and year released when a movie title is searched. Vlookup for tv shows will return the number of seasons for the show when a tv show title is searched.
