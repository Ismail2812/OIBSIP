# Level 1 — Task 1: EDA on Retail Sales Data

## Internship

Oasis Infobyte Internship — OIBSIP

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of retail sales data.

The objective is to explore sales patterns, identify important products and categories, analyze relationships between numerical variables, and extract meaningful business insights from the dataset.

## Objectives

The main objectives of this project were:

- Load and inspect the retail sales dataset
- Perform exploratory data analysis
- Analyze top-selling products
- Analyze revenue by category
- Study relationships between numerical variables
- Calculate correlations with Sales
- Calculate correlations with Profit
- Create visualizations
- Extract meaningful business insights

## Exploratory Data Analysis

The analysis included:

- Dataset inspection
- Data type analysis
- Descriptive statistics
- Product quantity analysis
- Category revenue analysis
- Correlation analysis
- Visualization of important patterns

## Top Products

The top products by quantity included:

1. Staples — 215
2. Staple envelope — 170
3. Easy-staple paper — 150
4. Staples in misc. colors — 86
5. KI Adjustable-Height Table — 74
6. Storex Dura Pro Binders — 71
7. Avery Non-Stick Binders — 71
8. GBC Premium Transparent Covers with Diagonal Lined Pattern — 67
9. Situations Contoured Folding Chairs, 4/Set — 64
10. Staple-based wall hangings — 62

## Category Revenue

The revenue analysis showed:

| Category | Sales |
|---|---:|
| Technology | 836,154.03 |
| Furniture | 741,999.80 |
| Office Supplies | 719,047.03 |

Technology generated the highest sales among the three categories.

## Correlation with Sales

The correlation analysis showed:

| Variable | Correlation with Sales |
|---|---:|
| Profit | 0.479064 |
| Quantity | 0.200795 |
| Row ID | -0.001359 |
| Postal Code | -0.023854 |
| Discount | -0.028190 |

Profit had the strongest positive correlation with Sales among the analyzed variables.

## Correlation with Profit

The correlation analysis showed:

| Variable | Correlation with Profit |
|---|---:|
| Sales | 0.479064 |
| Quantity | 0.066253 |
| Row ID | 0.012497 |
| Postal Code | -0.029961 |
| Discount | -0.219487 |

Sales had the strongest positive correlation with Profit.

Discount showed a negative correlation with Profit in the analyzed dataset.

## Key Insights

### 1. Technology Generated the Highest Sales

Technology had the highest category sales at approximately 836,154.03.

### 2. Staples Was the Top Product

Staples had the highest quantity among the analyzed products, with a quantity of 215.

### 3. Sales and Profit Have a Positive Relationship

Sales had a correlation of approximately 0.479 with Profit.

### 4. Quantity Has a Weaker Relationship with Sales

Quantity had a correlation of approximately 0.201 with Sales.

### 5. Discount Has a Negative Relationship with Profit

Discount had a correlation of approximately -0.219 with Profit.

## Visualizations

The project includes visualizations for:

- Top Products
- Category Revenue
- Correlation Analysis
- Sales-related analysis
- Profit-related analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files

- `Task1_EDA_Retail_Sales.ipynb`
- `README.md`

## Conclusion

This project successfully performed Exploratory Data Analysis on retail sales data.

The analysis identified the top products, compared revenue across categories, and examined relationships between sales, profit, quantity, discount, and other numerical variables.

Technology generated the highest category sales, while Staples was the highest-quantity product among the analyzed products.

The correlation analysis showed a positive relationship between Sales and Profit, while Discount showed a negative relationship with Profit.

Overall, the project demonstrates practical skills in data exploration, statistical analysis, visualization, correlation analysis, and extracting meaningful insights from retail data.
