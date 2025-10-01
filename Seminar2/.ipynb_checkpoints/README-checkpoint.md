# House Price Prediction (Linear Regression)
This project is dedicated to predicting house prices based on the dataset **reg_house_data.csv**.  
The goal is to build a basic linear regression model, go through the complete data processing pipeline, and evaluate prediction quality.

# Project Steps
1. Data loading (`reg_house_data.csv`)  
   - initial inspection, statistics, missing values.  
2. Feature selection  
   - numerical features.  
   - categorical features.  
3. Data preprocessing  
   - handling missing values;  
   - one-hot encoding for categorical features;  
   - normalization of numerical data (MinMaxScaler).  
4. Model  
   - Linear Regression;  
   - Ridge Regression.  
5. Training and evaluation  
   - train / test / validation split;  
   - model training;  
   - metrics: MSE, RMSE;  
   - scatterplot for over- and under-prediction analysis.  

# Libraries Used
- pandas  
- numpy  
- scikit-learn  
- matplotlib  

# Results
- Linear Regression gave a baseline level of error (MSE / RMSE).  
- Ridge Regression did not improve the result (regularization did not help).  
- The model performs adequately on the test data without severe overfitting.  
