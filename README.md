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
<img width="549" alt="image" src="https://user-images.githubusercontent.com/125685678/226031123-bcdd26e2-1a73-4559-b017-11e34bacaa36.png">
-  Feature analysis of the given 219 features
<img width="399" alt="image" src="https://user-images.githubusercontent.com/125685678/226031458-715f7b0e-da62-439a-b050-89a488a75ca6.png">

2. Feature Engineering
-  Aggregating features to decrease number of rows
<img width="1070" alt="image" src="https://user-images.githubusercontent.com/125685678/226032366-111b1093-ea73-4a8e-92f4-1e561d1b1168.png">

-  Joined 7 datsets together
<img width="1094" alt="image" src="https://user-images.githubusercontent.com/125685678/226031829-354864dd-8924-447a-8e5c-ce824039a7cc.png">
-  Created time features and financial ratios
<img width="1111" alt="image" src="https://user-images.githubusercontent.com/125685678/226032150-4aca2ed3-de94-47ab-93a6-c1259c13cc70.png">

3. Model Building
-  LightGBM was the best performing model
-  Feature Selection
4. Model Insights
- Best performing LightGBM model had an AUC score of 0.787 which allows Home Credit the confidence 
to extend loans to people with insufficient credit histories.
- To further improve the AUC score, more feature engineering would help. Of the top 15 features, 9 were features I created.
