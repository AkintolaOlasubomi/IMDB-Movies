# Investigate a Dataset - IMDB-Movies
This contains my code implementation and insights for the IMDB movies dataset. It is my first project for the ALX - T sponsored Udacity Data Analyst Nanodegree program.

## Introduction

This dataset contains details of Movies that were released between 1960 to 2015. There are 10,866 records and 21 attributes namely;
- id                   
- imdb_id              
- popularity           
- budget               
- revenue              
- original_title       
- cast                 
- homepage             
- director             
- tagline              
- keywords             
- overview             
- runtime              
- genres               
- production_companies 
- release_date         
- vote_count           
- vote_average         
- release_year         
- budget_adj           
- revenue_adj

## Questions Asked
In the code implementation, I will be looking at some questions and see if I would be able to get an answer from the dataset.
Some of the questions asked include:
- What are the most common genres?
- Who are the most casted actors?
- what are the relationships between attributes?

## Insights Gotten
> The most common genres were Drama, Comedy, Thriller, Action, and Adventure.

> The most casted actors included Robert De Niro, Bruce Willis, Samuel L Jackson, Nicolas Cage and Matt Damon.

> There appears to be a slightly positive correlation between the budget and the revenue. This means that to some extent, when the budget increases, the revenue increases. For a movie with a very high revenue, then a lot of moey must have gone into the production.

> There is no correlation between the budget and the runtime. A very high budget does not guarantee a long movie and vice versa. The runtime is totally independent of the budget.

> Also, there is no correlation between the runtime and the popularity. A longer movie does not mean it will gain popularity. They are totally independent of each other.

> The correlation between the vote_count and popularity is slightly positive. There is a chance of getting popular if the vote count is high.


> The quantitative data are all skewed and do not follow the normal distribution.

> Also, that a year has the highest the higest number of movies produced does not equal to it being the year with the highest budget. We can see that clearly from bar charts above.
