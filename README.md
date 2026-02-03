# Retail-Profit-Leak-Analysis-Inventory-Optimization-Dashboard
A  project using SQL, Power BI/Tableau, and Excel to identify revenue and margin losses in a retail business caused by discounts, returns, and inventory inefficiencies. The project models transactional data in a star schema, computes advanced KPIs using SQL, and presents actionable insights through interactive BI dashboards and Excel analysis.
flowchart TD
    A[Business Problem Definition] --> B[Data Collection]
    B --> B1[Orders Data]
    B --> B2[Order Items]
    B --> B3[Products]
    B --> B4[Stores]
    B --> B5[Inventory]
    B --> B6[Returns]
    B --> B7[Promotions]

    B --> C[SQL Data Modeling]
    C --> C1[Star Schema Design]
    C1 --> C1a[Fact_Sales]
    C1 --> C1b[Dim_Product]
    C1 --> C1c[Dim_Store]
    C1 --> C1d[Dim_Date]
    C1 --> C1e[Dim_Promotion]

    C --> D[SQL Transformations & KPIs]
    D --> D1[Revenue & Gross Margin %]
    D --> D2[Return Rate Analysis]
    D --> D3[Discount Impact on Margin]
    D --> D4[Stockout & Lost Sales]
    D --> D5[Inventory Turnover]

    D --> E[BI Visualization Layer]
    E --> E1[Executive Overview Dashboard]
    E --> E2[Store Performance Analysis]
    E --> E3[SKU-Level Profit Leak Analysis]
    E --> E4[Inventory & Stockout Dashboard]

    E --> F[Excel What-If Analysis]
    F --> F1[Discount Sensitivity Model]
    F --> F2[Margin Improvement Scenarios]
    F --> F3[Inventory Optimization Inputs]

    F --> G[Insights & Recommendations]
    G --> G1[Top Loss-Making Products]
    G --> G2[High-Return / Low-Margin SKUs]
    G --> G3[Stockout Reduction Strategy]
    G --> G4[Promotion Optimization]

    G --> H[Final Deliverables]
    H --> H1[Power BI / Tableau Dashboard]
    H --> H2[SQL Scripts & Views]
    H --> H3[Excel Models]
    H --> H4[GitHub Documentation]
