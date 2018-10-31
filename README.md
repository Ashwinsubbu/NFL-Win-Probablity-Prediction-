# NFL-Win-Probablity-Prediction-

Data Source - https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016 

Used the NFL Play by PLay Data 2009-2017 csv file for this project. 


### Motivation of the Project 
Sporting events like the NFL garner a lot of viewership and attention. Fans are always interested in statistics about games (winning odds of teams), player stats (pass averages, tackles, touch downs). This interest has led to a huge amount of data in terms of quantity (games across years) and features(passes, tackles) to be collected. Availability of this well-defined data presents us with opportunities to build robust machine learning models that can be used to classify/predict parameters accurately. This project of ours is a simple step in that direction. 


### Objective of the Project 
To parse the huge dataset, apply dimensionality reduction techniques, build regression models to predict the Win Probability of plays and to evaluate the performance of each model using standard metrics. 

### About the Dataset 
The dataset was chosen from Kaggle, it consists of play by play data collected on all NFL(National Football League)games conducted between 2009 and 2017.The features contain game details like number of touch downs, tackles, pass attempts etc. Some key information about the dataset are presented below:

• Dimension: 407688rows * 102 columns
• Datatype Split: 31(int64), 33(float64), 38(object)
• Null Data: 27% 

### Challenge to overcome 
Since the major objective of the project is not to develop an effective stratergy to replace the null values. I have deleted columns with with more than 30% of Null Data and all other records with any null values taking leverage of the big data. 

### Conclusion with Project Results 
Achieved a R2 Score of 0.901 using XGBoost model and a R2score of 0.867 using Rigde Regularization model. Applying PCA achieved a R2 score of 0.856. 
