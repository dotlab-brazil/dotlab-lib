==============
Data analysis
==============

To get the data distribution you can use the ``dotlab.data_analysis()`` function:

.. py:function:: data_analysis.get_distribution(df, target_col, numeric_columns=[])

  Get DataFrame distribution for a given target column.

  :param df: DataFrame to analyze
  :param target_col: Target column to analyze
  :param numeric_columns: List of numeric columns to analyze
  :return: A new DataFrame with the data distribution