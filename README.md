# NBA Prediction Models <img align="right" width="75" height="155" src="https://cdn.freebiesupply.com/images/large/2x/nba-logo-transparent.png">


Predicts NBA Games Using Regression Models 

# Model
The model uses seventeen factors scraped from sportsreference.com to determine the amount of games a team would win in any given season within the past five years. 

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
* Assists

# **Cleaning Process**

We pulled the total team statistic from the past three seasons and pulled the total Wins of the last three seasons and merged the data. We imported Pearson R and iterrated through the merged dataframe to check which if the teams statistics had the greatest affect of the overall team Wins. We selected the seventeen teams statistics that had an affect on wins greater than .4 and less than -.4 value. 

### Import api
![Clean1](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/import_sports.PNG)
### Merge Data
![Clean2](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/Merge_Data.PNG) 
### Assign Values
![Clean3](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/assignvlaues.PNG) 
### Prediction Models
![Clean4]( https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/Lineregmodel.PNG) 

![Clean5](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/model_predictions.PNG) 


# **Predictions Models**
We chose to use Linear Regession model as the data collected was quantitative and the linear regression was able to provide the best overall predictive analysis, showing R-squared to be ~.9

### Linear Regression
 ![Pred_Model1](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/Linear_Reg.PNG)

### Lasso Model
 ![Pred_Model2](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/lasso_chart.PNG)  

### Ridge Model
 ![Pred_Model3](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/Ridge_Model.PNG)  

### ElasticNet Model
 ![Pred_Model4](https://github.com/D-3nvironmentalist/Project-3/blob/master/Images/ElasticModel.PNG) 
