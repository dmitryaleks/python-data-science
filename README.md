# Notes on "Python Data Science Handbook"

## Pandas

[Jupyter Notebook demonstrating Series and DataFrame manipulations](notebooks/pandas-series-and-dataframes.ipynb)

### Series

Series is an extended version of a NumPy array that contains a sequence on values with an explicitly defined index. Index can be numberic or can consist of alphanumeric labels while index values don't have to be sequential.

### DataFrame

If a Series is an analog of a one-dimensional array with flexible indices, a DataFrame is an analog of a two-dimensional array with both flexible row indices and flexible column names. Just as you might think of a two-dimensional array as an ordered sequence of aligned one-dimensional columns, you can think of a DataFrame as a sequence of aligned Series objects. Here, by “aligned” we mean that they share the same index.

### Index

Index can be thought of either as an immutable array or as an ordered set (technically a multiset, as Index objects may contain repeated values).
