# Spotify-data-analysis-and-genre-prediction
Spotify is one of the largest music streaming services all over the world. With 271 million monthly active users, including 124 million paying subscribers, it is the ideal platform for artists to reach their audience. 
At the heart of Spotify lives a massive and growing data-set. What if we could analyze the music we listen to using Data Science?

In this analysis, I would mine the nuggets of insight hidden beneath mountains of Spotify data. In doing so, gain a greater understanding of the type of genres, 
tracks and artists the consumers have been listening to on Spotify.

Broadly, we will be performing the following steps to accomplish the project objectives:

1. Perform Exploratory Data Analysis:
2. Visulization of audio feaftures of different genres
3. Correlation between features
4. Popular artists within each genre
5. Generate Insights:
6. Trends of popular features in the past decade
7. Variability of characteristics across genres
8. Apply k-means clustering algorithm
9. Apply Hierarchical clustering algorithm
10. Use elbow curve which helps to find the optimum number of clusters

This analysis can help understand consumer behavior and suggest what music are they looking for and hence provide direction to artists and music producers.

Methodology

1. I started by looking at correlations amongst various features followed by the distributions for each of these features.
2. I then examined the top artists within each genre using tree map.
3. This was followed by looking at variability of characteristics amongst the 6 genres using radar charts.
4. I then analysed how various major features evolved in the past decade.
5. Lastly, I performed k-means and hierarchical clustering to understand commonalities between various genres and found the optimal number of clusters using elbow method.

Insights

1. Energy is highly positively correlated with loudness while it is highly negatively correlated with acousticness.
2. A lot of songs high a popularity score of 0, which means a lot of songs haven’t been explored yet.
3. For Genres EDM, rock, pop, rap, latin and r&b, the top artists are Martin Garrix, Queen, The Chainsmoker, Logic, Don Omar  
   and Bobby Brown respectively.
4. Latin music is most loudest as well as most danceable among all genres. R&b and rap tracks tend to have relatively less 
   energy as compared to other genres, while EDM has the highest acousticness.
5. Interestingly, songs are getting shorter by the year, while also becoming danceable over time.
6. Even though we have six genres in the data, as per clustering technique we got only 3 optimal clusters which means a lot of 
   the genres are very similar.
   
Implications

1. This analysis was conducted to explore the evolution of music over time and also diving deeper to understand trends in what makes a song more danceable than others can help DJs, artists, and producers create music based on characteristics like tempo or level of speechiness.

2. Netflix has a commendable job by leveraging data to produce video content, and the next music revolution could be brought in by similar techniques.

Limitations

1. Even though there are millions of songs that exist, we only had about 32k records for our analysis, and hence we couldn’t obtain a full picture of the features of music.

2. Also the analysis could be strengthened by incorporating user related features like their demographical attributes, user history etc.
