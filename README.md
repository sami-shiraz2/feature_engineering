# feature_engineering

Link of dataset:
https://www.kaggle.com/yogeerp/mercedes

# One Hot Encoding:
This is the technique use to transform categorical data (values) in integer,
So this made the dataset messy and increase it dimentionally, which affect the model accuracy.

# Count and Frequency Encoding (High Cardinality):
Another way to refer to variables that have a multitude of categories, is to call them variables with high cardinality.

If we have categorical variables containing many multiple labels or high cardinality,then by using one hot encoding, we will expand the feature space dramatically.

One approach that is heavily used in Kaggle competitions, is to replace each label of the categorical variable by the count, this is the amount of times each label appears in the dataset. Or the frequency, this is the percentage of observations within that category. The 2 are equivalent.
