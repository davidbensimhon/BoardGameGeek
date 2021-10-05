# BoardGameGeek

This project is part of my MSc in Data Science. The goal is to build a recommender system that can recommend to users on the BoardGameGeek website their next game for purchase. All coding is done in R.

I have inlcuded code that outlines:

1. The scraping of UK usernames using traditional HTML techniques.
2. The scraping of the top 500 games list using traditional HTML techniques.
3. The creation of functions that will be used to pull selected data from the BGG XML2 API.
4. The scraping of users game collections with ratings.
5. The scraping of the games metadata including features such as 'min_players', 'avg_playing_time', 'mechanic', 'category' etc.
6. The creation of Collaborative based filtering models using the 'recommenderlab' package alongside their evaluation.
7. The creation of Content based filtering system using a rule based approach.
