# 📊 Mid-D Hub — Sales Intelligence Dashboard

> A multi-tab Tableau dashboard delivering end-to-end visibility into Sales, Products, and Employees & Customers for a mid-distribution business.

---

## 🖼️ Dashboard Preview

### Sales
![Sales Dashboard](screenshots/sales.png)

### Products
![Products Dashboard](screenshots/products.png)

### Employees & Customers
![Employees & Customers Dashboard](screenshots/employees-customers.png)

---

## 📁 Repository Structure

```
Mid-DHub/
├── Mid-DHub.xlsx                  # Source data (Excel)
├── Tablue_Mid_D-Hub_.twbx         # Packaged Tableau workbook
├── screenshots/
│   ├── sales.png
│   ├── products.png
│   └── employees-customers.png
└── README.md
```

---

## 📌 Dashboard Overview

The workbook contains **3 interactive tabs**, each focused on a distinct business domain:

---

### 1. 💰 Sales

Tracks overall revenue performance and geographic distribution.

| KPI | Value |
|-----|-------|
| Total Sales | $22.9M |
| # Orders | 8,188 |
| Units Sold | 1.03M |
| Net Profit | $9.9M |

**Visuals included:**
- Sales & COGS trend by quarter (2013 Q1 – 2016 Q2)
- COGS %, Gross Profit Margin (GPM), and Average Transaction (AVG T) donut gauges
- Top 20 Sales Cities treemap
- % Sales by State horizontal bar chart (California 44.4%, Washington 21.3%, Alaska 15.1%, …)

---

### 2. 📦 Products

Analyzes product catalog health, demand, and profitability.

| KPI | Value |
|-----|-------|
| # Products | 671 |
| # Active Products | 227 |
| AVG Dry Lead Day | 13 Days |
| AVG Chilly Lead Day | 3 Days |

**Visuals included:**
- Active / ADP ratio donut charts
- Sales by Product Size treemap (50m, 20m, L, XL, M, S, 1/12 scale, 10m, N/A)
- Sales & Profit by Product bubble chart
- Profit by Package spiral chart (Each 96.1%, Packet 2.2%, Pair 1.1%, Bag 0.6%)
- Sales by Product Color bar chart (Blue $6.5M · N/A $5.1M · Black $3.8M · …)
- Top 20 Demand Products ranked list

---

### 3. 👥 Employees & Customers

Monitors customer activity, buying group performance, and salesperson rankings.

| KPI | Value |
|-----|-------|
| # Customers | 401 |
| # Active Customers | 49 |
| Avg. Order Price | $2.8K |
| AVG Delivery Days | 1 Day |
| # Employees | 211 |
| # Salespersons | 122 |

**Visuals included:**
- Active Customer % donut (12.2%)
- ASP gauge (81%)
- Sales by Buying Group Venn diagram (Independent $7.8M · Tailspin Toys $9.3M · Wingtip Toys $5.8M)
- Top 15 Customers lollipop chart (Customer IDs, max $409K)
- Top 20 Sales Persons ranked bar chart (Archer leads)

---

## 🛠️ Requirements

| Tool | Version |
|------|---------|
| Tableau Desktop / Tableau Public | 2021.1 or later |
| Microsoft Excel | 2016 or later (for source data) |

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/mid-d-hub.git
   cd mid-d-hub
   ```

2. **Open the workbook**
   - Launch **Tableau Desktop** or **Tableau Public**
   - Open `Tablue_Mid_D-Hub_.twbx`
   - The packaged workbook includes the data source — no extra connection steps needed

3. **Explore the data source**
   - Raw data lives in `Mid-DHub.xlsx`
   - Open it in Excel to inspect or modify the underlying tables before re-connecting in Tableau

---

## 🔄 Refreshing the Data

1. Update `Mid-DHub.xlsx` with new records
2. In Tableau, go to **Data → [Data Source Name] → Refresh**
3. All dashboards will update automatically

---

## 📊 Key Insights at a Glance

- **California dominates** with 44.4% of total sales
- **Tailspin Toys** is the top buying group at $9.3M in sales and $4.0M net profit
- **Blue** is the best-selling product color at $6.5M
- **"Each"** packaging accounts for 96.1% of profit by package type
- Only **12.2%** of customers are active — significant retention opportunity
- **Archer** leads the salesperson rankings with the highest revenue contribution

---

## 📄 License

This project is for internal business intelligence and reporting purposes.

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-viz`)
3. Commit your changes (`git commit -m 'Add new visualization'`)
4. Push to the branch (`git push origin feature/new-viz`)
5. Open a Pull Request

---

## 📬 Contact

For questions or feedback, open an issue or reach out to the data team.
