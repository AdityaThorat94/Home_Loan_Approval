# Home_Loan_Approval
Home Loan Approval Prediction
This project aims to predict loan approval using a logistic regression model. The project uses a training dataset and testing dataset of loan applicants, with home  loan approval being the target.

Table of Contents
Introduction
Data
Data Cleaning
Data Preprocessing
Model Training
Results
Conclusion

Introduction
Home Loan approval is an important decision for any bank or financial institution. This project aims to predict loan approval using a logistic regression model. The model is trained on a dataset of loan applicants and their characteristics.

Data
The dataset used in this project contains information on loan applicants, including their age, income, education, and other characteristics. The dataset is split into a training dataset and a testing dataset. The training dataset is used to train the logistic regression model, while the testing dataset is used to evaluate the performance of the model.

Data Cleaning
The dataset has null values, objects and is imbalanced. To prepare the data for training the model, the null values were handled by either replacing them with the median value or dropping the row with null value. The objects were converted into numeric values using One Hot Encoding. Further, to handle the imbalance in the target variable I stratified them

Data Preprocessing
The dataset was preprocessed by scaling the data using StandardScaler. This was done to ensure that all features were on the same scale and to improve the performance of the model.

Model Training
The logistic regression model was trained on the preprocessed data using scikit-learn. The model was trained on the training dataset and evaluated on the testing dataset using accuracy score, precision score, recall score and f-1 score.

Results
The logistic regression model achieved an accuracy of 83.7%, precision score of 87%, recall score of 84% and f1 score of 82%.

Conclusion
This project demonstrates the use of logistic regression in predicting loan approval. The model achieved good results on the testing dataset, indicating that it can be used to make accurate predictions. The code for this project is available on GitHub.
