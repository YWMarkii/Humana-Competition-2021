# Humana-Competition-2021
Humana-Mays Healthcare Analytics Case Competition offers an opportunity for U.S. master’s students to showcase their analytical skills and solve a real-world business problem for Humana utilizing real data.  
This project is conducted by Duke Fuqua MQM candidates Yingdong, Yijie, and Yuqing, along with Tiankai, an MAE candidate from Duke Econ.
* The original dataset was not allowed to be published due to the NDA with Humana. 

## Business Problem
**Backgroud**: A portion of the Humana members, like in the general population, are hesitant or resistant to get the vaccine due to a combination of factors that include, misinformation, and lack of trust in the vaccine.  
**Goal**: Using the provided data and potentially supplementing with public data, create a model to predict which members are likely to be hesitant so that Humana can design targeted outreaches for these members, prioritized to reach the most vulnerable and underserved populations to receive health solutions.  

## Data Source  
1. Dataset provided by Humana with 350+ features, which includes information of claims, demographics, credit, condition, etc. 
2. External dataset of historical county-level COVID-19 vaccination data from CDC. https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh

## Solution: Predicting the Likelihood of Hesitancy to COVID-19 Vaccine for Medicare Members Using a Gradient Boosting Tree Approach
After evaluating different models selection, we decided to use XGBoost, a gradient boosting algorithm, for building our predictive model. XGBoost implements a gradient boosting decision tree algorithm designed to be incredibly efficient and accurate. To maximize performance of our XGBoost model, we utilized a 10-fold Grid Search to tune the models hyperparameters. 

## Award: Top 20 on the leadingboard
Our model ranked #20 on the leading board with 0.6691 AUC and 0.9887 fairness score.  
  
![image](https://user-images.githubusercontent.com/63487847/148133190-d4eb58a4-4a1a-4d00-9dec-90331c083cda.png)
