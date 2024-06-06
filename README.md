# Sales Forecasting with LSTM

This project aims to forecast weekly sales data for different product categories in various grocery stores of Corporación Favorita, a large Ecuadorian-based grocery retailer using Long Short-Term Memory (LSTM) neural networks. The forecasts incorporate additional variables such as promotion status, store number, and product category.

## Project Structure

- **store-sales-time-series-forecasting.zip**: Directory containing the input data files.
- **.ipynb files**: Jupyter notebooks used for data analysis and model training.
- **README.md**: This readme file.
- **predictions.csv**: Final output after model training

## Requirements

To run this project, you need to have the following libraries installed:

- pandas 
- numpy
- tensorflow
- dask

## Steps

1. **Data Cleaning**: Process of cleaning and preprocessing raw data.
   
2. **EDA (Exploratory Data Analysis)**: Analyzing data to summarize its main characteristics.

3. **Plotting ACF and PACF graphs**: Checking for seasonality and autocorrelation in the data.

4. **Differencing**: Transforming a time series dataset to make it stationary.

5. **Stationarity Testing**: Testing the stationarity of the transformed dataset.

6. **Further Data Cleaning**: Additional preprocessing steps as necessary.

7. **Model Training using LSTM**: Training the Long Short-Term Memory (LSTM) neural network model.

8. **Model Testing and Evaluation**: Evaluating the trained model's performance.

9. **Finish**: Project Conclusion.

## Performance Metrics

After training the LSTM model, the following performance metrics were obtained:

- Mean Absolute Error (MAE): 0.08
- Mean Squared Error (MSE): 0.09
- Root Mean Squared Error (RMSE): 0.29
- R-squared (R2): 0.96

**Note**: The final output sales have not been inversely transformed after scaling.


