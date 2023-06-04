# Class 12 reading

## why this topic matters?


## reading Questions

1. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?

reqresstion use relationships among variables those variables can be dependent(outputs) or independent(inputs).

in data analysis we need to know the relation between some feild and regression answer how several variables are related.

2. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.

first you import numpy and the type of regression

```python
import numpy as np
from sklearn.linear_model import LinearRegression
```

second you create model

```python
model = LinearRegression()
```

third fit it

```python
# x and y are data you provided
model.fit(x, y)
```

last is getting the results

```python
result = model.score(x,y)
```

3. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?

the purpose of splitting the dataset is to evaluate the performance of the model for unseen data

it contribute by:

1. detection of overfitting
2. model selection and comparison
3. unbiased performance estimation
4. hyperparameter tuning

## Things I want to know more about