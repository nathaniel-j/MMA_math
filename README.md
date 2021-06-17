# MMA_math
### data analysis on the concept of MMA math as an outcome predictor

The file MMA_math.ipynb is a Jupyter notebook project with data analysis on the usefulness of the MMA math as a predictor for event outcomes. In this project I used an existing dataset I came across on Kaggle.com that contained extensive data on every fight in modern UFC history to develop and test a model to try to predict the fight winner. What I refer to as "MMA math" is the idea that if fighter A has beaten fighter X, and fighter B lost to fighter X, then fighter A **should** beat fighter B. 
```
if (A > X) and (B < X):
    return A > B
```
While this seems like a pretty logical and intuitive concept, I discovered that in the UFC it doesnt seem to hold true and I put forward 4 primary reasons that is the case. Even though this data set is not that great for machine learning due to the low correlative value of any of the features, I had a great time diving in and getting to know the data and will probably come back and build a ML model in the future. 
