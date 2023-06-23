# IBM_Telecom_Classification
This project is on customer churn prediction. The main objective of my project was to build a predictive model to generate a prioritized list of customers most vulnerable to churn.
Dataset link is here https://www.kaggle.com/datasets/blastchar/telco-customer-churn

predict variable (desired target): y — has the customer churned? (binary: “1”, means “Yes”, “0” means “No)

I cleaned the dataset to remove the missing variables and one hot encoded several categorical variables. I explored the correlation between several features and the target variable.I then used a correlation matrix to explore if there was any correlation between different features. I included all features to predict the target variable (customer churn).

My target variable was unbalanced. So I balanced the target variable with SMOTE (Synthetic Minority Oversampling Technique). With my training data created, I up-sampled the minority sample( in our case the 'yes_churn' (customers who churn) sample using the SMOTE algorithm.
