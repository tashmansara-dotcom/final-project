# final-project
Final project report
In this project at first loaded data from kaggle then loaded it on google colab then read this dataset  to understand it which this step called preprocessing and continued preprocessing by cleaning data from missing data and nans using several tools to make it able to apply several models after that we prepared data to the next by splitting it to training and testing data and did some EDA to better understanding the dataset and some visualization and also feature scaling to make data features as much as we can close to each other 

Next step is modeling we applied several model to find the best model to that fits the dataset like: RandomForestRegressor,decionTreeRegressor,
RandomForestclassifier,decionTreeclassifier, gridsearchcv, randomizedSearchcv,
KnnNeighbors(tested values 1,3,15), linear regression ,logesticRegression (L1,L2)
Hyperparameter tuning applied to improve model performance and avoid overfitting and underfitteng which unfortunately didn’t achieve that then used cross validation and k-fold cross validation to improve robustness of the models

Evaluated the model using regression metrics : MSE,RMSE,R2 score. 
Based on these results random forest regressor  and knn  we can say they performed well with some difference which also the grid search randomized search helped the random forest to improve its performance 
