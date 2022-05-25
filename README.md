# House_Price_Prediction

## About the Project
This project comes from a Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) and was used as my Data Analytics course project. It can be a good practice of data exploration, feature engineering and some regression techniques in machine learning. 

## The Dataset
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It can act as an expanded version of the often cited Boston Housing dataset. For details of this dataset, apart from the above Kaggle link, you can also find the original paper work [here](http://jse.amstat.org/v19n3/decock.pdf). I've uploaded both the original dataset and Kaggle competition dataset.

In the project I used Kaggle competition dataset. There are 79 feature vaiables and 1 target variable (SalePrice). Different types of variables are provided here, including discrete, continuous, ordinal and nominal, which is good for practicing applying correct methods on different variables. 

## Workflow

### 1. EDA (exploratory data analysis)
- 1.1 Ckeck Variable Types
- 1.2 Deal with Missing Values (do imputations)
- 1.3 Variable Dependency (multicollinearity)
- 1.4 Target Variable: SalePrice (skewness)
- 1.5 Variable Distributions (visualizations)
- 1.6 Outliers
- 1.7 Correlations (visualizations, Pearson and Spearman coefficients)

### 2. Data Preparation
- 2.1 Remove Outliers
- 2.2 Feature Engineering
  - Create New Variables
  - Remove Redundant Variables
- 2.3 Variable Transformations (Log Transformation, Box-Cox Transformation)
- 2.4 Categorical Encoding
  - Nominal Variables: One-Hot Encoding
  - Ordinal Variables: Ordinal Encoding
- 2.5 Standardization
- 2.6 Dimensionality Reduction

### 3. Modelling
- 3.1 Basic Models
- 3.2 Nested Cross-Validation for Hyperparameter Tuning and Model Evaluation

You can find more details in the notebook. 

## Insights and Future Work
There are a lot of potential factors that can affect house prices, but some variables can just be noise. The key is to extract important information from the data and then build models based on it, which can avoid overfitting and improve model performance.

The current work focuses more on data exploration and preparation part. For the modelling part, more techniques can be experimented to imporve the performance like model stacking and detailed tuning. The pipeline can also be improved so that we can check the improvements come from different data processing parts.
