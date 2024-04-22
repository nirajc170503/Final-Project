# Capstone Project
## Home Credit Default Risk.

Credit-lending plays a significant role in the banking sector. But the increase in non-performing loans has made the banking sector face huge losses and also has an impact on the economy of the country or the world. Thus an existential problem for any Loan provider today is to find out the Loan applicants who are very likely to repay the loan. This way companies can avoid losses and incur huge profits. 

So in this project, we are going to take the loan applicant data provided by Home Credit and identify the applicants who are most likely to default using  Supervised machine learning.

## About Home Credit

Home Credit Group is an international consumer finance provider which was founded in 1997 and has operations in 9 countries. Our responsible lending model empowers underserved customers with little or no credit history by enabling them to borrow easily and safely, both online and offline. 

Home Credit offers easy, simple and fast loans for a range of Home Appliances, Mobile Phones, Laptops, Two Wheeler's , and varied personal needs.

### Dataset

1.application_train

2.bureau

3.bureau_balance

4.credit_card_balance

5.installments_payments

6.POS_CASH_balance

7.previous_application

Dataset link: https://www.kaggle.com/c/home-credit-default-risk/data

## Project Cycle
### 1. Data Preprocessing (File1):
   
In this file, I've firstly cleaned seven datasets, addressing data type inconsistencies and missing values, and generated new features using domain knowledge and aggregation functions. This process involved retaining 122 features from a core dataset and adding around 30 new features, resulting in a comprehensive dataset ready for further analysis.

### 2. Feature Engineering (File2):
   
In this file, In our feature engineering process, I've implemented recursive feature elimination (RFE) to condense the number of features from your comprehensive dataset to just 15. This reduction is strategic, considering the large size of our dataset, as it will streamline future operations and analyses, ensuring efficiency and effectiveness in our data-driven tasks.

### 3. EDA (File3):

In our EDA file, I've conducted a comprehensive analysis on our final dataset with 15 features. This includes plotting distributions to understand the data's spread, using box plots for bivariate analysis to compare variables, and performing multivariate analysis to explore relationships among multiple variables. Additionally, I've applied outlier treatment using the capping method to handle extreme values and scaled the data using standard scaler to ensure uniformity and comparability across features.

### 4. Assumption (File4):
   
In our assumption file, I've examined the assumptions required for logistic regression. This step is crucial for ensuring the validity and reliability of our regression model, as it helps confirm that the data meets the necessary criteria for accurate interpretation of the results.

### 5. Base Model-Logistic regression (File5):

In our base model file, I've likely used a confusion matrix and a classification report to evaluate our logistic regression model. The confusion matrix summarizes the model's correct and incorrect predictions by class, while the classification report provides detailed metrics like precision, recall, and F1-score for each class. These analyses help assess the model's performance and identify areas for improvement.

### 6. Ml Models (File6):
   
In our ML model files, I've implemented a variety of machine learning models beyond the base logistic regression. This includes decision tree, KNN, random forest, AdaBoost, and XGBoost models. Additionally, I've explored using the SMOTE dataset to enhance the performance of these models, showcasing a comprehensive approach to improving model accuracy and robustness.

### 7. Summary Report (Word File):
   
It word file contains detail summary of entire project.
