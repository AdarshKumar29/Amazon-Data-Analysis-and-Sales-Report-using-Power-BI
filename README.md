### Amazon-Data-Analysis-and-Sales-Report-using-Power-BI
This project demonstrates the end-to-end process of building a robust business intelligence solution for Amazon e-commerce analytics using Power BI. Two real-world datasets- **Amazon_Sales_Report** and **Amazon_Fashion** were imported, cleaned, and transformed to enable comprehensive analysis.

## Key Steps:

- ### Data Integration & Cleaning:
  Both datasets were imported into Power BI and thoroughly cleaned in the Query Editor. This included standardizing column names, handling missing values, and deriving new     fields such as shipping details and total sales amount. The datasets were then merged using the ASIN (Amazon Standard Identification Number) as a relational key,      facilitating cross-table analysis.

- ### Data Modeling:
  A relational data model was established using ASIN to connect sales transactions with detailed product attributes. This enabled seamless aggregation and drill-through   analysis across both datasets.

- ### DAX Calculations:
  Custom DAX measures were developed to calculate key performance indicators, including:

  - Total Sales Amount

  - Total Orders

  - Pending, Cancelled, and Shipped Orders

  - Return Rate

    These measures provided dynamic, real-time insights into business performance.

- ### Interactive Dashboards:
  Two main dashboards were created:

  - **Orders Dashboard:** Visualizes sales trends, order status breakdowns, and fulfillment metrics.

  - **Products Dashboard:** Showcases product details, sales performance, and category-level insights.
  - An interactive tooltip page was implemented to display detailed product information on hover, enhancing user experience.

## Business Impact:
This solution empowers stakeholders to monitor sales performance, identify top-selling products and regions, and analyze order fulfillment efficiency. The dashboards facilitate data-driven decisions for inventory management, marketing strategies, and customer experience improvements.

## How to Use:

- Explore the Power BI dashboards to interact with sales and product data.

- Use filters and tooltips to drill down into specific categories, products, and order statuses.

- Leverage the insights to inform business strategies and operational improvements.
