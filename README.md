# Data Science Projects Using Python
My work - python and machine learning

# Machine-Learning-Models

****EDA-Diabetes.jpynb****

**Problem**: The goal of this assignment is to understand the logic and methods of exploratory data analysis (EDA)

**Task Performed**

Write Python scripts in order to complete the following tasks

1) Prepare the data in order to be ready to be fed to a model.
2) Look for missing, null, NaN records.
3) Find outliers.
4) Transform data - all entries should be numeric.
5) List all types of data, numeric, categorical,...
6) Perform EDA on data.
7) Present dependencies and correlations among the various features in the data.
8) List the most variables (Feature Importance) that will affect the target label.
9) State limitations/issues (if any) with the given dataset.

****Model_Bank_Marketing.jpynb****

**Problem**: The goal of this assignment is to understand the 'power' of various Machine Learning Classification algorithms applied to a dataset. By contrasting these very well-diverse and widely used models within the Machine Learning space. The end goal is to find the 'best' algorithm to do the job in quest.

**Task Performed**

Write up Python/R code snippets that will device 6 different classification algorithms on the same dataset. Namely, apply the following ML models:

* ﻿﻿﻿Logistic Regression (LR)
﻿﻿﻿* Naive Bayes (NB)
* ﻿﻿K-Nearest Neighbors (KNN)
﻿﻿﻿* Decision Tree (DT)
﻿﻿﻿* Random Forest (RF)
﻿﻿﻿* XGBoost Algorithm (XGB)


1) ﻿﻿﻿Prep the data in order to be ready to be fed to ML models.
2) ﻿﻿﻿Split the source dataset into training and test datasets at a 70%/30% ratio.
3) Run all algorithms with default values and report their model performance on the following metrics:
* ﻿﻿Accuracy
* ﻿﻿Precision
* Recall
* F1 Harmonic Mean
  
4) Generate a Classification Report (for each model) including Confusion Matrices, ROC Curves, and AUCs.
﻿﻿﻿Extra points, rerun some of the models by tuning some hyperparameters.


**Facebook_prophet_model_ElectricityComsumption.jpynb**

**Problem:** Implement a Time Series Forecasting model in Python, by using the FBProphet module.

The forecasting model should be able to predict New York City's Electricity Consumption (see below) by using Facebook's Prophet model. Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality.

You should test your forecasting model in three (3) distinct datasets. On Daily, Monthly Mean, and Yearly Mean electric consumption.

**Task Performed**

Write Python scripts in order to complete the following tasks :

﻿﻿﻿1) Since the time unit (day, month, year) varies from dataset to dataset, make your code agnostic of the input. In other words, have your code to determine the unit of the time series
2) Then, train your model (on the respective dataset) and predict the Electric Consumption (EC) values from the last date of the dataset into X units of time into the future.
* Should the unit of time be day, then predict the EC for 100/200/365 days into the future.
* Should the unit of time be month, then predict the EC for 1/6/9 months into the future.
* ﻿﻿﻿Should the unit of time be year, then predict the EC for 1/10/20 years into the future.

3) Tune your FBProphet model on the following parameters:

**﻿﻿﻿Forecasting growth:** Plausible values - logistic; linear; flat https://facebook.github.io/prophet/docs/saturating_forecasts.html
**﻿﻿﻿Seasonality:** Add manual seasonality by using the add_seasonality method.
Test it with various values for 'period? and 'Fourier order

4) For each model, print the predicted values in a tabular format and draw a line graph showing both the historical date and the future
5) Evaluate all models by providing their respective MAN (Mean Absolute Error) and  MAPE (Men Absolute Percentago Error), as well as R^2 (use Nklearn's respective

