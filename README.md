# Lab---Imbalance-Data.week9
Lab - Imbalance Data.week9
Instructions
Load the dataset and explore the variables.
We will try to predict variable Churn using a logistic regression on variables tenure, SeniorCitizen,MonthlyCharges.
Extract the target variable.
Extract the independent variables and scale them.
Build the logistic regression model.
Evaluate the model.
Even a simple model will give us more than 70% accuracy. Why?
Synthetic Minority Oversampling TEchnique (SMOTE) is an over sampling technique based on nearest neighbors that adds new points between existing points. Apply imblearn.over_sampling.SMOTE to the dataset. Build and evaluate the logistic regression model. Is it there any improvement?
Tomek links are pairs of very close instances, but of opposite classes. Removing the instances of the majority class of each pair increases the space between the two classes, facilitating the classification process. Apply imblearn.under_sampling.TomekLinks to the dataset. Build and evaluate the logistic regression model. Is it there any improvement?
