# Project Title: Calories Burnt on Workout  
## Description 
Supervised Learning    
Regression Problem    
To predict the data of calories burned in the exercises from the knowledge of duration (t), heart rate (h), body temperature (T), age (A), weight (W), height (H) and gender (G). It was verified that the variable that most influences the burning of calories is duration, followed by heart rate and body temperature.   

## Getting Started
**Tools used:** Jupyter Notebook  
**Languages:** python  
**Libraries:** Numpy,Pandas,Matplotlib,Seaborn  
**Dataset downloaded from kaggle-** https://www.kaggle.com/fmendes/fmendesdat263xdemos?select=exercise.csv  
**files:** Calories.csv,Exercise.csv  

## Table Of Contents  
Importing Libraries  
Loading Datasets  
Merging Dataframes    
Performing EDA  
Feature Selection  
Model Evaluation  

**Conclusion:** Accuracy scores for different models are  
 XGBOOST Model:99%  
 Linear Regression Model: 96%  
 Decision Tree Model: 99%  
 Random Forest Model: 96%    
From the above models performance we can say that every model is performing well but, **Decision Tree and XGBoost models** are giving higher score compared to other models. So, we can use Decision Tree or XGBoost Model for predictions.
