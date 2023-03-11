# UCLA-MAS-Thesis
Thesis on Creating a New Offensive Line Metric

This thesis is going to create a new metric that will emphasize an offensive lineman's physical dominance, measured through speed, agility, power, and other variables.

Here are the steps I have taken to far to accomplish this, and the steps I plan to take in the near future:

1. Acquire NFL player, play-by-play, game, and weekly tracking data from the NFL Big Data Bowl site (https://www.kaggle.com/competitions/nfl-big-data-bowl-2023/overview) and load the data into R.

2. Merge play-by-play data and player data with tracking data so we can have a new large dataset, with each row representing a given player's movement for a particular play.

3. Manipulate existing variables to create new ones for modeling purposes (ex. calculating a score differential variable and making in a factor)

4. Acquire salary data for each player from Spotrac.com, and use it as a response variable to see how the metric I create correlates to a tangible OL metric.

5. Create a model using old and new variables to come up with a metric for each player, aggregated across all of the player's plays. Use appr
