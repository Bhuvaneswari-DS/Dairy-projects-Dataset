# Dairy-projects-Dataset
📄 Dataset Description
This dataset contains 440 observations and 8 features.

It appears to be related to customer purchasing behavior based on different types of product categories.

All fields are numeric (integers) and represent either categories (Channel, Region) or annual expenditures in various product types.

✏️ Columns:

Column Name	Description
Channel	Customer segment (encoded numerically)
Region	Geographical area of the customer (encoded numerically)
Fresh	Annual spending on fresh produce
Milk	Annual spending on milk products
Grocery	Annual spending on grocery items
Frozen	Annual spending on frozen foods
Detergents_Paper	Annual spending on detergents and paper products
Delicassen	Annual spending on delicatessen foods
🛠️ Key Questions and Analysis using Pandas
1. Data Cleaning & Preparation
✅ Check for missing values across all columns.

✅ Detect and handle outliers in expenditure fields.

✅ Identify customers with extremely low or zero spending across all categories.

2. Basic Exploration
🔎 Find the number of unique values in Channel and Region.

🔎 Calculate descriptive statistics (mean, median, std) for each spending category.

🔎 Determine minimum and maximum values for each product category.

3. Grouping and Aggregation
📊 Group data by Channel and compute the average expenditure per product category.

📊 Group data by Region and sum the total spending.

📊 Compare average spending between different channels and regions.

4. Comparative Analysis
🔥 Compare spending patterns across regions: Which region spends the most on Fresh products? Frozen? Grocery?

🔥 Compare Channel-wise product preferences (e.g., does Channel 1 spend more on Milk or Grocery compared to Channel 2?).

5. Customer Segmentation
🧠 Create a new feature Total_Spend = Fresh + Milk + Grocery + Frozen + Detergents_Paper + Delicassen.

🧠 Identify the top 5% of customers by total spending.

🧠 Segment customers based on their dominant spending category (e.g., Fresh-dominant vs Grocery-dominant customers).

6. Correlation Analysis
📈 Compute and visualize the correlation matrix for spending features.

📈 Identify strong positive or negative correlations (e.g., Milk vs Grocery, Detergents_Paper vs Grocery).

7. Anomaly Detection
🚨 Find customers who spend significantly high amounts in only one category.

🚨 Identify multi-category outliers (customers with extreme values across several categories).

📊 Potential Visualizations (Optional Extensions)
Histogram of expenditures per product category.

Boxplots to detect outliers in each category.

Heatmap of correlations between spending categories.

Bar plots comparing average expenditures across Channels and Regions.

Scatter plots to study relationships (e.g., Milk vs Grocery expenditures).
