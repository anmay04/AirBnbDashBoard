# 🏡 Airbnb Booking & Customer Analysis Dashboard

A comprehensive Tableau dashboard project that provides deep insights into Airbnb's booking trends, customer behavior, and revenue patterns across countries and time. This analysis blends storytelling with business intelligence to empower stakeholders with actionable insights.

🌐 View Live Dashboard

## 🔗 [Click here to explore the interactive Tableau dashboard](https://public.tableau.com/views/AirbnbBookingsAnalysisFinal/DetailedAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📊 Project Overview

This project visualizes and explores a rich dataset on Airbnb bookings. The dashboard provides interactive insights into:

- Monthly booking and cancellation trends
- Revenue generation across locations
- Customer type distributions
- Booking lead time and rating performance
- Country-wise and owner-specific performance

Developed using Tableau Desktop Public Edition, the dashboard showcases data storytelling and slicing features designed for operational and strategic decision-making.

---

## 📌 Key Insights

| Insight Area               | Details                                                                               |
| -------------------------- | ------------------------------------------------------------------------------------- |
| Booking Analysis           | 📈 Peak bookings observed in **September** (178 bookings)<br>📉 Minimum in **July**   |
| Revenue                    | 💰 Total revenue reached **$36.4K** across 396 bookings                               |
| Customer Type              | 👥 Majority were **Transient-Party** (45.2%) and **Transient** (29.2%)                |
| User Channel Preference    | 🧾 Highest via **Online Travel Agents (318)**                                         |
| Property Type Distribution | 📍 Dominated by **Prime Locations** (365 vs. 31 Non-Prime)                            |
| Owner Analysis             | ⭐ Gina Gomez and Kristen Torres generated > **$12K** in revenue                      |
| Country Reach              | 🌍 Bookings span 30+ countries including **Germany**, **Brazil**, **Australia**, etc. |

---

## 📁 Files Included

| File Name                | Description                                      |
| ------------------------ | ------------------------------------------------ |
| `airbnb.csv`             | Core dataset with bookings and country metrics   |
| `dim_owner.csv`          | Owner metadata (names, performance, etc.)        |
| `dim_room_2.csv`         | Room-level granularity: location, type, etc.     |
| `fake_data_generator.py` | Python script using Faker to simulate owner data |

---

## 📷 Dashboard Snapshots

### 🧭 Homepage – Booking Analysis

![Booking Analysis](./assets/Screenshot%202025-06-16%20145844.png)

### 📍 Detailed View – Customer & User Insights

![Detailed Analysis](./assets/Screenshot%202025-06-16%20150159.png)

---

## 🛠 Tools Used

- **📊 Tableau Public** – Data visualization and dashboard creation
- **🐍 Python (Faker + Pandas)** – Synthetic data generation and preprocessing
- **📄 CSV Files** – Data modeling across facts and dimensions

---

## 🚀 How to Explore

1. Download the `.twbx` Tableau Workbook file (coming soon).
2. Install Tableau Public [here](https://public.tableau.com/en-us/s/download).
3. Open the workbook and interact with filters and visualizations.
4. For simulated data: run `fake_data_generator.py` in Python 3 environment.

---

## 🔮 Future Enhancements

- Embed predictive models using Python (e.g., booking forecast)
- Connect live data sources via Tableau Server
- Add user-level filters and dashboards for specific stakeholders

---

## 👤 Author

**Anant**  
_Data Analyst | Tableau Enthusiast | Insight Explorer_

---

> _“In a world full of data, let dashboards be your compass.”_
