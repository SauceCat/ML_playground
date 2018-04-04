
# A Never Complete Machine Learning List

## Get different data tables
- quick data exploration: how does each table look like? (data types, basic stats and graphs, size, shape)
- understand the major entity in each table: what is each table describing?
- understand the relationship between tables: how tables link to each other? 

## Feature engineering
- trace new features

## Target creation

## Reading and merging different tables
- how to merge tables? (define major key in each table)
- what happen after merging? percentage of merge successfully
- feature distribution through different tables
- basic stats about the final table: size, shape, uniqueness

## Data preprocessing
- imputation:  
  imputation report: imputation strategy, percentage of values to impute, impute with what value.  
- encoding: dates, categorial features  
  encoding report: encoding values and distribution  
- test whether all features are numeric and without any NaN value

## Model training
- model selection: well, we always use XGBoost
- cross validation and hyper parameter tuning
- need various model evaluation metrics and graphs
- feature selection: need good metrics to measure feature importance
- trace feature importance drift (measure model stability)
