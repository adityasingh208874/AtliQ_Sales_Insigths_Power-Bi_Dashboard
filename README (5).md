# AtliQ Hardware Sales Performance Dashboard | Power BI

An end-to-end sales analytics project built in Power BI, following the Codebasics Power BI project series. It turns raw sales data for AtliQ Hardware into an interactive dashboard that shows how the business is performing across markets, products, customers and time.

📺 Source project: [Codebasics Power BI YouTube Playlist](https://youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9&si=5dCyBWsm8AKLDCVq)
   |   [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDhlZThjZGEtMWQ0OC00N2MxLWIyYWEtZjk1YTA2OGFmMzYwIiwidCI6IjFiZDEyNzA3LTQ4NWQtNDI2OS1hOWY0LTVlNzkwZTI4YjI3MiJ9)

---

## Problem Statement

AtliQ Hardware supplies computer hardware and peripherals to clients across India, with its headquarters in Delhi and sales offices in multiple regions. As the business grew, the sales director found it hard to get a clear, up-to-date picture of performance. And whenever he calls the regional managers to get the current status of the sales and market, as a human behaviour, these people sugar cote the truth and send tons of Excel files instead of disclosing the truth, and which made it difficult to spot trends, weak markets and top customers.

## Goal
build a single, interactive dashboard that gives leadership accurate, real-time sales insights to support faster and better decisions.

---

## Dashboard Overview

The **Sales Overview** page includes:

| Section | What it shows |
|---|---|
| **KPI cards** | Total Sales, Total Quantity Sold, Previous Year Sales, YoY Growth %, YoY Growth |
| **Top Markets** | Markets ranked by revenue |
| **Best Selling Products** | Products contributing the most revenue |
| **Monthly Revenue Trend** | Month-by-month revenue for the selected year |
| **Top Customers by Revenue** | Highest-value customers |
| **Revenue by Zone** | Regional split (Central, North, South) |
| **Customer Type Revenue** | Brick & Mortar vs E-Commerce contribution |
| **Year slicer** | Filter the whole report by 2017, 2018, 2019 or 2020 |

---

## Tools & Skills Used

- **Power BI Desktop** for data modeling and visualization
- **Power Query** for data cleaning and transformation
- **DAX** for measures such as Total Sales, Previous Year Sales and YoY Growth
- **SQL / MySQL** for the source database (if you used it, otherwise delete this line)
- **Data modeling** with a star schema (fact and dimension tables)

---

## Repository Structure

```
├── DATASET/                 Source data files
├── PowerBi_Dashboard/       Power BI report (.pbix)
├── Screenshots/             Dashboard preview images
└── README.md
```

---

## Dashboard Preview

![Sales Overview](Screenshots/dashboard.png)

---

## Key Insights

Add your own findings here, for example:

- Total sales in 2019 were ₹336.02M, compared with ₹413.69M in 2018 (YoY decline of 18.77%)
- Top markets: *(add names)*
- Best-selling products: *(add names)*
- Revenue split by customer type: *(add %)*

---

## How to Use This Project

1. Clone or download this repository.
2. Open the `.pbix` file inside `PowerBi_Dashboard/` in **Power BI Desktop**.
3. If prompted, update the data source path to point to the files in `DATASET/`.
4. Use the year slicer and visuals to explore the data.

---

## Acknowledgements

This project was built by following the excellent [Codebasics](https://codebasics.io/) Power BI tutorial series. The dataset and problem statement belong to Codebasics.

---

## Connect With Me

**Your Name** | [LinkedIn](PASTE-LINKEDIN-LINK) | [GitHub](https://github.com/YOUR-USERNAME)
