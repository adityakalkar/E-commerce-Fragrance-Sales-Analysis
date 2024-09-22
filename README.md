# E-commerce-Perfume-Sales-Analysis

This project focuses on analyzing men's perfume sales data from eBay, with the goal of uncovering insights related to pricing, availability, and brand performance. The analysis is conducted using both SQL and Python, incorporating data cleaning, SQL querying, data visualization, and statistical hypothesis testing to provide a comprehensive view of the factors affecting perfume sales.

## Data Source
The dataset includes perfume listings with details like brand, title, price, available stock, and units sold. Key columns analyzed include brand, price, available, and sold, along with timestamps for when listings were last updated.

## Objectives
The main goals of this project are to clean and preprocess the data, perform SQL-based queries to investigate pricing and sales patterns, analyze the correlation between key variables, and evaluate the performance of different brands. Additionally, hypothesis testing is conducted to determine whether price significantly affects sales.

## Key Features
The dataset was cleaned by imputing missing values and then stored in an SQLite database for efficient querying. Price ranges were categorized into bins for detailed analysis of sales distribution, and SQL queries were used to identify price points and brands with the highest sales. Correlation analysis explored the relationships between price, available, and sold, while hypothesis testing showed that price does impact sales, though weakly. Lastly, a brand performance analysis highlighted the top-selling brands, with Calvin Klein and Versace leading.

## Results
Most sales occur in the $20-40 price range, with a weak but statistically significant negative correlation between price and sales. Top brands like Calvin Klein and Versace dominate the market, suggesting that brand reputation plays a key role in sales, even more than pricing strategies.

## Future Work
Future enhancements include time-series analysis of sales trends and using machine learning to predict sales based on features like price and brand.
