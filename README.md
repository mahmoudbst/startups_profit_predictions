# startups_profit_predictions

## Resources:
- Data: https://www.kaggle.com/farhanmd29/50-startups
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, pickle

## Data cleaning and EDA:
Our data consist of 50 startups dataset containing 5 columns  like “R&D Spend”, “Administration”, “Marketing Spend”, “State”, “Profit”.

In this dataset we have 5 columns :
- Research  
- Administration  
- Marketing 
- State  
- Profit 


We have no missing values:

![](Capture%20d’écran%202021-10-11%20003538.png)



Relation between numerical features and profit:

![](Capture%20d’écran%202021-10-11%20004229.png)



Correlation between numerical features:

![](Capture%20d’écran%202021-10-11%20004251.png)



Handling categorical features:

![](Capture%20d’écran%202021-10-11%20004340.png)

## Model selection

Finding the best model using GridSearchCv:

![](Capture%20d’écran%202021-10-11%20004409.png)
