# Random Forest Classification

The Random Forest Classifier is a set of decision trees from randomly selected subset of training set. It aggregates the votes from different decision trees to decide the final class of the test object.


## Advantage：
- It is one of the most accurate learning algorithms available. For many data sets, it produces a highly accurate classifier.

- It runs efficiently on large databases.
- It can handle thousands of input variables without variable deletion.
- It gives estimates of what variables that are important in the classification.
- It generates an internal unbiased estimate of the generalization error as the forest building progresses.
- It has an effective method for estimating missing data and maintains accuracy when a large proportion of the data are missing.


## Disadvantage：
- Random forests have been observed to overfit for some datasets with noisy classification/regression tasks.
- For data including categorical variables with different number of levels, random forests are biased in favor of those attributes with more levels. Therefore, the variable importance scores from random forest are not reliable for this type of data.

================================================
# About the project:
 
The dataset Iris consists of three classes - setosa, versicolor, virginica and features - 
sepal length (cm), sepal width (cm), petal length (cm), petal width (cm).

Using the RandomForestClassifier from sikit-learn with n_estimators = 100 (which means the number of trees in the forest) to train the model and result in accuracy of 97.7% .