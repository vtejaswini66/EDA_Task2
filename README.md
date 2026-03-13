# EDA_Task2
# Sales Data Analysis – Exploratory Data Analysis (EDA)

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on a sales dataset to identify patterns, relationships, and key business insights.
Using Python and data visualization libraries, we analyze how factors like sales, quantity, and marketing spend influence revenue.



##  Objective

* Load and explore the dataset
* Perform data analysis using Python
* Visualize relationships between variables
* Identify key insights from the sales data



##  Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab



##  Dataset Information

The dataset contains sales transaction data with the following columns:

| Column           | Description             |
| ---------------- | ----------------------- |
| order_id         | Unique order identifier |
| date             | Transaction date        |
| customer_id      | Customer identifier     |
| product_category | Category of product     |
| sales            | Sales value             |
| quantity         | Number of items sold    |
| marketing_spend  | Marketing expenditure   |
| revenue          | Total revenue generated |



##  Analysis Performed

The following analyses were performed:

1. Data loading and inspection
2. Descriptive statistics of numerical features
3. Product category distribution analysis
4. Correlation analysis using heatmap
5. Visualization of relationships between variables



##  Visualizations

The project includes several visualizations such as:

* Product Category Distribution
* Sales Distribution Histogram
* Correlation Heatmap
* Marketing Spend vs Revenue Scatter Plot



##  Key Insights

* Sales and revenue show a strong positive correlation.
* Quantity sold contributes significantly to revenue.
* Marketing spend shows very weak correlation with revenue in this dataset.



##  Repository Structure

sales-data-analysis
│
├── dataset
│   └── cleaned_dataset.csv
│
├── notebook
│   └── sales_analysis.ipynb
│
├── images
│   └── correlation_heatmap.png
│
└── README.md



##  How to Run the Project

1. Clone the repository
2. Open the notebook in Jupyter or Google Colab
3. Install required libraries

Example:

pip install pandas matplotlib seaborn

4. Run the notebook cells step by step.



##  Future Improvements

* Add more datasets for deeper analysis
* Build predictive models using machine learning
* Create an interactive dashboard for insights





