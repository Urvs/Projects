# Data Science Portfolio

Author - Urvashi

This repository contains the files for the Portfolio task for COMP2200/6200 in S2 2022. 

## Introduction

In the repository, there are four portfolio notebooks with csv files.

The language and tools here used is python, libraries like sci-kit learn; seaborn, matlab for visuals and Jupiter notebook for running environment.

Used Anaconda distribution for installation of Jupiter Notebook and command prompt which is downloaded from [Anaconda distribution installer](https://www.anaconda.com/products/distribution).

Several other requisites are installed from package manager [pip](https://pip.pypa.io/en/stable/installation/), downloading get-pip.py file then run following command on the system.

```bash
python get-pip.py 
```
## Summary of Portfolio

#### a. Portfolio1
In this notebook, basic analysis of the dataset is done. 
The data display, removal of missing data, descriptive statistics, plotting boxplots, worked on outliers detection and removal. Here, Epinions_test_data.csv file is exported for results.

#### b. Porfolio2
This includes training a linear regression model to predict user's rating towards items covers data exploration (encoding and correlation), building models (splitting data and training four models with different features), making predictions (evaluate model and its performance) and result evaluation (visualization, comparing and analysis of the result). Here, Epinion_cleaned_data_portfolio_2.csv
is used.

#### c. Portfolio3
In this task, work is to train classification models to predict if the user likes or dislikes an item, using same Epinion file. With the use of different models and methods, comparison for better accuracy score of the model is done.
This notebook covers  encoding data, training data, logistic regression, the use of RFE model, k-NeighboursClassifier and hyper-tuning with GridSearchCV is covered.

#### d. Portfolio4
The dataset used here is of the airplane passengers. The analysis done here for reviewing passengers airplane experience. It covers cleaning data, data encoding, worked with outliers, used various models for accuracy comparison such as linear and logistic regression models, methods like RFE and hyper-tuning; show confusion matrix, F1-score, AUC-ROC Curve, accuracy scores; kNN and Support vector classifiers.

## License
None
