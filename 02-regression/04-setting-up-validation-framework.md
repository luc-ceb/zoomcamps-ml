## 2.4 Setting up validation framework.
[Video](https://www.youtube.com/watch?v=ck0IfiPaQi0&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=15)
[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)
### Notas
In general, the dataset is split into three parts: training, validation, and test. For each partition, we need to obtain feature matrices (X) and y vectors of targets. First, the size of partitions is calculated, records are shuffled to guarantee that values of the three partitions contain non-sequential records of the dataset, and the partitions are created with the shuffled indices.
Pandas attributes and methods:
* df.iloc[] - returns subsets of records of a dataframe, being selected by numerical indices.
* df.reset_index() -restate the original indices
* del df[col] - eliminates target variables.

Numpy methods:
* np.arange() -returns an array of numbers.
* np.random.shuffle() - returns a shuffled array.
* np.random.seed() - set a seed.