# Iris Species Classification

## Project Overview

This project uses machine learning to classify iris flowers into three species: Setosa, Versicolor, and Virginica. The classification is based on four features: sepal length, sepal width, petal length, and petal width.

## Dataset

* Number of records: 150
* Number of features: 4
* Target variable: Species

## Models Used

1. Logistic Regression
2. K-Nearest Neighbors (K-NN)
3. Decision Tree

## Results

All three models achieved an accuracy of 100% on the test dataset.

## Best Model

K-Nearest Neighbors (K-NN) was selected as the final model and saved as `iris_model.pkl`.

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Example Inference

```python
import joblib
import numpy as np

model = joblib.load("iris_model.pkl")

sample = np.array([[5.1, 3.5, 1.4, 0.2]])

prediction = model.predict(sample)

print(prediction[0])
```

## Author

Machine Learning Internship Task – Iris Species Classification
