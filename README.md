# Player Valuation

Welcome to my take on NBA player valuation! Here I use FiveThirtyEight's raptor WAR advanced statistic to estimate how much a player is worth in dollars. I have posted a full write up and analysis of my findings [here](https://jquam15.github.io/Player_Valuation.html), so I would highly encourage you to check it out! Feel free to check out the rest of my work on my [website](https://jquam15.github.io) as well!

Advanced player data was acquired from the [538](https://github.com/fivethirtyeight/data/tree/master/nba-raptor) github repo and player/team salary data was scraped from the [Hoops Hype](https://hoopshype.com/salaries/2021-2022/) website.

The file **raptor.ipynb** contains the code I used scrape and clean the data, merge the data, and perform the analysis.

I saved the scraped data into csv files in the **data** folder. All of the below files contain data from the 2013-14 through 2021-22 seasons (beginning of the player tracking era). The data folder contains the following files:

* **player_raptor.csv** contains advanced player performance statistics from 538 for each season
* **player_salaries.csv** contains player salaries for each season
* **player_value.csv** final combined dataset that contains advanced player stats, player salary, and estimated player value
* **team_salaries.csv** contains total team salaries for each season 

The files **table.html** and **table.css** contain the code to visualize the table in a webpage
