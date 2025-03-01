Ved Store Annual Sales Report (2024) - Data Analysis and Insights

Objective:
The primary objective of this analysis is to create an annual sales report for Ved Store for the year 2024. This report aims to provide a detailed understanding of customer behavior, sales trends, and order dynamics, enabling the store to make data-driven decisions to optimize sales and customer engagement strategies for the upcoming year.

Data Cleaning and Preprocessing:
Data cleaning and preprocessing were the first steps in ensuring that the analysis provided meaningful insights. The following actions were performed:
Null Value Handling:
Filters were applied to all columns, identifying and removing any rows containing missing or null values to ensure a clean dataset.
Standardization of Categorical Data:
Gender Data: The "Gender" column had inconsistencies, with values such as "M", "Men", "W", and "Women". We standardized these by replacing "M" with "Men" and "W" with "Women" for uniformity.
Quantity Data: The "Quantity" column had mixed representations, with "one" and "1", "two" and "2" appearing in different rows. These inconsistencies were corrected by replacing textual representations ("one" with "1" and "two" with "2").

Data Transformation:
After cleaning the dataset, the following transformations were applied to facilitate deeper insights:
Age Group Classification: A new column was created to categorize customers into age groups based on the following formula:
=IF(Age>=50, "Senior", IF(Age>=20, "Adult", "Teenager"))
Month Extraction: A new column was added to extract the month from the "Date" column, using the formula:
=TEXT(Date, "mmm")

Data Analysis:
1. Sales vs Orders Comparison:
A pivot table was created to compare sales and orders across months:
Rows: Month
Values:
Sum of "Amount" (Sales)
Count of "Order ID" (Orders)
A combo chart was selected to visualize both sales and order quantities. Since the sales amounts were in millions, the numbers were formatted as:
[0.00,, "M"]
Key Insights:
The month of March saw the highest sales and order volume.

2. Gender-Based Purchase Comparison (Men vs Women):
A pivot table was used to compare the sales between men and women:
Rows: Gender
Values: Sum of "Amount" (Sales)
A pie chart was created for visual comparison.
Key Insights:
Women accounted for a higher volume of purchases than men in 2024.

3. Order Status Distribution:
A pivot table was constructed to analyze the distribution of order statuses:
Rows: Order Status
Values: Count of "Order ID"
A pie chart was used to display the distribution.
Key Insights:
92% of the orders were successfully delivered, indicating a high delivery success rate.

4. Top 10 States Contributing to Sales:
A pivot table was created to identify the top-selling states:
Rows: State
Values: Sum of "Amount" (Sales)
A bar chart was used to visualize the top 10 states contributing to sales.
Key Insights:
Maharashtra emerged as the highest-selling state.

5. Age vs Gender-Based Purchase Patterns:
This pivot table analyzed the relationship between age groups and gender, highlighting purchase behavior:
Rows: Age Group
Columns: Gender
Values: Count of "Order ID" (Sales)
The values were displayed as a percentage of the grand total for clarity, and a clustered column chart was used.
Key Insights:
Adults (ages 20-49) made the highest number of purchases across all age groups.

6. Sales by Channel:
A pivot table was used to analyze the sales distribution across different channels:
Rows: Channel
Values: Count of "Order ID"
The values were displayed as a percentage of the grand total, and a pie chart was used for visualization.
Key Insights:
Amazon, Flipkart, and Myntra were the top three channels driving sales.

Slicers for Dynamic Filtering:
To enhance the interactivity of the report, slicers were added for:
Category
Month
Channel
These slicers were linked to the respective pivot tables, allowing users to filter and explore the data dynamically.

Key Insights and Findings:
Highest Sales Month: March recorded the highest sales and order volume in 2024.
Gender-based Purchases: Women contributed to a higher volume of sales compared to men.
Order Status: 92% of all orders were successfully delivered.
Top States for Sales: Maharashtra was the leading state in terms of sales.
Age Group Insights: The "Adult" age group (ages 20-49) accounted for the largest share of purchases across all age groups.
Top Performing Channels: The highest sales were driven by the online channels Amazon, Flipkart, and Myntra.


Recommendations for Future Growth:
Based on the analysis, the following strategic recommendations are made for increasing sales in 2025:
Target Women Customers (Age 20-49): Focus on women in the age group of 20-49 years who reside in top-selling states such as Maharashtra, Karnataka, and Uttar Pradesh.
Leverage E-commerce Platforms: Continue and expand marketing efforts on platforms like Amazon, Flipkart, and Myntra, which were the highest-performing sales channels in 2024.
Personalized Offers & Promotions: Tailor ads, offers, and coupons for the targeted customer segments to enhance engagement and drive conversions.

By implementing these recommendations, Ved Store can strategically target its customer base and further drive growth and sales in the upcoming year.
