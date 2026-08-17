# Customer Segmentation Dashboard — RFM Analysis

An interactive customer segmentation project using **RFM analysis** (Recency, Frequency, and Monetary value) on the Sample Superstore dataset.

## Live dashboard

After GitHub Pages is enabled, the dashboard will be available at:

`https://delwar-mahmud.github.io/customer-segmentation-rfm-dashboard/`

Replace `YOUR-USERNAME` with your GitHub username.

## Project overview

This project helps marketing and e-commerce stakeholders identify valuable customers, customers who need attention, and customers at risk of churn. The browser dashboard is fully interactive and contains the dataset within the page, so it requires no backend.

### Features

- Segment, region, and order-year filters
- Customer-name search
- RFM KPI cards and customer-segment visualization
- Clickable segment bars
- Sortable priority-customer table
- Responsive desktop, tablet, and mobile layout

## RFM business rules

| Metric | Score 3 | Score 2 | Score 1 |
|---|---:|---:|---:|
| Recency | 90 days or less | 91–365 days | More than 365 days |
| Frequency | 8+ orders | 4–7 orders | 1–3 orders |
| Monetary | $4,000+ | $1,500–$3,999.99 | Less than $1,500 |

## Dataset

- **Source:** Sample Superstore
- **Rows:** 9,994 transactions
- **Customers:** 793
- **Analysis period:** 2014–2017

## Tools and skills demonstrated

- Customer segmentation and RFM analysis
- Data cleaning and validation
- Business-rule scoring
- KPI design and stakeholder-focused storytelling
- Interactive dashboard development with HTML, CSS, and JavaScript
- GitHub Pages deployment

## Run locally

Download the repository and open `index.html` in a modern browser. No installation or internet connection is required.

## Repository structure

```text
.
├── index.html              # Complete interactive dashboard and embedded data
├── README.md               # Project documentation
├── DEPLOYMENT.md           # GitHub Pages publishing instructions
└── .nojekyll               # Serves the project as a static site
```

## Important note

This repository contains the shareable web edition of the analysis. The data preparation and RFM model were designed for a Power BI customer-segmentation workflow; the published dashboard is implemented as standalone HTML, CSS, and JavaScript so recruiters can view it without a Power BI account.

