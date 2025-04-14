# Exploratory Data Analysis (EDA) - Task 5

## Objective

Perform EDA on the given dataset to:

- Understand the dataset’s structure and quality.
- Identify relationships between variables.
- Visualize important patterns using various plots and charts.

## Dataset

The dataset used for this EDA task is:
- **Sample Superstore Data** (commonly used in sales and profit analysis)

It contains the following key columns:
- `Ship Mode`
- `Segment`
- `Country`
- `City`
- `State`
- `Region`
- `Category`
- `Sub-Category`
- `Sales`
- `Quantity`
- `Discount`
- `Profit`

## Analysis Performed

- **Data Cleaning**: Checked for null values, duplicates, and corrected data types.
- **Descriptive Statistics**: Summary statistics to understand distributions.
- **Univariate Analysis**: Analyzed individual features using histograms, bar plots, etc.
- **Bivariate/Multivariate Analysis**: Explored relationships using scatter plots, pair plots, and heatmaps.
- **Correlation Matrix**: Visualized correlation among numerical variables.
- **Sales & Profit Analysis**: By Region, Category, Sub-Category, and State.

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights

- Some states (e.g., Texas, Illinois) generate high sales but low profit due to higher discounts.
- Office Supplies is the highest selling category.
- Certain Sub-Categories such as Binders and Chairs contribute significantly to losses in some regions.
- Western and Eastern regions contribute more to profits than Central and Southern.

