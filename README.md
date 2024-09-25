# BlinkIT Grocery Data Analysis Project
![Untitled design](https://github.com/user-attachments/assets/7ba5415f-cb50-4973-977f-bf6800cc274d)

## Project Overview
This project is a comprehensive analysis of BlinkIT’s grocery sales dataset, conducted using Power BI. It involves data cleaning, visualization, and deriving actionable business insights. The project culminates in an interactive dashboard designed to assist stakeholders in optimizing product strategies, outlet management, and marketing efforts.



## Dataset Description

The dataset used in this analysis contains **8,523** records with the following columns:

- **Item Fat Content**: Classification of the product's fat content (Low Fat, Regular).
- **Item Identifier**: Unique identifier for each item.
- **Item Type**: Category of the product (e.g., Fruits and Vegetables, Frozen Foods).
- **Outlet Establishment Year**: Year when the outlet was established.
- **Outlet Identifier**: Unique identifier for each outlet.
- **Outlet Location Type**: Classification of the outlet's geographical location (Tier 1, Tier 2, Tier 3).
- **Outlet Size**: Size of the outlet (Small, Medium, High).
- **Outlet Type**: Type of outlet (e.g., Supermarket Type1, Type2).
- **Item Visibility**: Percentage visibility of the item in the store.
- **Item Weight**: Weight of the item in kilograms (some missing values).
- **Sales**: Sales figures for each item.
- **Rating**: Customer ratings for each product on a scale from 1 to 5.



## Project Workflow

### 1. Data Cleaning
- **Missing Values**: Addressed missing values in the **Item Weight** column using interpolation techniques.
- **Standardization**: Ensured consistent formatting across categorical columns such as **Item Fat Content** and **Outlet Size**.
- **Outlier Detection**: Checked for outliers in **Sales**, **Item Visibility**, and **Item Weight**, and treated them where necessary.
- **Data Validation**: Verified the accuracy of data points, particularly in categorical columns like **Outlet Type** and **Item Type**.

### 2. Data Analysis
A thorough analysis was performed using Power BI to understand the following aspects:

- **Sales Analysis**: 
  - The average sales per item across outlets is ₹141, with the highest being ₹266.89.
  - Items in **Tier 1 outlets** generated the highest sales, indicating higher customer traffic or spending power in these locations.

- **Product Performance**:
  - Categories such as **Fruits and Vegetables** and **Frozen Foods** contributed significantly to total sales.
  - **Low Fat** products performed better in sales, suggesting a consumer preference for healthier options.
  
- **Outlet Insights**:
  - Outlets classified as **Supermarket Type1** and located in **Tier 1** cities saw the best overall performance.
  - Outlets with a **High size** had higher sales compared to Medium and Small outlets.

- **Customer Behavior**:
  - Products with higher **Item Visibility** (above 6.61%) performed better in terms of sales, highlighting the importance of product placement and visibility.
  - **Customer Ratings**: Products with average ratings above 4.0 tend to generate higher sales, indicating that quality ratings impact purchase decisions.

### 3. Dashboard Development
The Power BI dashboard was developed with the following components:

- **Sales by Outlet**: A visual breakdown of sales performance by outlet type, size, and location.
- **Sales by Product Type**: A bar chart showing sales across different product categories.
- **Item Visibility vs. Sales**: A scatter plot demonstrating the correlation between product visibility and sales.
- **Rating Distribution**: A visual distribution of customer ratings, helping to understand consumer satisfaction.
- **Interactive Filters**: Custom filters for users to view sales data by outlet size, location, item type, and year of establishment, making the analysis more accessible and insightful.



## Key Insights and Results

1. **Outlet Performance**:
   - Outlets in **Tier 1** cities and those categorized as **Supermarket Type1** account for approximately **60% of total sales**.
   - Large-sized outlets perform better, contributing significantly more to revenue compared to smaller outlets.

2. **Product Categories**:
   - **Fruits and Vegetables** and **Frozen Foods** are the most profitable categories.
   - There is a clear consumer preference for **Low Fat** products, accounting for a substantial portion of sales.

3. **Visibility & Ratings**:
   - Items with greater visibility (more than 6.61%) tend to drive higher sales.
   - Products with ratings of **4 and above** perform better, emphasizing the impact of customer satisfaction on revenue.

4. **Sales Trends**:
   - Consistent patterns across outlets indicate that high-visibility products should be prioritized.
   - High-performing outlets should continue receiving investments for growth and promotions.



## Business Application of the Dashboard

This Power BI dashboard offers significant value to BlinkIT’s management team and other stakeholders:

1. **Inventory Management**:
   - By identifying top-performing product categories like **Fruits and Vegetables**, the team can make more informed decisions regarding stock levels and replenishment.

2. **Outlet Performance Monitoring**:
   - The dashboard allows management to track sales across different outlet types and locations, highlighting the performance of outlets in **Tier 1** cities and larger stores, helping focus expansion efforts in the right areas.

3. **Targeted Marketing Campaigns**:
   - Insights into **Low Fat** product sales can inform the marketing team to promote healthier product options, tapping into consumer preferences.
   - Visibility metrics help refine product placement strategies, ensuring high-demand items are prominently displayed.

4. **Customer Satisfaction**:
   - The **Rating Analysis** empowers BlinkIT to focus on improving products with lower ratings, potentially increasing customer retention and sales in the long term.



## Conclusion

This project demonstrates the power of data-driven decision-making for retail businesses. The dashboard provides clear, actionable insights that BlinkIT can leverage to improve product strategies, optimize outlet performance, and enhance customer satisfaction. With the insights generated, the client can make informed decisions that drive growth and increase operational efficiency.
