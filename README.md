Amazon Sales Data Analysis Project 📊
📋 Project Overview
This project involves a comprehensive analysis of Amazon sales data to extract actionable insights into sales performance, product popularity, and customer behavior. By leveraging Python's data science libraries, I conducted data cleaning, exploratory data analysis (EDA), and visualization to support strategic business decision-making.

🎯 Key Objectives
Sales Overview: Analyze revenue trends and patterns over time.

Product Analysis: Identify top-selling categories and size preferences.

Fulfillment Analysis: Evaluate the effectiveness of different shipping methods.

Customer Segmentation: Distinguish between B2B and B2C buying behaviors.

Geographical Analysis: Map sales distribution across various Indian states and cities.

🛠️ Tech Stack
Language: Python

Libraries: Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization), NumPy (Numerical Analysis)

🧼 Data Cleaning Process
To ensure the accuracy of the analysis, the following steps were taken:

Handling Missing Values: Filled null values in the Amount and geographical columns.

Data Type Correction: Converted the Date column to a standardized datetime format.

Column Removal: Dropped empty or redundant columns like New and PendingS.

Export: Saved the processed data as Cleaned_Amazon_Sale_Report.csv.

📈 Key Insights & Visualizations
1. Sales Trends
The analysis reveals significant fluctuations in daily revenue, identifying specific high-demand periods that can be leveraged for future marketing campaigns.

2. Product Preferences
T-shirts emerged as the leading product category, with Medium (M) being the most frequently purchased size.

3. Geographical Hotspots
Maharashtra is the highest revenue-generating state, followed by Karnataka and Tamil Nadu, indicating a strong urban market presence.

💡 Recommendations
Inventory Management: Prioritize stock for M and L size T-shirts to prevent stock-outs.

Marketing Strategy: Focus advertising spend on the top 3 states (Maharashtra, Karnataka, Tamil Nadu).

Shipping: Continue leveraging Amazon Fulfillment, as it handles the majority of successful deliveries.

📁 Repository Structure
DA_Code.ipynb: The main Python Notebook containing the analysis code.

Cleaned_Amazon_Sale_Report.csv: The processed and cleaned dataset.

images/: Contains all visualization charts (PNG format).

Amazon Sale Report.csv: The raw dataset used for the project.
