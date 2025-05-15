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

