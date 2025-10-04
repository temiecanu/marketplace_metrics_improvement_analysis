# Marketplace Metrics Improvement Analysis

## Project Overview

This project dives deep into how users engage with the e-commerce platform across sessions — identifying bottlenecks, churn timelines, and drop-off triggers. Using Python (Pandas, Plotly, Seaborn), I explored user activity patterns and evaluated conversion performance at each funnel stage. The project delivers clear, actionable insights to boost user engagement, improve repeat purchase rates, and support product and marketing teams with evidence-backed decisions.

### Company Context: NovoMercado

NovoMercado is a fictional online marketplace modelled to resemble mid-size regional e-commerce platforms. Through exploratory data analysis (EDA), funnel tracking, and visual storytelling, the notebook uncovers actionable insights to improve customer experience and conversion rates across the platform.

---

## Repository Structure

```
marketplace_metrics_improvement_analysis/
│
├── data/                      
│   ├── olist_orders_dataset.csv           # Orders placed by customers
│   ├── olist_order_items_dataset.csv      # Items within each order
│   └── olist_customers_dataset.csv        # Customer metadata
│
├── business_analysis_presentation.pdf     # Final project slides
├── marketplace__metrics_analysis.ipynb    # Full analysis notebook
├── README.md
```

---

## Project Goals

- **Funnel Breakdown**: Analyse the key stages of the user journey to detect where users drop off.
- **User Inactivity Patterns**: Identify days and points in the journey when customers stop engaging with the platform.
- **Retention Metrics**: Evaluate customer retention by tracking repeat activity and session return rates.
- **Recommendations**: Propose product and marketing actions backed by behavioural data.

---

## Data Description

### Tables

- **Orders (`olist_orders_dataset.csv`)**
  - Contains order-level metadata: order ID, customer ID, order status, and key timestamps.

- **Order Items (`olist_order_items_dataset.csv`)**
  - Includes product-level details per order, such as item ID, quantity, and price.

- **Customers (`olist_customers_dataset.csv`)**
  - Provides anonymised customer metadata, including unique customer ID and location (city/state).

---

## Tools Used

- Python (Pandas, NumPy)
- Visualisation: Plotly, Seaborn, Matplotlib
- Jupyter Notebook for step-by-step workflow and documentation
- EDA techniques: funnel analysis, retention curves, cohort segmentation

---

## Business Questions

- What stages of the user funnel have the highest drop-off?
- How long does it typically take for users to churn?
- Which product categories drive more repeat purchases?
- When are users most engaged in their sessions?
- What behaviours predict long-term retention?

---

## Key Insights

- Drop-offs are concentrated around early funnel stages and add-to-cart transitions.
- Users tend to disengage after initial sessions; key inactivity spikes are measurable.
- Repeat purchase rates are low for certain product categories.
- User engagement varies by time of day and session order.

---

## Recommendations

- Improve onboarding UX to prevent early funnel exits.
- Introduce re-engagement nudges after session inactivity spikes.
- Promote categories with high repeat purchases in remarketing.
- Optimise site traffic for peak hours of user engagement.

---

## Results

- Presented targeted retention actions to reduce churn and extend session activity.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/artemietu/marketplace_metrics_improvement_analysis
cd marketplace_metrics_improvement_analysis
```
2. Install required libraries:

```bash
pip install -r requirements.txt
```
3. Run the Jupyter notebook or script:

```bash
jupyter notebook marketplace_metrics_improvement_analysis.ipynb
```

---

## Author

Artemie Țurcanu — Data Analyst.