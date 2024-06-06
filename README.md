# Sales Forecasting with LSTM

This project aims to forecast weekly sales data for different product categories in various branches of Corporación Favorita, a large Ecuadorian-based grocery retailer using Long Short-Term Memory (LSTM) neural networks. The forecasts incorporates additional variables such as promotion (discount), store number, and product category.

## Project Structure

- **store-sales-time-series-forecasting.zip**: Directory containing the input data files.
- **.ipynb files**: Jupyter notebooks used for data analysis and model training.
- **README.md**: This readme file.
- **predictions.csv**: Final output after model training.

## Notebooks

- **LSTM-Sales-Forecasting.ipynb**: Notebook containing all ML proccesses including data cleaning, analysis, model training, and prediction.
- **test_data_cleaning.ipynb**: Notebook for cleaning and preprocessing of test data.
- **inverse_transformation_sales.ipynb**: Notebook for combining final predicition with test data after inverse transformation.

## Requirements

To run this project, you need to have the following libraries installed:

- pandas 
- numpy
- tensorflow
- dask
- scikit-learn

## Steps

1. **Data Cleaning**: Process of cleaning and preprocessing raw data.
   
2. **EDA (Exploratory Data Analysis)**: Analyzing data to summarize its main characteristics.

3. **Plotting ACF and PACF graphs**: Checking for seasonality and autocorrelation in the data.

4. **Differencing**: Transforming a time series dataset to make it stationary.

5. **Stationarity Testing**: Testing the stationarity of the transformed dataset.

6. **Further Data Cleaning**: Additional preprocessing steps as necessary.

7. **Model Training using LSTM**: Training the Long Short-Term Memory (LSTM) neural network model.

8. **Model Testing and Evaluation**: Evaluating the trained model's performance.

9. **Sales Predicted Data Inverse Transformation**: Inversing scalar transformation on predicted output for cleaner data representation.

## Performance Metrics

After training the LSTM model, the following performance metrics were obtained:

- Mean Absolute Error (MAE): 0.08
- Mean Squared Error (MSE): 0.09
- Root Mean Squared Error (RMSE): 0.29
- R-squared (R2): 0.96


