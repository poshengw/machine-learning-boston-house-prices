## Machine Learning Engineer Nanodegree
## Model Evaluation and Validation

<br/>

### Predicting Boston Housing Prices

### Project Summary:
- Evaluate the performance and predictive power of a model. 
- **Data Exploration**.
- Defined a Performance Metric: **coefficient of determination (R^2)** to quantify your model's performance. The coefficient of determination for a model is a useful statistic in regression analysis, as it often describes how "good" that model is at making predictions.
- Performed **DecisionTreeRegressor** with different max_depth correspoinding to different generalization ability. Complexity curve explains the graph for a decision tree model that has been trained and validated on the training data using different maximum depths. The graph produces two complexity curves — one for training and one for validation.
- **Bias-Variance Tradeoff** investigation.
- Perfromed **Grid search technique** and how it can be applied to optimize a learning algorithm to find the best hyperparameters.
- Performed **Cross-Validation technique**: k-fold cross-validation training technique.
- **Sensitivity and robust**: Run the fit_model ten times with different training and testing sets to see how the prediction for a specific client changes with respect to the data it's trained on.
- Analyzed performance graphs for a learning algorithm with varying parameters and training set size to pick the optimal model that best generalizes for unseen data.

### Data:

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
