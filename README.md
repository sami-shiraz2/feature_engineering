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

# Missing Values- Feature Engineering- Day 1
Lifecycle of a Data Science Projects

1) Data Collection Statergy---from company side,3rd party APi's,Surveys,Surveys
2) Feature Engineering---Handling Missing Values

Why are their Missing values?? Survey--Depression Survey

1) They hesitate to put down the information
2) Survey informations are not that valid
3) Men--salary
4) Women---age
4) People may have died----NAN

Data Science Projects---Dataset should be collected from multiple sources

# What are the different types of Missing Data?

# Missing Completely at Random, 
MCAR: A variable is missing completely at random (MCAR) if the probability of being missing is the same for all the observations. When data is MCAR, there is absolutely no relationship between the data missing and any other values, observed or missing, within the dataset. In other words, those missing data points are a random subset of the data. There is nothing systematic going on that makes some data more likely to be missing than other.

# Missing Data Not At Random(MNAR): 
Systematic missing Values There is absolutely some relationship between the data missing and any other values, observed or missing, within the dataset.


# Mean/ MEdian /Mode imputation:
When should we apply? Mean/median imputation has the assumption that the data are missing completely at random(MCAR). We solve this by replacing the NAN with the most frequent occurance of the variables
