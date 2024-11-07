For saving a Model in [[SkLearn Library]], we can use either #Pickle or #Joblib library from sklearn.externals
For #Pickle:
```python
import pickle
with open('file', 'wb') as f:
	pickle.dump(model, f)
```
```python
import pickle
with open('file', 'rb') as f:
	model = pickle.load(f)
```
For #Joblib:
```python
from sklearn.externals import joblib
joblib.dump(model, 'file')
```
```python
from sklearn.externals import joblib
model = joblib.load('file')
```

TAGS: