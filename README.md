# CarDekho Price Prediction - Machine Learning in Python

## Problem Statement
The used car market in India is a dynamic and ever-changing landscape. Prices can fluctuate wildly based on various factors, including the make and model of the car, its mileage, condition, and prevailing market trends. This variability makes it challenging for sellers to determine the optimal price for their cars.

## Objective
To develop a machine learning model capable of predicting the price of a used car based on its features. The model will be trained on a dataset of used cars sold on [Cardekho.com](https://www.cardekho.com/) in India, enabling accurate price predictions for any used car with sufficient feature data.

## Approach
1. **Data Collection**  
   Utilize a dataset containing information on used cars sold in India, including features such as make, model, year, mileage, fuel type, transmission type, and condition.

2. **Feature Engineering**  
   Process and clean the dataset to handle missing values, normalize numerical data, and encode categorical features.

3. **Model Selection**  
   Use the Linear Regression algorithm to develop the prediction model.

4. **Model Training**  
   Train the Linear Regression model on the dataset, optimizing its parameters to improve accuracy.

5. **Evaluation**  
   Evaluate the model using the Root Mean Squared Error (RMSE) metric to ensure robust performance.

6. **Deployment**  
   Deploy the model for real-world usage, enabling sellers and buyers to get accurate price predictions for used cars.
   
## Files

- **CarDekho_Price_Prediction_ML.ipynb**: Jupyter notebook containing the full implementation of the project.
- **Cardekho.csv**: Raw dataset used for model training and evaluation.

## Benefits
- **For Sellers**: More accurate pricing will help sellers sell their cars faster and for a higher price.
- **For Buyers**: Buyers will be able to find competitively priced cars more easily.
- **For the Market**: The overall used car market in India will become more efficient, benefiting all stakeholders.

## Usage
1. Run the data preprocessing script:
   ```bash
   python scripts/preprocess_data.py
   ```
2. Train the model:
   ```bash
   python scripts/train_model.py
   ```
3. Predict car prices:
   ```bash
   python scripts/predict.py --features "make:model, mileage, condition, year"
   ```

## Results
The Linear Regression model achieved robust performance on test data, with an RMSE of **Y**, making it a reliable tool for price prediction in the Indian used car market.

