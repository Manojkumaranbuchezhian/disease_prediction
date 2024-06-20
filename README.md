# disease_prediction
It is a robust machine-learning model that can efficiently predict the disease of a human, based on the symptoms that he/she possesses.

# Data set description
This dataset consists of two CSV files one for training and one for testing. There is a total of 133 columns in the dataset out of which 132 columns represent the symptoms and the last column is the prognosis.

# Algorithm
1.Reading the dataset

2.Splitting the data for training and testing the model

3.Model Building: [K-Fold Cross-Validation, Support Vector Classifier, Gaussian Naïve Bayes classifier, Random Forest classifier]

4.Using K-Fold Cross-Validation for model selection

5.Building robust classifier by combining all models

6.Fitting the model on whole data and validating on the Test dataset

7.Creating a function that can take symptoms as input and generate predictions for disease

8.Calling the function

9.End of the program

# Approach
Gathering the Data: Data preparation is the primary step for any machine learning problem. We will be using a dataset from Kaggle for this problem. This dataset consists of two CSV files one for training and one for testing. There is a total of 133 columns in the dataset out of which 132 columns represent the symptoms and the last column is the prognosis.

Cleaning the Data: Cleaning is the most important step in a machine learning project. The quality of our data determines the quality of our machine-learning model. So it is always necessary to clean the data before feeding it to the model for training. In our dataset all the columns are numerical, the target column i.e. prognosis is a string type and is encoded to numerical form using a label encoder.

Model Building: After gathering and cleaning the data, the data is ready and can be used to train a machine learning model. We will be using this cleaned data to train the Support Vector Classifier, Naive Bayes Classifier, and Random Forest Classifier. We will be using a confusion matrix to determine the quality of the models.

Inference: After training the three models we will be predicting the disease for the input symptoms by combining the predictions of all three models. This makes our overall prediction more robust and accurate.
