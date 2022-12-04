## 2.3 EDA.
[Video](https://www.youtube.com/watch?v=k6k8sQ0GhPM&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=14)
[Diapositivas](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)
### notas
Atributos y metodos de Pandas:
Pandas atributes and methods:
* df[col].unique() - returns a list of unique values in the series.
* df[col].nunique() - returns the number of unique values in the series.
* df.isnull().sum() - returns the number of null values in the dataframe.

Matplotlib and seaborn methods:
* %matplotlib inline - assure that plots are displayed in jupyter notebook's cells
* sns.histplot() - show the histogram of a series.

Numpy methods:
* np.log1p() - applies log transformation to a variable and adds one to each result
Long-tail distributions usually confuse the ML models, so the recommendation is to transform the target variable distribution to a normal one whenever possible.
