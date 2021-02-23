# Data-Analysis-and-Plotting-Project-3

Overview
If you are planning on going out to see a movie, how well can you trust online reviews and ratings? Especially if the same company showing the rating also makes money by selling movie tickets. Do they have a bias towards rating movies higher than they should be rated?

Goal:
Your goal is to complete the tasks below based off the 538 article and see if you reach a similar conclusion. You will need to use your pandas and visualization skills to determine if Fandango's ratings in 2015 had a bias towards rating movies better to sell more tickets.

Understanding the Background and Data
Read the article in the code notebook

After reading the article, read these two tables giving an overview of the two .csv files we will be working with:

The Data
This is the data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s openly available on 538's github: https://github.com/fivethirtyeight/data. There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

all_sites_scores.csv
all_sites_scores.csv contains every film that has a Rotten Tomatoes rating, a RT User rating, a Metacritic score, a Metacritic User score, and IMDb score, and at least 30 fan reviews on Fandango. The data from Fandango was pulled on Aug. 24, 2015.

Column	Definition
FILM	- The film in question
RottenTomatoes	- The Rotten Tomatoes Tomatometer score for the film
RottenTomatoes_User	- The Rotten Tomatoes user score for the film
Metacritic	- The Metacritic critic score for the film
Metacritic_User	- The Metacritic user score for the film
IMDB	- The IMDb user score for the film
Metacritic_user_vote_count	- The number of user votes the film had on Metacritic
IMDB_user_vote_count	- The number of user votes the film had on IMDb

fandango_scape.csv
fandango_scrape.csv contains every film 538 pulled from Fandango.

Column	Definiton
FILM	- The movie
STARS	- Number of stars presented on Fandango.com
RATING	- The Fandango ratingValue for the film, as pulled from the HTML of each page. This is the actual average score the movie obtained.
VOTES	- number of people who had reviewed the film at the time we pulled it.

Both the datasets and the code notebook is provided make sure to check it
