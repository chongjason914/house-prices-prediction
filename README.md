# House Prices: Advanced Regression Techniques

## Introduction
This repository contains an end-to-end analysis and solution to the [Kaggle house prices prediction competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview).

## Problem statement
The aim of this competition is to analyse 79 different features that describe every aspect of the residential homes in Ames, Iowa and subsequently make predictions on the final sale price of
each home. This is an example of a regression problem in machine learning as sale price, which is our target variable, has a continuous distribution.

The key practice skills in this competition are:
- Creative feature engineering
- Advanced regression techniques like random forest and gradient boosting

## Evaluation metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sale prices. 

## Data description
Information regarding the columns in the dataset can be found in the data description text file as part of this repository.

## Notebook Content
**0. Introduction**

**1. Import libraries**

**2. Import and read data**

**3. Exploratory data analysis (EDA)**
- 3.1 Descriptive statistics
- 3.2 Check data types
- 3.3 Feature analysis
  - 3.3.1 Reponse (target) variable
  - 3.3.2 Correlation between numerical variables
  - 3.3.3 Numerical variable: OverallQual
  - 3.3.4 Numerical variable: GrLivArea
  - 3.3.5 Numerical variable: GarageCars
  - 3.3.6 Numerical variable: TotalBsmtSF
  - 3.3.7 Numerical variable: FullBath
  - 3.3.8 Numerical variable: YearBuilt
  - 3.3.9 Mega scatter plot
- 3.4 Examine missing data

**4. Data preprocessing**
- 4.1 Impute missing values
  - 4.1.1 Missing values in garage
  - 4.1.2 Missing values in basement
  - 4.1.3 Missing values in masonry veneer
  - 4.1.4 Other missing values
- 4.2 Detect and remove outliers
  - 4.2.1 Make sure outliers have been removed from GrLivArea and TotalBsmtSF
- 4.3 Apply log transformation to sale price
- 4.4 Apply Box-Cox transformation to numerical features with high skewness
- 4.5 Feature engineering
  - UnfBsmt
  - HasWoodDeck
  - HasOpenPorch
  - HasEnclosedPorch
  - Has3SsnPorch
  - HasScreenPorch
  - YearsSinceRemodel
  - TotalHomeQuality
  - TotalSF
  - YearBuiltAndRemodel
  - TotalBathrooms
  - TotalPorchSF
  - HasPool
  - Has2ndFloor
  - HasGarage
  - HasBsmt
  - HasFireplace
- 4.6 Encode categorical features

**5. Modelling**
- 5.1 Get the new training and test set
- 5.2 Define cross-validation strategy and evaluation metric
- 5.3 Model evaluation
  - Ridge
  - Lasso
  - Elastic net
  - Support vector regressor
  - Gradient boosting
  - Light GBM
  - XGBoost
- 5.2 Make predictions on test data using Ridge

**6. Conclusion**

## References
I have made references to the following notebooks in the making of this notebook:
- [Comprehensive data exploration with Python](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python) by [Pedro Marcelino, PhD](https://www.kaggle.com/pmarcelino)
- [#1 House Prices Solution [top 1%]](https://www.kaggle.com/jesucristo/1-house-prices-solution-top-1) by [Nanashi](https://www.kaggle.com/jesucristo)
- [How I made top 0.3% on a Kaggle competition](https://www.kaggle.com/lavanyashukla01/how-i-made-top-0-3-on-a-kaggle-competition#EDA) by [Lavanya Shukla](https://www.kaggle.com/lavanyashukla01)
- [Stacked Regressions: Top 4% on LeaderBoard](https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard) by [Serigne](https://www.kaggle.com/serigne)

## My platforms 
Reach out to me if you have any questions!
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/channel/UCQXiCnjatxiAKgWjoUlM-Xg?view_as=subscriber)
- [Medium](https://www.medium.com/@chongjason)
