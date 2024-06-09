# Sales Forecasting

This project focuses on forecasting weekly sales for a retail store using the ARIMA model. The dataset includes information on weekly sales for different stores and departments, along with whether the week was a holiday.

## Project Overview

Sales forecasting is an essential task for inventory management, financial planning, and marketing strategy. This project aims to predict future sales based on historical sales data using the ARIMA model, a popular time series forecasting method.

## Dataset

The dataset contains the following columns:

- `Store`: The store number
- `Dept`: The department number
- `Date`: The week of the data point
- `Weekly_Sales`: The weekly sales amount
- `IsHoliday`: Whether the week is a special holiday week

## Project Steps

1. **Data Preprocessing**: Load and clean the dataset, handle missing values, and sort the data by date.
2. **Feature Engineering**: Aggregate weekly sales data by date.
3. **Train-Test Split**: Split the data into training and testing sets.
4. **Model Training**: Fit an ARIMA model on the training data.
5. **Forecasting**: Make sales forecasts on the test data and evaluate the model.
6. **Future Forecasting**: Fit the model on the entire dataset and forecast future sales.

## Installation

To run this project, you need to have the following libraries installed:

- pandas
- matplotlib
- statsmodels
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas matplotlib statsmodels scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Lourdhu02/Sales-Forecasting.git
```

2. Navigate to the project directory:

```bash
cd walmart_sales_forecasting
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the `walmart_sales_forecasting.ipynb` notebook to see the results.

## Results

The ARIMA model successfully forecasted the weekly sales. The visualizations and evaluation metrics provided insights into the model's performance.

## Conclusion

This project demonstrates the effectiveness of the ARIMA model in forecasting sales. Accurate sales forecasts can help businesses in various strategic areas such as inventory management and financial planning.
