# BIS568 final project (Machine learning application)
## Background Information & Problem Specification
Diabetes, a widespread chronic condition that occurs when the body is unable to properly regulate blood sugar (glucose) levels, demands effective early detection to enhance patient outcomes and reduce the burden on healthcare systems. Especially, in recent years, more and more young adults begin to suffer from diabetes, which severely influence their life qualities.
In our pursuit of accurate and efficient diagnostic tools, we turn to the MIMIC-III (Medical Information Mart for Intensive Care III) database—an invaluable resource that captures a wealth of clinical data from intensive care units. Harnessing the power of machine learning, we employed three distinct algorithms: Random Forest, XGBoost, and Logistic Regression.
Our objective is not just to predict diabetes but to contribute to a more personalized and proactive approach to healthcare.

## Patient Cohord Definition
Age 18-30
Alive
Visit Number Less Than 20

## Machine Learning Methods
Model 1: Logistic Regression
Model 2: XGBoost
Model 3: Random Forest

## Model Performance
![image](https://github.com/YuchenZhu2335/BIS568-final-project/assets/143673300/9432633b-0e75-4851-aa73-89986d1e2173)
![image](https://github.com/YuchenZhu2335/BIS568-final-project/assets/143673300/17b08914-f838-4e39-bd64-c4f3513efb8c)
![image](https://github.com/YuchenZhu2335/BIS568-final-project/assets/143673300/d735f90c-b59c-412c-b342-a55d9facef80)
Model 1: Logistic Regression
AUC = 0.60; PR-AUC = 0.08 Terrible Precision-Recall Curve; The model is also not well calibrated. 
Model 2: Random Forest
AUC = 0.95; PR-AUC = 0.83 Good Precision-Recall Curve; But the model is not that well calibrated.
Model 3: XGBoost
AUC = 0.93; PR-AUC = 0.72 Good Precision-Recall Curve; And the model is the most calibrated one among all three algorithms; Overall XGBoost is the best algorithm we can get.



