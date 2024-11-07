#Random_Forest classification in [[SkLearn Library]] is a method to classify input using multiple decision trees.
The most popular decision among the decision trees is considered as final output.
```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier(n_estimators=100)
model.fit(inputs, targets)
model.score(inputs, targets)
model.predict(inputs)
```
Here n_estimators means the number of decision trees.