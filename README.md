# Super-Store-Sales-Dashboard
This Super Store Sales Dashboard provides a comprehensive overview of sales performance across regions, segments, sub-categories, and time periods. Built using Power BI, it enables dynamic filtering and tracking of key sales KPIs such as total revenue, profit, quantity sold, and average delivery time. The dashboard empowers decision-makers to optimize product strategy, logistics, and customer segmentation.

## Problem Statement
The company needed a unified view of sales performance to understand trends across different regions, customer segments, and product categories. Without such visibility, it was difficult to identify high-performing areas, optimize inventory, or reduce delivery times.

To address this, an interactive Power BI dashboard was created to monitor sales and profitability metrics. By using slicers, KPIs, and visual analysis (donut charts, bar graphs, line graphs, and maps), it helps management make informed decisions to boost revenue, streamline delivery, and refine marketing strategies.

## Steps Followed
- Step 1 (Data Collection): Loaded the "Superstore" dataset into Power BI. This dataset contains transaction-level data including sales amount, product categories, customer segment, ship mode, payment type, and delivery time.
- Step 2 (Data Cleaning and Preparation): Used Power Query to remove nulls and duplicates. Calculated average delivery time in days and cleaned date formats.
- Step 3 (DAX Measures): Built custom KPIs including:

        Total Sales = SUM(Sales[SalesAmount])
        Total Profit = SUM(Sales[Profit])
        Avg Delivery Time = AVERAGE(Sales[DeliveryDays])
- Step 4 (Visualizations): Designed interactive visuals for Sales by Region, Payment Mode, Segment, Category, and Sub-Category. Added Year-on-Year trend lines and maps to identify location-wise performance.
- Step 5 (Interactivity and Slicers): Integrated filters by region (Central, East, South, West), category, and ship mode to allow cross-drill analysis.
- Step 6 (Design & Formatting): Applied pastel gradient backgrounds and consistent color legends. Used KPI cards and charts to convey performance clearly.

## Snapshot of Super Store Sales Dashboard (Power BI Service)
![Image](https://github.com/user-attachments/assets/9e34125b-9ab0-419f-8396-e0b27244b102)

## Insights
1. Total Sales Reach 2M with a Profit of 175K: The company achieved 2 million in revenue with a profit of 175K from 22K orders. However, the average delivery time is high at 103 days, suggesting supply chain inefficiencies.
2. West Region Leads in Sales (33%): Among all regions, the West accounts for the highest share of sales (33%), followed by East (29%) and Central (22%). South performs the lowest at just 16%.
3. COD and Online Payments Dominate: Cash on Delivery (43%) and Online payments (35%) make up the majority, suggesting convenience-focused buyer behavior. Cards are the least used at 22%.
4. Consumers Drive the Most Sales (48%): The Consumer segment contributes the most to total sales, followed by Corporate (33%) and Home Office (19%). Marketing efforts can focus more on the Consumer group.
5. Phones and Chairs Are Top-Selling Sub-Categories: Phones (0.20M) and Chairs (0.18M) generate the most revenue, followed by Binders and Storage. This indicates demand concentration in tech and furniture.
6. Standard Shipping Mode Is Widely Used: 0.68M worth of goods were shipped using Standard Class, much higher than First Class or Same Day delivery. This could explain longer delivery times.
7. YoY Sales Trends Show Higher Sales in Early and Late Year: Monthly sales peaked during March and November 2020. A clear seasonal pattern is visible, highlighting strategic months for promotions.
8. Profit Declines Mid-Year: Although sales remain consistent, monthly profit drops significantly during May to August. Indicates possible discounts or high operating costs during this period.

## Acknowledgements
This dashboard is built as part of a Data Visualization and Analytics learning project. Inspired by Rishabh Mishra – YouTube.
