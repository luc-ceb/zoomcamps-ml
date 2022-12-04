## 2.8 Baseline model forcar price prediction project.
[0Video](https://www.youtube.com/watch?v=SvPpMMYtYbU&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=19)
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)
### Notes
* In this lesson we build a baseline model and apply the df_train dataset to derive weights for the bias (w0) and the features (w). For this, we use the train_linear_regression(X,y) function from the previous lesson.
* Linear regression only applies to numerical features. Therefore, only the numerical features from df_train are used for the feature matrix.
* We notice some of the features in df_train are nan. We set them to 0 for the sake of simplicity, so the model is silvable, but it will be appropriate if a non-zeo value is used as the filler (e.g. mean value of the feature).
* Once the weights are calculated, then we apply them on g(X) = w0 + X . w to derive the predicted y vector.
* Then we plot both predicted y and the actual y on the same histogram for a visual comparision.


