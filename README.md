### Demand Forecasting to Optimize Supply Chain Management

**Submitted by Team 2(Carlos Iturralde, Vikash Sinha, Olaoluwa Olasanoye)**

#### Executive summary
This project aims to develop a predictive model for afor Demand Forecasting to Optimize Supply Chain Management. By leveraging multiple regression models, including Linear Regression, Decision Trees, and Random Forest, we aim to predict future sales and demand for WalMart Store. The project may help to provide insights into the Consumer Demand  and identifies patterns in Sales trends, giving Store  the ability to optimize their supply-chain.

#### Rationale
Sales fluctuate due to several factors such as demand, economic factor, and seasonality. Being able to predict these fluctuations can help store make informed decisions related to Supply-chain.

#### Research Question
Can we build a model to accurately predict Weekly Sales-demand for future , considering time-series and other factor?

#### Data Sources
The data used in this project is sourced from Kaggle, 

#### Methodology
To answer the research question, we employ multiple regression models including:

Linear Regression
Decision Trees
Random Forests
ARMA
SARMA

The project involved the following steps:
Data Preprocessing: Cleaning and encoding non-numeric variables like Wee day. We used cleaned data from source.
Feature Selection: Identifying and analyzing the importance of different features like Temperature, CPI.
Model Training: Each model was trained using the preprocessed dataset, and hyperparameters were tuned using grid search.
Model Evaluation: Cross-validation was used to assess each model’s performance using metrics such as RMSE (Root Mean Squared Error), MSE (Mean Squared Error), and R² (R-squared).

Additionally, time series forecasting using ARIMA (AutoRegressive Integrated Moving Average) to conduct for predicting future Demand based on historical trends.

#### Results 
The Random Forest model outperformed the other models in terms of predictive accuracy. The following insights were gathered:


