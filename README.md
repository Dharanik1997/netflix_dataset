# netflix_dataset

● Netflix is one of the most popular media and video streaming platforms. They
have over 8000 movies or tv shows available on their platform, as of mid-2021,
they have over 200M Subscribers globally.
● The particular business case focuses on the Netflix show data and provides
insightful information on 8807 shows
● Analyzing the data and generating insights helps Netflix decide which type of
shows/movies to produce and how to grow the business.

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Objectives

- Analyze the distribution of content types (movies vs TV shows).
- Identify the most common ratings for movies and TV shows.
- List and analyze content based on release years, countries, and durations.
- Explore and categorize content based on specific criteria and keywords.

  ## EDA Analysis
  
1. Find the counts of each categorical variable both using graphical and non-
graphical analysis.
a. For Non-graphical Analysis:
Hint : We want you to find the values counts of each category for the given
column
b. For graphical analysis:
Hint : We can use a count plot to get the counts of each category
______________________________________________________________________________
2. Comparison of tv shows vs. movies.
a. Find the number of movies produced in each country and pick the top 10
countries.
Hint : We want you to apply group by each country and find the count of unique
titles of movies
b. Find the number of Tv-Shows produced in each country and pick the top 10
countries.
Hint : We want you to apply group by each country and find the count of unique
titles of Tv-shows
______________________________________________________________________________
3. What is the best time to launch a TV show?
a. Find which is the best week to release the Tv-show or the movie. Do the analysis
separately for Tv-shows and Movies
Hint : We expect you to create a new column and group by each week and count
the total number of movies/ tv shows.
b. Find which is the best month to release the Tv-show or the movie. Do the
analysis separately for Tv-shows and Movies
Hint : We expect you to create a new column and group by each month and
count the total number of movies/ tv shows.
______________________________________________________________________________
4. Analysis of actors/directors of different types of shows/movies.
a. Identify the top 10 directors who have appeared in most movies or TV shows.
Hint : We want you to group by each actor and find the count of unique titles of
Tv-shows/movies
b. Identify the top 10 directors who have appeared in most movies or TV shows.
Hint : We want you to group by each director and find the count of unique titles
of Tv-shows/movies
______________________________________________________________________________
5. Which genre movies are more popular or produced more
Hint : We want you to apply the word cloud on the genre columns to know which kind
of genre is produced
______________________________________________________________________________
6. Find After how many days the movie will be added to Netflix after the release of
the movie (you can consider the recent past data)
Hint : We want you to get the difference between the columns having date added
information and release year information and get the mode of difference. This
will give an insight into what will be the better time to add in Netflix
______________________________________________________________________________

Insights:

The Box plot comparing 'TV Shows and Movies by rating' suggests that TV Shows tend to have a wider range of ratings, indicating a more diverse viewer base with mixed opinions. In contrast, Movies show higher consistency in ratings, possibly due to selective audience targeting. Extreme outliers in movies may indicate strong reactions (both positive and negative), while TV shows likely appeal to a more stable audience.
From the plot of Number of Movies and TV Shows Released Each Year, TV shows show a sharper increase in the number of additions, it indicates that Netflix has been focusing more on episodic content recently. This aligns with broader industry trends where streaming services see TV shows as a tool to boost user engagement and retention compared to one-time movie viewing.
Count plot for rating and type shows the precise counts for each category like movies are higher in type than Tv Shows and TV-MA is higher in rating, and this plot is useful for reports or descriptive statistics. Specific countries like the United States, India, and the United Kingdom lead in content production.
Heat map correlation shows the number of Movies & TV shows that loaded for each year.
The bar plot comparing the 'top 10 countries producing Movies vs. TV Shows' provides valuable insights of understanding that the which countries need to focus more on movies and TV shows.
Line plot of 'Weekly Release Trend for TV Shows and Movies' shows the peaks in certain weeks(e.g., around holidays, weekends, or special events, it indicate that audiences are more engaged at these times. Releasing content during these peaks could maximize audience reach and viewership.
Line plot of 'Monthly Release Trend for TV Shows and Movies' shows months with higher release volumes indicate seasonality(e.g., winter months, summer for family-friendly content, holidays for block bluster releases). Launching during these months could benefit from a larger audience and better competition positioning.
From the word cloud insights the popular genres are International movies, Dramas, Tv Shows, Documentaries, Comedies  indicating high viewer demand.
Movies are mostly added to Netflix one to two years i.e., 438 days after their release. Understanding this timeline helps strategize release schedules.

Recommendations:

Align new releases with periods of high viewer activity (e.g., December) for maximum engagement.
Invest in partnerships with top-performing directors and actors to produce exclusive content that attracts their fanbase.
Negotiate shorter delays for adding movies post-release to maintain freshness in content offerings.
 Expand content from emerging markets (e.g., South Korea, Spain) to cater to global audiences appreciating diverse cultural narratives.
Explore tiered subscription models offering discounts for users who primarily consume regional or older content, expanding affordability.
Analyze real-time viewing data during releases to adjust marketing efforts dynamically, ensuring optimal reach.
Introduce more short-duration content (e.g., web series or mini-documentaries) to attract younger audiences with shorter attention spans.

