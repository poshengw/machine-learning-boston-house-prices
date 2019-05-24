# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

### Problem Summary:
- Evaluate the performance and predictive power of a model. 
- Data Exploration.
- Define a Performance Metric: coefficient of determination (denoted by R2) to quantify your model's performance. The coefficient of determination for a model is a useful statistic in regression analysis, as it often describes how "good" that model is at making predictions.
- DecisionTreeRegressor with different max_depth correspoinding to different generalization ability. Complexity curve explains the  graph for a decision tree model that has been trained and validated on the training data using different maximum depths. The graph produces two complexity curves — one for training and one for validation
- Bias-Variance Tradeoff investigation
- Grid search technique and how it can be applied to optimize a learning algorithm to find the best hyperparameters.
- Cross-Validation technique:  k-fold cross-validation training technique. What benefit does this technique provide for grid search when optimizing a model?
- ShuffleSplit: difference between shuffleSplit and  K-Fold cross-validation technique 
- Performs grid search over the 'max_depth' parameter for a decision tree regressor trained on the input data [X, y]
- Sensitivity and robust: Run the code cell below to run the fit_model function ten times with different training and testing sets to see how the prediction for a specific client changes with respect to the data it's trained on.

### Data:

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

