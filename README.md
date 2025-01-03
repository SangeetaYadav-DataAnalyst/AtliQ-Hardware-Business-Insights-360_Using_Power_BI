## Welcome to AtliQ Hardware Business Insights 360 - Your Gateway to Data-Driven Decision Making!

This project is a comprehensive Power BI dashboard developed to analyze and visualize key performance metrics across various departments at AtliQ Hardware. It provides actionable insights into finance, sales, marketing, supply chain, and executive operations, empowering stakeholders to make informed decisions for strategic growth.

[Link to Interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjliZjFjY2YtMTE4OC00NTBmLWE4ZmEtNTU5YzJhN2Q1ZTQyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Overview

AtliQ Hardware has experienced rapid growth in recent years, expanding its operations globally and serving customers through three primary **channels—retailers, direct sales, and distributors**. However, the company recently faced a major setback when a new store in America, launched based on intuition and limited Excel analysis, resulted in unforeseen losses. Meanwhile, competitors with strong analytics teams were making data-driven decisions, leaving AtliQ with no choice but to embrace a data analytics culture to remain competitive.

This project marks AtliQ’s first step into Power BI, to empower stakeholders to make better decisions using real-time analytics. The focus areas for this project span finance, sales, marketing, and supply chain operations.

I, Sangeeta , worked on this project by following tools and techniques:

## 📌 Project Kickoff: Key Questions to Ask Before Starting
Before diving into the project, I focused on clarifying the objectives and understanding stakeholder expectations. These were some key questions that helped guide the process:

1. What is the primary objective of building this Power BI dashboard?
2. How will the success of this project be measured?
3. What is the timeline for the project, and are there any preview milestones?
4. What hopes and fears do stakeholders have regarding this dashboard?
5. Who will be using the dashboard, and for what purpose?
6. What resources and data are required to build the dashboard?
7. Are there any specific design preferences or expectations from stakeholders?

This initial phase was critical to ensure alignment with business needs and to avoid rework later in the process.

## 📊 Understanding the Dataset

Once the project goals were clear, I explored the data the data engineering team provided. Here's a high-level view of the datasets:

### Dimension Tables

- **dim_customer:** Includes static details like customer names, markets, and platforms (e.g., Brick & Mortar, E-commerce).
- **dim_market:** Contains information on 27 distinct markets, 7 sub-zones, and 4 regions (APAC, EU, LATAM, and NAN).
- **dim_product:** Lists product categories and divisions, such as PCs, peripherals, and networking equipment.

### Fact Tables

- **fact_forecast_monthly:** Holds forecasted customer demand for improved inventory planning and cost optimization.
- **fact_sales_monthly:** Similar to the forecast table, but includes actual sold quantities.

### Additional Tables

- **freight_cost:** Transportation costs for each market.
- **gross_price:** Product pricing details.
- **pre_invoice_deductions & post_invoice_deductions:** Deductions applied before and after invoicing.
- **manufacturing_cost:** Product manufacturing costs by year.

The data engineering team ensured that the datasets were denormalized for analytics purposes. However, understanding the structure of dimension and fact tables was crucial for effective data modeling in Power BI.

## 📐 Data Modeling

Data modeling forms the foundation of any successful Power BI project. For this report, I followed the **snowflake schema** to ensure optimized performance and ease of use. Poor data modeling can negatively impact report performance, so I paid special attention to relationships, cardinality, and ensuring clean joins.

Key practices followed:
![h](https://github.com/user-attachments/assets/1eaab072-d23e-459a-8e24-be9ad0832042)


- Avoiding circular dependencies.
- Using surrogate keys for relationships.
- Creating a date table using M language for consistent time-based analysis.
  
**Tech Stacks:**

1. SQL
2. PowerBi Desktop
3. Excel
4. DAX language
5. DAX Studio (for report optimization)
6. Project charter file

**PowerBI Techniques Learned:**

1.  Asking the right questions before starting a project
2.  Creating calculated columns
3.  Creating measures using the DAX language
4.  Data modeling
5.  Using Bookmarks to switch between visuals
6.  Page navigation with buttons
7.  Preventing zero division errors using the divide function
8.  Dynamic titles based on applied filters
9.  Using KPI indicators
10. Conditional formatting of visual values with icons or background colour
11. Data validation techniques
12. Publishing reports to Power BI services
13. Setting up a personal gateway for data auto-refresh
14. Creating PowerBi Apps
15. Collaborating, managing workspaces, and setting access permissions in Power BI services

**Company Background:**
AtliQ Hardware sells computers and accessories through retailers and direct distributors worldwide. They recently faced unexpected losses in their American store due to decisions based on surveys, intuition, and limited Excel analysis. To compete better, the company needs to build an analytics team for data-driven insights and decisions.

**Project Outcome:**
This project aims to clarify the purpose and goals of the data analytics initiative. The report generated will enable data-driven decision-making and answer numerous questions about the company's performance. It's a step towards surviving and thriving in the industry.

**Overall Report**

Home Page of the Dashboard
![h](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/Home.png)

Finance View
![f](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/finance.png)

Sales View
![s](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/Sales.png)

Marketing View
![m](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/marketing.png)

Supply Chain View
![sp](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/Supply_Chain.png)

Executive View
![e](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/executive.png)

Info Page
![i](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/info.png)

Support Page
![sprt](https://github.com/SangeetaYadav-DataAnalyst/AtliQ-Hardware-Business-Insights-360/blob/main/Support.png)

Your thoughts and feedback are highly appreciated. Let's continue this data-driven journey together!
