## [0.0.8] - 2023-09-26
### Added
- **Vector Mean Calculation**: Added a new method to calculate the mean (average) of the vector's values. You can now use the `mean` method to obtain the mean value of a Vector.

- **Vector Variance Calculation**: Implemented a method to compute the variance of the vector's values. You can now use the `variance` method to calculate the variance of a Vector.

- **Vector Standard Deviation Calculation**: Introduced a method for calculating the standard deviation of the vector's values. You can now use the `std_deviation` method to find the standard deviation of a Vector.

- **Linear Regression**: Added support for linear regression with the `LinearRegression` class. You can use the `fit` method to train a linear regression model and the `predict` method to make predictions based on the trained model.

- **Time Series Analysis**: Introduced a new class, `TimeSeriesAnalysis`, for analyzing time series data.
  - `moving_average(self, window_size: int) -> Vector`: Added a method for calculating the moving average of a time series with a specified window size.
  - `exponential_smoothing(self, alpha: float) -> Vector`: Added a method for applying exponential smoothing to a time series with a given smoothing parameter.

- **Added the `irr` method** to the `FinancialAnalysis` class for calculating the Internal Rate of Return (IRR) of cash flows.
- **Added the `npv` method** to the `FinancialAnalysis` class for calculating the Net Present Value (NPV) of cash flows.

These new methods allow users to perform advanced financial analysis, making it easier to assess the profitability and value of investments and projects.
These new features provide additional statistical analysis capabilities for Vector objects, as well as the ability to perform linear regression on your data using the `LinearRegression` class.
These new features enable users to perform time series analysis, including moving average and exponential smoothing, using the `TimeSeriesAnalysis` class. This enhances the capabilities of the library for working with time series data.
