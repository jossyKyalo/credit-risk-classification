# **Module 12 Report**
## **Overview of the Analysis**
In this analysis, we evaluated various machine learning models to predict credit risk associated with loan applications. The primary goal was to classify loans as either 0 (healthy loan) or 1 (high-risk loan), providing the financial institution with insights to make informed lending decisions.

The dataset included financial information about loan applicants, such as credit history, income, loan amount, and other relevant features. Our aim was to predict the likelihood of loan default based on these factors.

**Key Variables:**
The target variable (loan_status) had the following value counts:
0 (Healthy Loans): 75036
1 (High-Risk Loans): 2500

**Machine Learning Process:**
1. Model Selection: Implemented multiple Logistic Regression 
2. Model Training: Trained the models using training data and validated them with test data.
3. Performance Evaluation: Assessed models using metrics like accuracy, precision, and recall.
   
## **Results**
**Machine Learning Model Performance**

+**Logistic Regression Model:**

 + Accuracy: 99%
   
 + Precision (Healthy Loans): 1.00
   
 + Precision (High-Risk Loans): 0.86
   
 + Recall (Healthy Loans): 1.00
   
 + Recall (High-Risk Loans): 0.91

## **Summary**
The Logistic Regression model performed the best among the evaluated models, achieving an accuracy of 99% with perfect precision and recall for healthy loans, and strong scores for high-risk loans. This suggests that it is highly effective in identifying both loan types, which is crucial for minimizing financial risk.

**Recommendations:**
Given its performance metrics, I recommend using the Logistic Regression model for credit risk assessment. The high precision for healthy loans ensures that most loans classified as healthy are indeed so, reducing potential losses.
