# Lending-Club-Project
Methodologies applied in the project:
1- Data Extraction
2- Exploratory Data Analysis
3- Data Cleaning
4- Data Pre-processing
5- Machine Learning model using Linear Regression
6- Deep Learning model using ANN
7- Evaluation of Models
Project Goal:
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict whether or not a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. The "loan_status" column contains our label.

# Important Note: There are two different models done using different ways of data cleaning and preprocessing to reach the best possible accuracy.

# Conclusion:
Due different ways of data preprocessing, there are different accuracy results between the two models. The second model has a higher accuracy "89%" than the first model "81%" due to a bigger number of features using many dummy variables and deleting columns which may cause noise or do not affect the loan status, but both models faced difficulties on getting a high recall percentage in the 0 or the predicted charged off data. This resulted due to the high bias for the fully paid data. Enhancement can be done to have more data on the charged off loans and to be more informative to have better accuracy across the whole dataset.
