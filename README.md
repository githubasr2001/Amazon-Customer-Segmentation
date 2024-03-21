# Amazon-Customer-Segmentation


This Jupyter Notebook provides an in-depth analysis of customer data focusing on sales, profit, geographical distribution, and customer segmentation. The data comes from an Amazon sales dataset and explores various aspects of sales and customer behavior over time.

## Getting Started

### Prerequisites

To run this notebook, you need the following packages installed:

- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn
```

### Dataset

The dataset, named `Amazon 2_Raw.xlsx`, contains sales data with the following columns:

- Order ID
- Order Date
- Ship Date
- EmailID
- Geography
- Category
- Product Name
- Sales
- Quantity
- Profit

## Analysis Overview

The notebook is structured as follows:

1. **Initial Data Exploration**: Loading the data, checking data types, and ensuring there are no null values.
2. **Sales Analysis Over Time**: Analysis of total sales over time, visualized monthly.
3. **Profit Analysis Over Time**: Similar to sales analysis but focusing on profit.
4. **Product Category Performance**: Evaluation of sales and profit performance across different product categories.
5. **Geographic Analysis**: Detailed analysis of sales and profit, both state-wise and city-wise.
6. **Time to Ship Analysis**: Calculation of shipping time and its average across categories.
7. **Forecasting**: Using ARIMA for sales forecasting over the next 5 years.
8. **Customer Segmentation**: Implementation of RFM (Recency, Frequency, Monetary) analysis for customer segmentation, followed by K-Means clustering to identify customer groups.

## Highlights

- The analysis provides insights into sales trends, identifying peak periods and product categories driving the most revenue.
- Geographic analysis helps pinpoint regions contributing most to sales and profit.
- The time-to-ship analysis can help in optimizing logistics and improving customer satisfaction.
- Future sales are forecasted, aiding in strategic planning.
- Customer segmentation identifies key customer groups, allowing for targeted marketing strategies.

## How to Use

1. Clone the repository or download the notebook.
2. Ensure you have the required data file `Amazon 2_Raw.xlsx` in your working directory.
3. Run the notebook cells sequentially to reproduce the analysis.

