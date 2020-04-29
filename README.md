# Corona_week2_analysis

About challenge-
Kaggle is launching a companion COVID-19 forecasting challenges to help answer a subset of the NASEM/WHO questions. While the challenge involves forecasting confirmed cases and fatalities between April 1 and April 30 by region, the primary goal isn't only to produce accurate forecasts. It’s also to identify factors that appear to impact the transmission rate of COVID-19.
Project description
Imported necessary libraries like pandas,numpy,seaborn,Loaded Dataset,Used info() to get an idea on how many non-null values we have for each feature replacing null values with 'N/A' So that they are not excluded in groupby clause
Used barplot from seaborn library to visualize top 10 countries with confirmed cases and fatalities .Used Time series anlaysis to plot cumulative confirmed cases over the week ,used time series decomposition to check on trend ,seasonaltiy and noise.
Also used Random Forest Regressor to predict confirmed cases and fatalities .
