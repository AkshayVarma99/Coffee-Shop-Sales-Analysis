# Coffee Shop Sales Analysis - Maven Roasters

## Table of Contents
- [Project Overview](#project-overview)
- [Data Structure](#data-structure)
- [Key Insights & Recommendations](#key-insights--recommendations)
- [Sales Dashboard Overview](#sales-dashboard-overview)
- [Interactive Dashboard](#interactive-dashboard)
- [Recommendations](#recommendations)
- [Resources](#resources)

## Project Overview
**Maven Roasters** is a fictitious coffee shop chain with three locations across New York City. This project analyzes the sales data to derive insights into the shop's performance and customer behavior. Using key metrics such as total revenue, order volume, average order value (AOV), and product performance, the analysis identifies trends and patterns that can help optimize operations, improve customer satisfaction, and boost sales.

The project includes the development of an interactive dashboard using **Streamlit** to visualize key metrics and make data-driven decisions. The analysis is performed using **Python**, **Pandas**, and **SQL**, with an emphasis on product-level performance and customer preferences.

## Data Structure
The coffee shop's sales data consists of a single table with 149,115 records, containing transaction details, timestamps, location information, and product-level sales.

## Key Insights & Recommendations

### Key Insights:
- **Total Revenue**: $698K generated from 149K orders, with the highest revenue month being June ($166K).
- **Top Location**: **Hell's Kitchen** generated the most revenue, contributing $236K.
- **Top Products**: **Barista Espresso** was the top-performing product with $91K in sales.
- **Most Popular Coffee Type**: **Gourmet Brewed Coffee** was the most ordered coffee, with 16K orders (29% of total coffee sales).
- **Peak Hours**: Sales peaked at 10 AM with 18K orders, while the least performing hour was 8 PM with 603 orders.
- **Popular Product Categories**: Coffee was the most popular category, followed by Tea and Bakery.

### Recommendations:
1. **Target High-Value Products**: Promote **Coffee Beans** with seasonal offers like “Buy One Get One Free” to encourage bulk purchases, especially during colder months when customers tend to brew coffee at home.
2. **Boost Sales During Slow Months**: To drive revenue during January and February (typically low-earning months), introduce offers like reward cards or complimentary drinks for birthdays.
3. **Optimize Operating Hours**: Since sales drop significantly after 8 PM, consider launching end-of-day promotions or discounts to increase sales during slower hours.
4. **Revise Product Categories**: Rotate underperforming product categories and introduce new offerings to engage customers and create fresh interest.
5. **Gather Customer Feedback**: Regularly send surveys at the end of each season to gather feedback on customer satisfaction, service quality, and product offerings, helping refine business strategies.

## Sales Dashboard Overview
The interactive sales dashboard provides the following key insights:
- **Revenue by Month & Location**: Visualizes revenue trends across locations and months, highlighting June as the peak month and Hell's Kitchen as the top performer.
- **Top Products by Revenue**: Displays a ranking of products by sales, with **Barista Espresso** leading.
- **AOV by Product**: Shows Average Order Value (AOV) for each product, with **Coffee Beans** having the highest AOV at $22.
- **Popular Categories & Coffee Types**: Analyzes the performance of product categories and coffee types, highlighting **Coffee** as the most popular category and **Gourmet Brewed Coffee** as the most ordered coffee type.
- **Peak Hour & Day**: Visualizes peak sales hours (10 AM) and provides insights on sales distribution throughout the day.

## Interactive Dashboard
An interactive dashboard is available for a more detailed analysis. You can explore the data visually, view insights, and make data-driven decisions based on the findings. The dashboard was developed using **Streamlit**, and you can view it [here](link_to_dashboard).

## Recommendations
- Implement promotional offers for **high-value products** like Coffee Beans during colder months.
- Use targeted marketing campaigns in **slow months** (e.g., January and February) to increase customer engagement and sales.
- Introduce **end-of-day discounts** to increase sales during the 8 PM hour when sales are the lowest.
- Experiment with new **product categories** to keep the menu fresh and engage repeat customers.
- Conduct regular **customer feedback surveys** to continuously improve service quality and product offerings.

## Resources
- Pre-processing steps for data cleaning and transformation can be found [here](link_to_resources).
- View the **interactive Streamlit dashboard** [here](link_to_dashboard).
