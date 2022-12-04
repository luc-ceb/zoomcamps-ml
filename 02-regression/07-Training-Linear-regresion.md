## 2.7 Training Linear regression.
[Video](https://www.youtube.com/watch?v=hx6nak-Y11g&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=18)
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)
### Notes
Obtaining predictions as close as possible to y target values requires the calculation of weights from the general LR equation. The feature matrix does not have an inverse because it is not square, so it is required to obtain an approximate solution, which can be obtained using the Gram matrix (multiplication of feature matrix and its transpose). The vector of weights or coefficients obtained with this formula is the closest possible solution to the LR system.

