## 2.13 Regularization.
[Video](https://www.youtube.com/watch?v=91ve3EJlHBc&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=24)
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)
### Notes
If the feature matrix has duplicated columns, it does not have an inverse matrix. But, sometimes this error could be passed if certain values are slightly different between duplicated columns.

So, if we apply the normal equation with this feature matrix, the values associated with duplicated columns are very large, which decreases the model performance. To solve this issue, one alternative is adding a small number to the diagonal of the feature matrix, which corresponds to regularization.

This technique works because the addition of small values to the diagonal makes it less likely to have duplicated columns. The regularization value is a parameter of the model. After applying regularization the model performance improved.