# LendingClub Default Classification

John Michitsch

## Abstract

Peer-to-Peer Lending sites like LendingClub allow investors to play 'bank' and earn money from making unsecured loans.
Along with the profit potential comes default risk. 
Can we use historical loan data to predict which loans will ge into default?

## Design

Individual, like myself, wants to invest in the peer-to-peer market. 
I can only invest a limited amount at a time so avoiding bad loans is more important than missing out on some good ones. 

## Data

### Data Source

Data was found on Kaggle https://www.kaggle.com/husainsb/lendingclub-issued-loans

CSV file of ~887K loans (70+ features including borrower  - state, zip, income - and loan - amount, term, rate, grade information)
from LendingClub between 2007 and 2015.

## Algorithms

A number of the classification algorithms available in sklearn (Logistic Regression, Decision Tree Classifier, Random Forest Classifier, 
Naive Bayes, K-NearestNeighbos), as well as Xgboost were run on the data.  Accuracy, Precision, F1, etc. scores and confusion matrices were generated and 
compared between algorithms. 

## Tools

Jupyter Notebook to write / execute Python code
Pandas / Numpy libraries for data manipulation
Mathplotlib and Seaborn for visualizations
Sklearn for classification algorithms and related functions
xgboost for XGBoost algorithm
imblearn for undersampling function


## Communication

Findings are consolidated in a Keynote presentation and the supporting Jupyter notebooks can be found here. 
(Prep_ notebooks contain EDA and export versions of the feature (X) dataframe
 Model_ notebooks load the saved dataframes and execute the various models)
 
