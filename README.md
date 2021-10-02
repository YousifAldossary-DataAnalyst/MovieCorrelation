# Amazon Food Reviews

## Summary:
As Always first things first is to clean the data. The correlation between movie type, budget and more with revenue.
The prediction that was made is as "to expect that as the budget increases, then the gross also increases". So we also expect big company like Fox, Disney to have high correlation too.
However, the overall objective is to find the best correlation with revenue.

## Context:
a dataset focused on movie revenue and analyze it over the last decades. 

## Data include:
  - budget: the budget of a movie. Some movies don't have this, so it appears as 0
  - company: the production company
  - country: country of origin
  - director: the director
  - genre: main genre of the movie.
  - gross: revenue of the movie
  - name: name of the movie
  - rating: rating of the movie (R, PG, etc.)
  - released: release date (YYYY-MM-DD)
  - runtime: duration of the movie
  - score: IMDb user rating
  - votes: number of user votes
  - star: main actor/actress
  - writer: writer of the movie
  - year: year of release

## Objective: 
To determine the highest correlation with gross revenue in the movie dataset using python. 

## Application used:
#### Python (jupyter):
  - Matplot
  - Pandas
  - Seaborn
  - Matplotlib.pyplot
  
#### Movies.csv Dataset
  https://www.kaggle.com/danielgrijalvas/movies
  
## Object based considerations
   - Methods:
     1. Finding missing data or incorrect ones and correct them. 
     2. Remove Duplicates.
     3. Finding Correlations.
