# K-nearest neighbours

K-nearest neighbours (KNN) is a machine learning algorithm that is good a classifying moderately-sized datasets. It does so by looking at the n-dimensional space, where n is the number of features, and looking at nearby points to the data point you want to classify. It is a fairly simple technique but it can be very effective for data with low noise levels where the data points are nicely grouped together. Learning is almost instantaneously while classifying depends on the size of the training data.

The notebook in this tutorial will show you how to apply this technique to classifying penguins, diabetes patients, and books to display its strength and weaknesses.


| Dataset      | Source    | Licence |
|:-------------|:----------|:--------|
| diabetes.csv | [Pima Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) | CC0: Public Domain |
| booksummaries.txt | [CMU Book Summary Dataset](https://www.cs.cmu.edu/~dbamman/booksummaries.html) | CC-BY-SA 3.0 |
