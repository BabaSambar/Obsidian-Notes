#Linear_Model in [[SkLearn Library]]
```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
# Training model
model.fit(input_array, target_array)
# Predicting from model
print(model.predict(input_array))
# To know the score of model
print(model.score(input_array, target_array))
```
