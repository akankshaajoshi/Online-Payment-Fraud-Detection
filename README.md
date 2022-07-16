# Online-Payment-Fraud-Detection

Online payment fraud detection is a logistic regression based prediction model that predicts whether the given transaction is fraud or not with an accuracy of 91.0%.
Dataset for this project is taken form kaggle and can also be downloaded with the help of the given link/api call. 
Link: https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset
Dataset API Call: kaggle datasets download -d rupakroy/online-payments-fraud-detection-dataset

Prediction model was created using a sequence of methodologies which are: 

1.Data wrangling: Data cleaning was not required for the dataset as it already had the data encoded in the proper format. 

2.Data preprocessing: Conversion of categorical variables to discrete numbers for the prediction algorithm. Information about the transaction ID details was retained by setting it as the index. 

3.Exploratory data analysis: Usage of libraries such as Matplotlib and Seaborn to check relation between feature values. Feature selection by feature and correlation analysis. Dropping features with very low correlation to improve the running time of the algorithm and reducing hidden parameters.

4.Prediction model: A major issue of class imbalance is handled by SMOTE(Synthetic Minority Oversampling Technique) to create equal classes for each of the target values. Logistic regression is chosen as the running algorithm due to its simplicity and high accuracy on the data. 

5.Model tuning: Hyperparameter tuning on a logistic regression model to predict the final values. 3-fold cross validation test and classification reports were used to check model suitability. 

An overall accuracy metric of 91.0% is achieved for the prediction model. 
