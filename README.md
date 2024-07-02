### README for Sweet Lift Taxi Order Prediction Project

## Project Description

Sweet Lift, a taxi company, has collected historical data on taxi orders at the airport. To attract more drivers during peak hours, we need to predict the number of taxi orders for the next hour. The goal is to build a model capable of making such predictions.

The RMSE on the test set should not exceed 48.

## Project Instructions

### 1. Data Preparation
- Download the data available in the file `/datasets/taxi.csv`.
- Resample the data to an hourly frequency.
- Load and observe the dataset.
- Ensure data cleanliness and address any missing values or outliers.

### 2. Data Analysis
- Analyze the data to understand patterns and trends.
- Identify any seasonality, trends, or anomalies in the data.
- Visualize the data to gain insights.

### 3. Model Training
- Train different models with various hyperparameters.
- Ensure the test sample represents 10% of the initial dataset.
- Use cross-validation to evaluate model performance.
- Select and tune models, including but not limited to time series models and machine learning models.

### 4. Model Evaluation
- Test the models using the test sample.
- Calculate the RMSE to ensure it does not exceed 48.
- Compare the performance of different models.
- Analyze prediction quality and speed.

### 5. Conclusion
- Summarize findings and results.
- Make recommendations based on model performance.
- Suggest potential improvements or next steps.

## Data Description

The dataset includes the following key feature:
- **num_orders**: The number of taxi orders in a given time period.

The data is indexed by date and time.

## Steps Taken

### Data Preparation:
1. Loaded and observed the data from `/datasets/taxi.csv`.
2. Resampled the data to an hourly frequency.
3. Ensured data cleanliness and addressed any missing values or outliers.

### Data Analysis:
1. Analyzed the dataset to identify patterns and trends.
2. Visualized the data to gain insights into seasonality, trends, and anomalies.

### Model Development:
1. Trained different models with various hyperparameters.
2. Used cross-validation to evaluate model performance.
3. Selected the best-performing models and tuned their hyperparameters.

### Model Evaluation:
1. Tested the models using the test sample.
2. Calculated the RMSE to ensure it did not exceed 48.
3. Compared the performance of different models.
4. Analyzed the prediction quality and speed of each model.

### Conclusion:
1. Summarized the findings and results.
2. Made recommendations based on model performance.
3. Suggested potential improvements or next steps for further optimization.

## Conclusion

This project involves preparing and analyzing historical taxi order data to develop predictive models for forecasting taxi orders for the next hour. The aim is to provide Sweet Lift with a reliable model that can help attract more drivers during peak hours by accurately predicting demand. The results include evaluating different models, ensuring the RMSE on the test set does not exceed 48, and making recommendations based on model performance.
