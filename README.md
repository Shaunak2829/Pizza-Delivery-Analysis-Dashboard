# Pizza-Delivery-Analysis-Dashboard

Looking at both dashboard screenshots carefully to capture all the data points and insights before writing the README.

Here's your industry-standard GitHub README description:

---

# 🍕 Pizza Delivery Sales & Operations Analysis | Power BI Dashboard

## Short Description

An end-to-end Power BI dashboard analyzing **1,084 pizza delivery orders** across **6 restaurant brands** and **10 US cities**, covering sales performance, revenue trends, payment behavior, and delivery efficiency. Built to surface operational bottlenecks and revenue patterns that help restaurant managers and operations teams make data-driven decisions.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power Query Editor** | Data cleaning, transformation & shaping |
| **DAX** | KPI measures, calculated columns, time intelligence |
| **`.pbix`** | Development file format |
| **`.png`** | Dashboard preview exports |

---

## 📂 Data Source

- **Platform:** [Kaggle](https://www.kaggle.com/)
- **Domain:** Pizza delivery transactions across multiple US cities and restaurant chains
- **Scope:** Multi-year data (2024–2026) covering order value, payment method, delivery duration, traffic conditions, and customer ratings

---

## ✨ Features & Highlights

### 📊 Page 1 — Pizza Sales Analysis (Home Page)

**Dashboard KPIs:**
- Total Revenue: **$44,105.47**
- Total Orders: **1,084**
- Average Order Value: **$40.70**
- Average Customer Rating: **3.69 / 5**

**Key Findings:**

- 📉 **Order volume is declining sharply year over year** — from **443 orders in 2024** to **373 in 2025** and only **268 in 2026** (a ~40% drop over 3 years), signaling a retention or demand problem that needs urgent investigation.

- 🏙️ **Atlanta leads all cities with $3.2K in revenue**, followed by Milwaukee ($2.7K) and Louisville ($2.6K). The bottom 4 cities — Dallas, Chicago, and Boston — each generate only ~$1.8K, representing a **43% revenue gap** between top and bottom markets.

- 📅 **May is the peak revenue month at $7.4K**, nearly **4.6x higher than July's low of $1.6K** — indicating strong seasonality that can be leveraged for targeted promotions in low-performing months.

- 💳 **Card ($10.8K) and Apple Pay ($10.2K) together account for ~$21K or ~48% of total revenue**, making digital-first payment the dominant channel. Cash still contributes $9.0K, suggesting a mixed customer base.

- 🍕 **Revenue is fairly evenly distributed across all 6 brands** (range: $8.1K–$9.44K), meaning no single restaurant is significantly outperforming others — a competitive positioning opportunity for differentiation.

---

### 🚚 Page 2 — Delivery Performance & Delays

**Dashboard KPIs:**
- Avg Delivery Time (Delayed Orders): **31.08 min**
- Avg On-Time Delivery Time: **28.37 min**
- High Traffic Orders %: **32.29%**

**Key Findings:**

- 🚦 **High traffic conditions inflate delivery time by ~10+ minutes** — average delivery time jumps from **23.60 min (Low traffic)** → **29.53 min (Medium)** → **34.21 min (High)**, a **45% increase** from best to worst condition.

- ⏰ **Delay rates spike at 11AM–12PM (60%) and 12PM–1PM (60%)**, pointing to a clear lunch rush bottleneck. A secondary spike occurs at **8PM–9PM (50%)**, coinciding with dinner demand — these two windows alone are likely responsible for the majority of delayed orders.

- 🏪 **Domino's has the highest delay rate at 40%**, followed by Marco's Pizza (38%) and Papa John's (37%). Little Caesars performs best at 34% — a **6-percentage-point gap** that, at 1,084 total orders, translates to roughly **65 additional delayed orders** at Domino's compared to Little Caesars.

- 📍 **Distance and traffic level are positively correlated with delivery duration** — the scatter plot confirms that high-traffic (red) orders cluster at longer distances and higher delivery times, validating that route optimization or zone-based staffing could directly reduce delays.

---

## 💡 Business Recommendations

1. **Address the order volume decline** — with orders dropping ~40% over 3 years, implement a loyalty/retention program, particularly targeting repeat customers in low-revenue cities.
2. **Staff up during 11AM–1PM and 8PM–9PM** — these peak-delay windows are predictable; pre-scheduling additional delivery riders during these hours could reduce delay rates by an estimated 10–15%.
3. **Domino's needs an operational audit** — at 40% delay rate (highest among all brands), a route or kitchen throughput review is warranted.
4. **Run promotions in July** — with revenue hitting a $1.6K low versus a $7.4K May peak, a July campaign could recover an estimated **$2,000–$3,000 in otherwise lost revenue**.
5. **Double down on Atlanta and Milwaukee** — the top 2 cities by revenue; targeted upsell campaigns here would yield higher ROI than equivalent spend in bottom-tier cities.

6. Preview:
Home Page - https://github.com/Shaunak2829/Pizza-Delivery-Analysis-Dashboard/blob/main/Delivery%20Performance%20page.png
