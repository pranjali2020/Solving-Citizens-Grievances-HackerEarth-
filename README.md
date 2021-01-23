# Solving-Citizens-Grievances-HackerEarth-
In this problem, you are given a dataset that contains grievances of various people living in a country. Your task is to predict the importance of the grievance with respect to various articles, constitutional declarations, enforcement, resources, and so on, to help the government prioritize which ones to deal with and when.

###### [HackerEarth Machine Learning Hackathon](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-grievance-importance/)

# Contents
```
├── predict_importance.ipynb
├── Dataset
│   └── sample_submission.csv
│   └── test.csv
│   └── train.csv
└── README.md
```
# Installation
- Python 3
- Jupyter Notebok
Make sure the following Libraries are Installed
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable)

# Data Selection
This Data was provided by [HackerEarth](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-grievance-importance/).

# Preprocessing data:
Various Data Preprocessing Techniques are used to Clean the Data.
- Handled the Categorical data using Target Encoding, Hashing Encoding and One Hot Encoding.
- Used Feature Selection for filtering irrelevant or redundant features from given Dataset.
- Extracted informative features from date columns using pandas.
# Visualization
- For this part, I have used Seaborn and Matplotlib which are most popular visualisation libraries available.
- To detect outliers and get better insightes from the Data.

# Modeling 
- Used different machine learning Ensemble classifiers like Random Forest Classifier, LightGBM Classifier, Gredient Boosting Classifier and XGBoost.
- Used GridSearchCV to tune Hyper parameters.
- After that, I took Voting of 1 Random Forest, 1 LightGBM, 1 Gredient Booosting, and 1 XGBoost, which gave high Accuracy Score.

# Ranking 
![alt text](https://github.com/pranjali2020/Solving-Citizens-Grievances-HackerEarth-/blob/scgh/HackerEarthScore.png)

