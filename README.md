# Stock Market Forecasting using Prophet

This project is an example of using the Prophet library to forecast stock market prices. The goal of this project is to demonstrate how to use the Prophet library to create a time series model that can accurately predict future stock prices.

---

## Data
The data used in this project is the historical data for the S&P 500 index obtained from yfinance library. The data is collected from the start of 2015 to the end of 2018.

---

## Dependencies

The following dependencies are required to run this project:

pandas
numpy
scikit-learn
fbprophet
yfinance

You can install these dependencies by running the following command:

!pip install pandas numpy scikit-learn fbprophet yfinance

---

## Usage

To use the code in this project, you can clone the repository and then run the jupyter notebook file.

The notebook is divided into several sections:

**Data Preparation:** This section shows how to use the yfinance library to download the historical data for the S&P 500 index and how to prepare the data for use in the prophet model.

**Model Training:** This section shows how to create and train the prophet model on the historical data.

**Predictions:** This section shows how to use the trained model to make predictions for future stock prices.

**Evaluation:** This section shows how to evaluate the model's performance using metrics such as mean absolute error (MAE) and root mean squared error (RMSE).

## Conclusion

The Prophet library is an easy-to-use tool that can be used to forecast stock prices. By following the steps outlined in this project, you can create a time series model that can accurately predict future stock prices. Additionally, the ability to evaluate the model's performance using metrics such as MAE and RMSE can help to ensure that the model is robust and accurate.