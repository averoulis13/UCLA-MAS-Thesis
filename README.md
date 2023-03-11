# UCLA-MAS-Thesis
Thesis on Creating a New Offensive Line Metric

This thesis is going to create a new metric that will emphasize an offensive lineman's physical dominance, measured through speed, agility, power, and other variables.

Here are the steps I have taken to far to accomplish this (steps completed are starred), and the steps I plan to take in the near future:

1. Acquire NFL player, play-by-play, game, and weekly tracking data from the NFL Big Data Bowl site (https://www.kaggle.com/competitions/nfl-big-data-bowl-2023/overview) and load the data into R.*

2. Merge play-by-play data and player data with tracking data so we can have a new large dataset, with each row representing a given player's movement for a particular play.*

3. Manipulate existing variables to create new ones for modeling purposes (ex. calculating a score differential variable and making in a factor), may want to create more variables

4. Acquire salary data for each player from Spotrac.com, and use it as a response variable to see how the metric I create correlates to a tangible OL metric. (have first 100 players, working on scraping the rest)

5. Create a model using old and new variables to come up with a metric for each player. Use appropriate weights for each of the variables, and aggregate these variables over all plays that a given player participates in.

6. Perform exploratory analysis on the aggregated variables by comparing them to the response, and determine through manual inspection/judgment as well as a modeling technique like stepwise regression which variables should go in the model. 

7. Determine if any transformations/adjustments should be made to variable aggregation based on the model's performance on training and test sets of the data, and change the model accordingly. 

8. Find an appropriate model that roughly approximates salary but also is not too predictive of the response.

9. Evaluate the dominance of offensive line units across teams by comparing the average dominance metric of teammmates. Then we can see which teams are the most dominant on the offensive line. 
