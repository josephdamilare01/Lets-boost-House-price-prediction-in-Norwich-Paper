# Lets-boost-House-price-prediction-in-Norwich-Paper
This repository contains the code and dataset used for the project House Price Prediction in Norwich.


# House Price Prediction in Norwich

This repository contains the R code and dataset used for the project *House Price Prediction in Norwich*, developed as part of the coursework for modules ECO-7000A (Econometric Methods) and ECO-7009A (Financial Econometrics) at the University of East Anglia. This project aims to analyze and predict property prices in Norwich using various econometric and machine learning models.

## Project Overview

The primary objective of this project is to build robust models to predict house prices based on property characteristics and economic indicators. The project explores multiple machine learning techniques, including advanced boosting algorithms, to achieve accurate predictions.

## Contents

- **Dataset**: The *HOUSE_2023* dataset, provided by the University of East Anglia's School of Economics, specifically for students enrolled in the aforementioned modules. Access to this dataset may require authorization from UEA.
- **Code**: R scripts that implement data preprocessing, exploratory data analysis (EDA), and predictive modeling techniques. Models include:
  - **CatBoost**
  - **XGBoost**
  - **Gradient Boosting (GBoost)**
  - **LightGBM (LightBoost)**

## Getting Started

### Prerequisites
To run the code in this repository, you will need to have R installed along with the following packages:
- `catboost`
- `xgboost`
- `lightgbm`
- `gbm`
- `dplyr`
- `ggplot2`
- `caret`
- `data.table`

You can install the required packages in R as follows:

```r
install.packages(c("catboost", "xgboost", "lightgbm", "gbm", "dplyr", "ggplot2", "caret", "data.table"))
