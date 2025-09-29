# Global Superstore Sales Dashboard

## 1. Project Title / Headline
🌐 Global Insights: Superstore Sales Analytics Dashboard  
A dynamic, interactive data visualization tool built with Power BI to analyze a dataset of 51,290 global superstore orders, focusing on sales performance, profitability, regional trends, and customer returns.

## 2. Short Description / Purpose
The Global Insights Dashboard is a visually engaging and analytical Power BI report designed to help business analysts, sales managers, and regional teams explore superstore sales data comprehensively. This tool is intended to provide actionable insights into sales trends, profit margins, shipping costs, and return rates to optimize inventory, pricing, and logistics strategies.

## 3. Tech Stack
The dashboard was built using the following tools and technologies:
- 📊 **Power BI Desktop** – Primary platform for creating interactive reports and visualizations.
- 📂 **Power Query** – Used for data transformation, cleaning, and creating derived columns and a Date Table.
- 🧠 **No DAX (Data Analysis Expressions)** – Relied on Power BI’s built-in aggregations and visual-level filters to avoid complex calculations, per user preference.
- 📝 **Data Modeling** – Established relationships among Orders, Returns, People, and Date Table for cross-filtering.
- 📁 **File Format** – `.pbix` for development and delivery.

## 4. Data Source
- **Source**: `global_superstore_2016.xlsx` dataset embedded in the `.pbix` file.
- **Details**: Includes 51,290 order records with fields such as `Order ID`, `Sales`, `Profit`, `Shipping Cost`, `Order Date`, `Region`, `Category`, `Sub-Category`, `Quantity`, and custom columns like `Is Returned` and `Sales per Unit`.
- **Notes**: Data spans 2012-2015; update the source in Power Query if using a different dataset, ensuring column names and formats align.

## 5. Features / Highlights
- **Business Problem**  
The retail industry struggles with analyzing large order datasets to identify regional performance, profitability drivers, and return patterns. Key questions like "Which regions are most profitable?" or "How do shipping costs impact sales?" are challenging without integrated visualization.

- **Goal of the Dashboard**  
To deliver an interactive visual tool that:  
- Enables users to explore global superstore sales data in detail.  
- Supports decisions such as regional focus, pricing adjustments, and return management.  
- Uncovers trends in sales, profit, shipping efficiency, and product popularity.

- **Walkthrough of Key Visuals**  
  - **Key KPIs (Summary Page)**  
    - Total Sales: ~$2.2M (based on dataset)  
    - Total Profit: ~$266K  
    - Total Orders: 5,009  
    - Total Customers: 793  
    - Total Quantity: 37,873  
  - **Fiscal Year & Region Filter Panel (All Pages)**  
    Interactive dropdown slicers allow users to filter all visuals by year (2012-2015) and region (e.g., Central, East, West, South).  
  - **Sales Performance (Line Chart, Trends)**  
    Line chart displays sales trends by month, colored in blue (`#4A90E2`).  
  - **Region Performance (Stacked Bar Chart, Trends)**  
    Stacked bar chart shows sales by region, with colors like West (`#4A90E2`), East (`#9B59B6`), Central (`#E74C3C`).  
  - **Revenue Split by Category (Stacked Bar Chart, Trends)**  
    Stacked bar chart illustrates sales by category (Technology, Furniture, Office Supplies) with matching colors.  
  - **Top 3 Products by Sales (Clustered Bar Chart, Products)**  
    Clustered bar chart highlights the top three sub-categories (e.g., Phones, Chairs, Tables) by sales, with distinct colors.  
  - **Category Ranking (Table, Products)**  
    Table lists top 5 sub-categories by sales for detailed insight.  
  - **Quantity & Sales by Category (Table, Products)**  
    Table shows quantity and sales totals per category.  
  - **Performance Ratio (Cards, Metrics)**  
    Two cards display total Profit (red `#E74C3C`) and Sales (blue `#4A90E2`) for visual comparison.  
  - **Avg Shipping Cost by Region (Bar Chart, Metrics)**  
    Bar chart presents average shipping cost by region, styled like other bars.  
  - **Sales by Segment (Donut Chart, Insights)**  
    Donut chart visualizes sales distribution by segment (Consumer, Corporate, Home Office) with template colors.  

- **Business Impact & Insights**  
  - **Regional Optimization**: Identify high-performing regions for targeted marketing or resource allocation.  
  - **Profitability Analysis**: Assess profit margins and shipping costs to refine pricing strategies.  
  - **Return Management**: Analyze return rates by region to improve product quality or customer satisfaction.  
  - **Product Focus**: Highlight top-selling products for inventory and promotion decisions.
