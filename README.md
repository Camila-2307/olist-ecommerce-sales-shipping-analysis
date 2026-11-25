# Olist Brazilian E-Commerce: Sales & Shipping Cost Analysis

## Overview
An exploratory data analysis and predictive modeling project using the Olist Brazilian E-Commerce Public Dataset. The project investigates product sales, shipping charges, and geographic patterns across Brazil to identify business insights and opportunities for improving sales and logistics strategies.

## Business Question
How do product sales and shipping costs vary across different geographic regions in Brazil, and what patterns can businesses identify to improve sales and logistics strategies?

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. **Data Integration:** Combined eight interconnected datasets into an order-item-level analytical dataset.
2. **Data Cleaning:** Addressed missing values, standardized categories, and reviewed potential outliers.
3. **Feature Engineering:** Created variables for purchase dates, delivery duration, delivery delays, total item cost, and freight percentage.
4. **Exploratory Data Analysis:** Examined descriptive statistics, correlations, geographic freight patterns, and product category sales.
5. **Predictive Modeling:** Compared Linear Regression and Decision Tree models to predict item-level freight charges.
6. **Business Recommendations:** Identified opportunities for regional logistics review, improved freight estimation, and data-driven product planning.

## Key Findings
- The North region had the highest average freight charge per item at R$36.84, compared with R$17.37 in the Southeast.
- Product weight had the highest relative feature importance in the Decision Tree model at 69.5%.
- Health & Beauty generated the highest category sales value at approximately R$1.26 million.

## Model Performance
The Decision Tree performed better than Linear Regression and the median baseline.

| Metric | Decision Tree |
|---|---:|
| MAE | R$5.844 |
| RMSE | R$11.234 |
| R² | 0.523 |

## Dataset
Olist Brazilian E-Commerce Public Dataset, available through Kaggle.

The original dataset is not included in this repository. Refer to the dataset source for access and licensing information.

## Limitations
The analysis uses historical marketplace transactions and recorded freight charges. Freight charges do not represent Olist's internal shipping expenses. The model also uses a limited set of predictors and does not account for all logistics factors, such as route distance and carrier details.

## Author
Camila Campbell  
Business Analytics & Information Systems Student | University of South Florida
