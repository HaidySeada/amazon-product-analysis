# Amazon Sales Data Analysis

## Project Overview

This project explores an Amazon product dataset using Python to investigate product pricing, discount percentages, customer ratings, review counts, and product categories.

The goal is to demonstrate data cleaning, exploratory data analysis (EDA), statistical summaries, data visualization, and basic review sentiment analysis to support a better understanding of product performance and customer feedback.

## Objectives

- Understand the dataset structure and assess data quality.
- Clean price, discount, rating, and review-count columns.
- Identify and handle missing values.
- Check for duplicate records.
- Explore product prices, ratings, and discount patterns.
- Compare average ratings and discounts across product categories.
- Identify frequently occurring product-name keywords.
- Explore customer review sentiment using TextBlob.
- Examine the correlation between discounted prices and product ratings.

## Tools & Technologies

- Python
- Pandas — data cleaning, transformation, and analysis
- NumPy — numerical operations
- Matplotlib — data visualization
- Seaborn — statistical visualization
- SciPy — scientific computing
- WordCloud — product keyword visualization
- TextBlob — basic sentiment analysis
- Jupyter Notebook — interactive analysis

## Dataset Overview

The dataset contains **1,465 rows and 16 columns**.

It includes information about:

- Product identifiers and names
- Product categories
- Actual and discounted prices
- Discount percentages
- Product ratings and rating counts
- Product descriptions
- Customer identifiers and names
- Review titles and review content
- Product image and product links

The dataset uses Indian rupees (₹) for product prices.

## Project Workflow

1. **Data Loading:** Load the CSV file into Pandas.
2. **Data Inspection:** Examine dimensions, column names, data types, and descriptive statistics.
3. **Data Cleaning:** Convert price, discount, rating, and rating-count columns into numeric formats.
4. **Missing Value Analysis:** Measure missing values and handle missing rating counts.
5. **Duplicate Analysis:** Check for duplicate product records.
6. **Exploratory Data Analysis:** Investigate product pricing, ratings, and category-level statistics.
7. **Data Visualization:** Create histograms, scatter plots, bar charts, and a word cloud.
8. **Review Analysis:** Apply basic polarity-based sentiment scoring to review text.
9. **Correlation Analysis:** Examine the relationship between discounted prices and ratings.

## Key Findings

- The dataset contains 1,465 product records and 16 columns.
- Two missing values were identified in `rating_count` and replaced with the column median.
- The average product rating in the analyzed dataset is approximately 4.10 out of 5.
- The correlation between discounted price and rating is approximately 0.12, indicating a weak positive linear relationship in this dataset.
- Product ratings and average discounts were compared across product categories.

These findings describe the analyzed dataset and should not be generalized to all Amazon products or customers.

## Project Structure

```text
Amazon-Sales-Analysis/
├── amazon_sales.ipynb
├── amazon.csv
├── requirements.txt
└── README.md
```

## Installation & Usage

Install the required libraries:


pip install pandas numpy matplotlib seaborn scipy wordcloud textblob jupyter


Launch Jupyter Notebook:


jupyter notebook


Open `amazon_sales.ipynb` and run the cells in order.

## Limitations

- The analysis is based on the available dataset rather than live Amazon data.
- The dataset contains product and review information, not verified transaction-level sales.
- Correlation does not establish causation.
- Automated sentiment polarity is a basic text-analysis method and may not accurately capture sarcasm, context, or nuanced opinions.

## Author

**Haidy Seada**

Senior Data Analyst | Python | SQL | Power BI | Data Visualization