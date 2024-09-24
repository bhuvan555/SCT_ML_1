# House Price Prediction using Linear Regression

## Project Overview

This project is designed to predict house prices using a Linear Regression model, focusing on specific features like the size of the living area, number of bedrooms, full bathrooms, and half bathrooms. The project is built using Python and leverages popular libraries like `pandas`, `numpy`, `scikit-learn`, and `matplotlib` for data manipulation, machine learning, and visualization.

## Dataset

The project uses the following datasets:
- **train.csv**: Training data containing features and house prices.
- **test.csv**: Test data for which predictions need to be generated.
- **sample_submission.csv**: Sample format for submitting the predicted house prices.

### Features Used for Prediction:
- **GrLivArea**: Above-ground living area (square feet).
- **BedroomAbvGr**: Number of bedrooms above ground.
- **FullBath**: Number of full bathrooms.
- **HalfBath**: Number of half bathrooms.

## Workflow

1. **Data Preprocessing**:
   - Handling missing values by filling them with the mean of respective columns.
   - Splitting the data into training (80%) and validation (20%) sets.

2. **Model Training**:
   - A Linear Regression model is trained using the selected features from the training data.

3. **Model Evaluation**:
   - Model performance is evaluated using the Root Mean Squared Error (RMSE) on the validation set.
   - Visualizations like actual vs predicted prices and residuals analysis are used to assess model accuracy.

4. **Test Set Prediction**:
   - Predictions are generated on the test dataset and saved in a file named `submission.csv`.

## Visualizations

- **Actual vs Predicted Sale Price**: A scatter plot to compare actual sale prices with predicted prices.
- **Residuals Plot**: Visualizes the differences (errors) between predicted and actual sale prices.
- **Feature vs Sale Price Plots**: Shows relationships between individual features and the target variable (SalePrice).
- **Correlation Matrix Heatmap**: A heatmap that shows correlations between selected features and sale prices.

## Project Dependencies
1.pandas
2.numpy
3.scikit-learn
4.matplotlib

## Results
The Linear Regression model’s performance is measured using RMSE (Root Mean Squared Error), and additional visualizations provide insights into the model's prediction accuracy and behavior.

