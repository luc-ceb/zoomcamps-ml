## 1.3 Supervised Machine Learning
[![Supervised Machine Learning](https://www.youtube.com/watch?v=j9kcEuGcC2Y&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=4)
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-13-supervised-machine-learning)
## Notes
In Supervised Machine Learning (SML) there are always labels associated with certain features. The model is trained, and then it can make predictions on new features. In this way, the model is taught by certain features and targets.

- Feature matrix (X): made of observations or objects (rows) and features (columns).
- Target variable (y): a vector with the target information we want to predict. For each row of X there's a value in y.
The model can be represented as a function g that takes the X matrix as a parameter and tries to predict values as close as possible to y targets. The obtention of the g function is what it is called training.

## Types of SML problemas
* Regression: the output is a number (car's price)
* Classification: the output is a category (spam example).
	- Binary: there are two categories.
	- Multiclass problems: there are more than two categories.
* Ranking: te output is the big scores associated with certain items. It is applied in reccomender systems.
In summary, SML is about teaching the model by showing different examples, and the goal is to come up with a function that takes the feature matrix as a parameter and makes predictions as close as possible to the y targets.
