# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Database Setup and Injection

-Imported the data into mongoDB and created a new client of mongoDB in the notebook. 

-Added the resturant 'Penang Flavours'

-Removed Dover results

## Data Analysis

Answered the following questions and created dataframes from each of the queried data from the nosql database.

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

Example of the last dataframe:
```python
 	_id 	count
0 	Thanet 	1130
1 	Greenwich 	882
2 	Maidstone 	713
3 	Newham 	711
4 	Swale 	686
```

