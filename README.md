# NBA-Predict <img align="right" width="75" height="155" src="https://cdn.freebiesupply.com/images/large/2x/nba-logo-transparent.png">


Predicts NBA Games Using a Regression Model 

# Model
"The model uses seventeen factors scraped from sportsreference.com to determine the amount of games a team would win in any given season within the past five years. 

* Assists
* Def Rebounds
* FG%
* FG
* Opp Assists
* Opp Blocks
* Opp Def Rebounds
* OPP FG %
* OPP points
* OPP 3 Pt %
* OPP total rebounds
* OPP 2 Pt FG%
* Points
* Rank
* 3 pt FG%
* Total Rebounds
* 2 Pt FG % 

# **Cleaning Process**

We pulled the total team statistic from the past three seasons and pulled the total Wins of the last three seasons and merged the data. We imported Pearson R and iterrated through the merged dataframe to check which if the teams statistics had the greatest affect of the overall team Wins. We selected the seventeen teams statistics that had an affect on wins greater than .4 and less than -.4 value. 

* ![Clean1]()


# **Predictions Models**
We chose to use Linear Regession model as the data collected was quantitative and the linear regression was able to provide the best overall predictive analysis, showing R-squared to be ~.9

