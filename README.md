# classification-challenge

# Classification Challenge - Spam Detector

In this challenge we are tasked with the analysis of email meta data to determine if the email is spam or not spam.

## Workflow
1. Prepare original data by reading it into a pandas data frame
2. Split the data into our target (y) and data (X) series and dataframe, respectively
    - using the train_test_split method from sklearn to generate the training and testing dataframes
3. Using the StandardScaler, scale the testing and training data
4. Fit, train and predict using LogisticRegression modeling
5. Fit, train and predict using RandomForest modeling
6. Provide best results details.