# ontario_ltc_covid19
Ontario LTC COVID19 Risk Machine Learning Regression

For the past two years, COVID-19 pandemic has presented unprecedented challenges to Canada’s health system. Long-Term Care sector especially was impacted severely due to its vulnerable senior population with numerous underlying health conditions as well as the congregate living environment.

According to a report by Public Health Ontario (2021), there were 14,960 confirmed cases of COVID-19 in Ontario among Long-term care home residents from January 2020 to February 2021. Long-term care home residents accounted for 15% and 3.4% of all reported cases in wave 1 and 2 respectively. There were 390 and 899 Long-term care home outbreaks in wave 1 and wave 2 respectively.

In this paper the author uses machine learning techniques to study COVID-19 related mortality rate of long-term care home residents. 

In this study the author used COVID-19 related public data from the Ministry of Ontario and Public Health Ontario. The dataset contains information including resident and healthcare worker COVID-19 positive cases and deaths in long-term care homes, long-term care home COVID-19 outbreaks, resident and healthcare worker immunization in long-term care homes, COVID-19 cases by public health unit, long-term care home size in terms of bed count, and so on.

This study explores the available data and identifies factors associated with mortality of residents and staffs diagnosed with COVID-19 in long-term care homes and designs a machine learning model utilizing models including multiple linear regression, Lasso regression, Ridge regression, Random Forest, and Support Vector regression (SVR) in order to predict the mortality rate of COVID-19 related resident deaths of long-term care homes. 

Model performance was evaluated with R squared, Mean Absolute Error (MAE), and Root Mean Square Error (RMSE). Runtime was also tracked to compare the efficiency of each model.

The analysis and models were run using Python. Scikit-learn machine learning models and metrics APIs were used to build and evaluate the models. Packages for data manipulation and analysis include pandas, numpy, math, statistics, time, statsmodels and so on. Seaborn, scipy, and matplotlib.pyplot packages were used for data visualization.

The model predicts Long-term care home residents’ COVID-19 mortality rate based on multiple factors from both Long-term care homes and communities which was represented by public health units.

# Project Workflow
![image](https://user-images.githubusercontent.com/103083590/164200963-d4b80dce-c8dc-4169-a743-2739175fb220.png)

