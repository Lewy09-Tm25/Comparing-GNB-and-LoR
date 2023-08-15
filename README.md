# Comparing-GNB-and-LoR

The primary focus of this project is to understand the functioning of 2 very well-known classification algorithms, Gaussian Naive Bayes and Logistic Regression. They have been used on the same dataset of https://archive.ics.uci.edu/dataset/94/spambase.

The repo contains two noteboks namely Gaussian Naive Bayes.ipynb and Logistic Regression.ipynb. Following is the high-level explanation of both.

## Gaussian Naive Bayes.ipynb
The Jupyter notebook contains 5 parts to it.
#### Part 1 : Exploratory Data Analysis
Here the data is analysed for it features as well importance. From data cleaning to correlation among the features, this part contains all the possible and most efficient engineering of data.
#### Part 2 : Model training
Leveraging sklearn library's in-built method GaussianNB(), a model has been created and fit into the training data that was split in the earlier part.
#### Part 3 : Analysing model performance
Using sklearn library's in-built method cross_val_predict(), the classifier goes through the process of cross validating the model with 3 folds. And thereafter, the results are visualized graphically and interpreted.
#### Part 4 : Evaluating model on test data
The model with best possible set of hyperparamters is selected and is used to predict the test set data. Here, the classification is done and their interpretations concurred.
#### Part 5 : Written report 
This is the last part of the notebook where the project is understood and whether the Naive Bayes assumptions are held.

## Logistic Regression.ipynb
The Jupyter notebook contains 5 parts to it.
#### Part 1 : Exploratory Data Analysis
Here the data is analysed for it features as well importance. From data cleaning to correlation among the features, this part contains all the possible and most efficient engineering of data.
#### Part 2 : Model training
Leveraging sklearn library's in-built method LogisticRegression(), a model has been created and fit into the training data that was split in the earlier part.
#### Part 3 : Analysing model performance
Using sklearn library's in-built method cross_val_predict(), the classifier goes through the process of cross validating the model with 3 folds. And thereafter, the results are visualized graphically and interpreted.
#### Part 4 : Evaluating model on test data
The model with best possible set of hyperparamters is selected and is used to predict the test set data. Here, the classification is done and their interpretations concurred.
#### Part 5 : Written report
Evidently, the above 4 parts are not disalike to GNB's notebook, and hence this is the part where the comparisons between the 2 models have been made.
