# LightGBM Repayment Capabilities
<img width="704" alt="image" src="https://user-images.githubusercontent.com/125685678/221344416-4fd16b85-066b-4efb-b3bf-923b8b2b7851.png">  

*Predicting repayment capabilities of loan applicants*
# Business Problem
Many people struggle to get loans due to insufficient or non-existent credit histories. Often, untrustworthly lenders take advantage of this group of
people. Home Credit strives to broaden financial inclusion for the unbanked population by providing a 
 safe borrowing experience. To best serve this group of individuals, Home Credit makes use of a variety of  data 
 to predict their clients' repayment abilities. Home Credit wants to ensure loan applicants that are
 capable of repayment are not rejected and that loans are given with a principal, maturity, and 
repayment calendar that will empower their clients to be successful.

# How is Success Measured?
Home Credit measured the success of this project using AUC Score.
AUC is best when trying to minimize both false positives and false negatives. 

# Overview of the Process
1. Exploratory Analysis
-  Addressed the imbalanced data
-  Feature analysis of the given 219 features
2. Feature Engineering
-  Aggregating features to decrease number of rows
-  Joined 7 datsets together
-  Created time features and financial ratios
3. Model Building
-  LightGBM was the best performing model
-  Feature Selection
4. Model Insights
- Best performing LightGBM model had an AUC score of 0.787 which allows Home Credit the confidence 
to extend loans to people with insufficient credit histories.
- To further improve the AUC score, more feature engineering would help. Of the top 15 features, 9 were features I created.
