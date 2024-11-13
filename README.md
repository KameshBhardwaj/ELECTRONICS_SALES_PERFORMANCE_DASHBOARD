# Electronics Sales Performance Dashboard

## Objective
The goal of this project was to analyze electronic sales data from September 2023 to September 2024, focusing on customer demographics, purchasing behaviors, and product preferences. This dashboard provides insights for improved decision-making, customer targeting, and marketing strategies.

## Data Cleaning and Preparation
I performed an initial data review in Excel to identify blanks, irregularities, and formatting issues. Further data cleaning and transformation steps were conducted in Power BI, including:

- **Table Duplication and Splitting**: Created two tables, one for overall sales data and another for add-on purchases.
- **Custom Columns**: Used DAX formulas to create columns for total sales, age groups, add-on categories, and calculated additional metrics such as average age and total customer count.
- **Unpivoting**: Unpivoted columns to handle add-ons as separate items, making analysis easier.
- **Measures for KPIs**: Defined measures for Total Sales, Add-on Price, Total Number of Customers, Average Rating, and Units Sold.

## Data Visualization in Power BI
To visualize the data effectively, I designed a two-page dashboard with the following features:

- **Button for Page Navigation**: A button is placed on each page to switch seamlessly between Page 1 and Page 2, ensuring easy access to all insights without overwhelming the space on a single page.
- **Slicers for Interactivity**: Key slicers, such as **Gender**, **Age Group**, **Shipping Type**, and **Loyalty Membership Status**, allow users to filter and analyze specific segments. These slicers are synced across both pages to maintain the same filtering selections on each page.

### Page 1 Visualizations
1. **Cards (KPI Summary)**: Display total customers (12k), total sales ($64.8M), total units sold (110k), and average rating (3.09).
2. **Add-on Sales by Category (Stacked Bar)**: Summarizes revenue by add-on types: Impulse Item, Accessory, and Extended Warranty.
3. **Sales by Payment Method (Stacked Bar)**: Shows customer payment preferences, including PayPal, Credit Card, and Bank Transfer.
4. **Sales by Product Type (Stacked Bar)**: Highlights top-selling product categories, such as Smartphones, Smartwatches, and Laptops.
5. **Customer Gender Distribution (Donut Chart)**: Compares customer gender percentages.
6. **Loyalty Membership Distribution (Donut Chart)**: Illustrates the split between loyalty program members and non-members.

### Page 2 Visualizations
1. **Sales and Customer Count by Age Group (Line and Stacked Column)**: Shows total sales and number of customers in age brackets from 18-80.
2. **Loyalty Members by Age Group (Line Chart)**: Tracks loyalty membership distribution across age groups.
3. **Sales Trends by Month (Line Chart)**: Displays monthly sales trends, with peaks and dips in specific months.
4. **Sales by Order Status and Shipping Type (Clustered Bar)**: Compares revenue based on order completion and shipping preference.
5. **Sales by Gender and Product Type (Treemap)**: Analyzes male and female purchase patterns across different electronic products.

## Analysis and Insights
1. **Customer Overview**: 12k customers contributed to $64.8M in total sales with 110k units sold. Average customer satisfaction rating was moderate at 3.09.
2. **Product and Payment Preferences**: Smartphones and smartwatches lead in sales. Payment preference varies, with PayPal and Credit Cards being the most popular.
3. **Add-On Purchases**: Add-ons, such as impulse items and accessories, contributed significantly, showing cross-selling opportunities.
4. **Gender and Loyalty Breakdown**: There is an almost equal gender split, while loyalty membership participation is lower (26.61%).
5. **Age-Related Sales Trends**: Older age groups (66-80) have the highest sales volume, while younger groups (18-25) have lower spending. Targeted promotions may optimize these trends.
6. **Order and Shipping Patterns**: Expedited and standard shipping dominate, with a notable cancellation rate in same-day delivery orders, warranting closer investigation.

## Recommendations for Future Analysis
1. **Broaden Product Range**: Consider adding new product lines to attract more customer segments.
2. **Enhance Loyalty Program**: Introduce targeted loyalty incentives or tiered rewards to boost retention.
3. **Targeted Promotions**: Offer age-specific promotions, especially to encourage purchases among younger customers.
4. **Explore Payment-Based Offers**: Partner with credit card companies for exclusive discounts, as these are high-volume payment methods.
5. **Analyze Order Cancellations**: Investigate reasons behind high cancellations, especially with specific shipping types, to reduce future lost sales.

## Conclusion
This dashboard offers a comprehensive view of electronic sales performance over the past year, with insights into customer demographics, preferences, and behavior. The analysis points to actionable opportunities in product expansion, customer loyalty, and targeted marketing, which could drive future growth and improved customer satisfaction.
