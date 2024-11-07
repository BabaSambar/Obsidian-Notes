KFold is a concept in [[SkLearn Library]] in which multiple iterations of same or different models are passed to minimize the error in output.
StratifiedKFold adjusts some values which might be concentrated at one end of inputs.
For this CrossValueScore is also used.
```python
from sklearn.model_selection import StratifiedKFold
kf = StratifiedKFold()
kf = KFold(n_splits=10, shuffle=True)

def get_score(estimator, xtrain, xtest, ytrain, ytest):
    estimator.fit(xtrain, ytrain)
    return estimator.score(xtest, ytest)

for train_index, test_index in kf.split(iris.data):
    xtrain, xtest, ytrain, ytest = iris.data[train_index], iris.data[test_index], iris.target[train_index], iris.target[test_index]
```
n_splits specify number of divisions to be done on the KFold algorithm.
```python
print(cross_val_score(Model(), data, target))
```

TAGS: 