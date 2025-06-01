# Feature Engineering

## Feature Selection
---

### RFE
RFE (Recursive Feature Elimination) is a feature selection technique that iteratively removes the least relevant features based on a base model, until only the most important ones remain. It improves model performance by reducing dimensionality, preventing overfitting, and speeding up training.

**Activities**
- [RFE](https://github.com/Kaiziferr/feature_engineering/blob/main/feature_selection/02_RFE.ipynb): Practical implementation of RFE for regression and classification models, as well as the use of a function to determine the importance criterion by invoking the 'importance_getter' parameter.

### Mutual Information
Mutual information measures how much uncertainty is reduced about one variable by knowing another, using the concept of entropy from information theory. It is a non-negative and symmetric metric that equals zero only when the variables are independent. Although it has no upper bound, values above 2.0 are uncommon. It is useful for detecting non-linear relationships between variables, but it has limitations: it does not capture interactions between features and can be redundant when selecting similar variables. It is ideal for datasets with medium to large sample sizes and without high dimensionality.

**Activities**
- [Mutual Information](https://github.com/Kaiziferr/feature_engineering/blob/main/feature_selection/01_mutual_Information_MI.ipynb): Implementation of mutual information methods for classification and regression, specifying categorical and discrete variables, as well as identifying nearest neighbors to consider marginal and joint probabilities in order to estimate entropy.
