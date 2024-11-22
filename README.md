# **Sales Data Analysis Project**

## **Overview**

This project is focused on analyzing sales data to uncover patterns, identify best-selling products, and derive key revenue indicators. The goal is to leverage these insights to support data-driven decision-making, ultimately improving sales strategies and business outcomes.

## **Objectives**

- **Total Sales Calculation**: Compute the total sales across all products to assess overall revenue.
- **Sales Trend Analysis**: Examine how sales have evolved over time, identifying peaks, troughs, and trends that can inform strategic planning.
- **Best-Selling Products**: Determine which products are driving the most revenue, helping prioritize inventory and marketing efforts.
- **Revenue Indicators**: Calculate additional metrics such as average sales per transaction and identify high-value customers to optimize customer relationship management.
- **Data Visualization**: Create clear and insightful visualizations that communicate findings effectively to stakeholders.

## **Dataset**

The dataset used in this project consists of sales records that include details such as product names, quantities sold, profit, sales dates, shipping date, customer IDs, and categories. This data serves as the foundation for all analyses and visualizations.

## **Key Analyses**

1. **Total Sales Calculation**: 
   - We calculated the total sales by multiplying the quantity of items sold by their respective unit prices. This metric serves as the basis for evaluating overall revenue.

2. **Sales Trend Over Time**:
   - By analyzing sales data over time, we identified trends and patterns. Understanding these trends helps in making informed decisions about seasonal promotions, inventory management, and more.

3. **Best-Selling Products**:
   - Identifying the top-selling products allowed us to recognize the key revenue drivers. These insights are crucial for inventory planning and marketing focus.

4. **Revenue by Category**:
   - Grouping sales by product category provided insights into which categories contribute most to the revenue. This can guide decisions on product expansion and diversification.

5. **High-Value Customers**:
   - We identified customers who contribute the most to revenue, helping tailor customer relationship management strategies.

## **Visualizations**

To effectively communicate the findings, various visualizations were created, including:

- **Sales Trend Over Time**: A line chart showing how sales fluctuate over different periods.
- **Best-Selling Products**: A bar chart highlighting the top 10 products by revenue.
- **Revenue by Category**: A bar chart depicting total sales by product category.
- **High-Value Customers**: A ranking of customers based on their total purchases.

## **Summary of Findings**

- The sales data revealed significant insights into product performance, customer behavior, and sales trends.
- **Top Products**: Certain products consistently outperform others, making them focal points for marketing and inventory decisions.
- **Sales Trends**: Sales exhibit distinct trends that could be leveraged for seasonal promotions and demand forecasting.
- **Customer Insights**: High-value customers were identified, allowing for targeted retention strategies.

## **Recommendations**

Based on the analysis, the following recommendations are proposed:

- **Marketing Focus**: Allocate more resources to promote best-selling products and high-revenue categories.
- **Customer Retention**: Implement loyalty programs for high-value customers to enhance repeat purchases.
- **Inventory Optimization**: Adjust inventory levels based on sales trends and product performance to reduce overstock and stockouts.
- **Sales Promotions**: Introduce strategic promotions during low-sales periods to boost revenue.

## **Conclusion**

This project highlights the power of data-driven insights in shaping effective business strategies. By thoroughly analyzing sales data, businesses can make informed decisions that lead to increased revenue, optimized operations, and improved customer satisfaction.

---

# Titanic Survival Prediction Analysis

## Overview

This project aims to predict survival outcomes for passengers aboard the Titanic using various machine learning techniques. The dataset used for this analysis is the well-known Titanic dataset, which includes features such as passenger age, sex, ticket class, and more.

## Project Structure

- `data/`: Contains the datasets used in this project.
- `notebooks/`: Jupyter notebooks with exploratory data analysis (EDA), model training, and evaluation.
- `scripts/`: Python scripts for data preprocessing, feature engineering, and model building.
- `models/`: Saved models and configurations.
- `requirements.txt`: List of Python dependencies required to run the project.
- `README.md`: This file.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed. This project uses several libraries and tools that are specified in `requirements.txt`. You can install them using pip:

```bash
pip install -r requirements.txt
```

### Dataset

The dataset used in this project is the Titanic dataset from Kaggle. It includes the following files:
- `train.csv`: Training data.
- `test.csv`: Test data for predictions.
- `gender_submission.csv`: Example of the format for submitting predictions.

You can download the dataset from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data) and place them in the `data/` directory.

### Running the Analysis

1. **Exploratory Data Analysis (EDA):**
   - Open `notebooks/eda_notebook.ipynb` to explore and visualize the dataset.

2. **Data Preprocessing and Feature Engineering:**
   - Run `scripts/preprocess.py` to clean and preprocess the data.

3. **Model Training:**
   - Execute `scripts/train_model.py` to train different machine learning models and evaluate their performance.

4. **Making Predictions:**
   - Use `scripts/predict.py` to generate predictions on the test set.

5. **Submission:**
   - Format your predictions according to `gender_submission.csv` and submit them to Kaggle.

## Results

The results of different models, including accuracy scores and feature importances, are documented in `notebooks/model_comparison.ipynb`.

## Contributing

Feel free to fork the repository and submit pull requests. If you have suggestions or improvements, open an issue to discuss potential changes.

## Acknowledgements

- The Titanic dataset is provided by Kaggle.
- Libraries and tools used include Pandas, NumPy, Scikit-Learn, Matplotlib, and Seaborn.

