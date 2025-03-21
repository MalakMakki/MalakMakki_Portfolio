# Automated Data Pipeline for Weather Forecasting (Azure)
## Objective: Familiarize with Azure and cloud computing, including an ML model.
## Description:
The work was divided into many sprints aiming to achieve a full Machine Learning model that forecasts the weather in Beirut city.
The first sprint was simply a test of the API based on a simple HTML page and JavaScript and Python code to complete the fetching of weather data based on a user-input city. Then, as a first step, this project was deployed using Microsoft Azure.
The second sprint focused on the concept of fetching big data using the same API but with an interval time input that guarantees the fetching of a large amount of weather data to be used later as a base for our future forecasting model.
The third sprint was dedicated to implementing Sprint 2 via a pipeline in a Data Factory on Azure to render this data in real-time through a scheduler that continuously updates the data.
In the final sprint, after obtaining our big data from previous sprints, we built a Machine Learning model based on Random Forest and XGBoost, then compared their accuracy based on the R² metric, which was 0.87 and 0.86, respectively. We then processed a time series analysis as a good introduction for further improvements in modeling in the future.
## Results:
We obtained stationary data that can serve as a solid base for any time series forecasting. The predictive model, based on Random Forest and XGBoost, was evaluated, and their accuracy was compared using the R² metric, which resulted in 0.87 and 0.86, respectively.
Here are the reports for the first sprints.: https://drive.google.com/drive/folders/1i_ppbGKuVMVaaq7bLVoFL34AuC3DUan_?usp=sharing

