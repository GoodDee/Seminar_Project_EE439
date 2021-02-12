# Seminar_Project_EE439
This repository contains all my notebook files that are used for writing the research article. 
  
  
## StoryBoard on Two Plots (Good for Reviewing the Result)    
[https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Storyboard%20EE439.pptx](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Storyboard%20EE439.pptx)  
  
  
## Title  
Evaluating the Role of Volatility in Predicting SET Index and Exploring Volatility Behavior From SET Index to Individual Stocks  
  
## Abstract  
This study evaluates the role of technical indicators in four categories (trend, momentum, volatility, volume) in predicting changes in SET index movement in multi-class classification framework. Models conducted in this study are logistic regression and decision tree. This predictive model uses training data from 2008 to 2017, validating data in 2018 and testing data in 2019. Specifically, the role of volatility in prediction model is evaluated by using feature importances from decision tree model, and its associated interpretation is done using the results from logistic regression. To start exploring the behavior of this variable, 14-day standard deviation on SET index is chosen as representing volatility under the linear regression framework. However, the result from using SET index does not always generalize to individual stocks due to their heterogeneity. Therefore, the snapshot of volatility behavior in individual stocks for the past few years (2015-2019) is examined by considering historical volume traded as one aspect of heterogeneity. By sorting the stocks on historical volume traded and splitting stocks into ten deciles, linear regression was employed in each group for each year. The exploratory data analysis conducted in this study could explain intuition behind volatility clustering and response to shocks found in SET Index and among individual stocks. This result may give implications on applying technical indicators as trading strategies.  
  
## List of Models  
  
**1. Predictive Models on SET using technical indicators as features in form of Logistic Linear Regression and Decision Tree**  
  A. EDA on SET: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0.ipynb)  
  B. Predictive Model on SET: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part2_Revised.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part2_Revised.ipynb)  
  C. Results via visualization: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part3_Revised.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part3_Revised.ipynb)  
  
**2. Explain volatility clustering and asymmetric responses to shocks in form of Linear Regression on Individual Stocks**  
  A. Preliminary analysis on SET Index: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part4.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V0_Part4.ipynb)  
  B. Algorithm itself: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V1.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V1.ipynb)  
  C. Results via visualization: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V1_Part2.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V1_Part2.ipynb)  
  
**3. Exploratory analysis of technical indicators and features across Individual Stocks and across time (2015-2020)**  
  A. Algorithm itself: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V2.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V2.ipynb)  
  B. Results via visualization: [https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V2_Part2.ipynb](https://github.com/GoodDee/Seminar_Project_EE439/blob/main/Model_V2_Part2.ipynb)  
