## Description

This a lung cancer dataset from https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer. It has 16 features and 309 records. The goal of the project is to investigate the correlation between the variables, predict how likely and inidvidual who smokes is to develop lung cancer and if how likely women who smoking and drinking are susceptible to develop the disease compared to men.

Some Questions include:

- Are there any missing data in the dataset?
- Show the correlation between the data
- Is there a correlation between Gender and lung Cancer?
- What is the age distribution?
- Given the features can lung cancer be predicted?
- What would be the accuracy of the model?
- Are there all the features necessary to predicting how likely a person is to developing the disease?
- Can number of features be reduced for simplicity?


## Methodology

The entire project is written in python and the library stack includes pandas for loading the data and dataFrame manipulations, numpy and scikit-learn for data mining, mathematical and probabilistic operations, as well as seaborn and matplotlib for data visualization.

The data are loaded into a pandas data frame and the factors are encoded into binary data.

This project uses a correlation matrix to show the correlation between Gender and Lung Cancer.

The dataframe is then split into a training set and a test set, and a logistic regression was implemented for the prediction. The model is trained on the training set and then tested on the test set.

A confusion matrix is used to compare the model's output to the true result.

To answer the question about the importance of the features in predicting the disease, a principal component analysis (PCA) is implemented.
