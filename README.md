<div align="center">

# 👗 ━━ Myntra · Sales & Product Analytics Dashboard ━━ 👠
### *Interactive Power BI Report on E-Commerce Orders, Revenue, Brands & Products*

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Measures%20%26%20KPIs-FF3F6C?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![E-Commerce](https://img.shields.io/badge/Domain-E--Commerce%20Fashion-FF6F00?style=for-the-badge&logo=myntra&logoColor=white)](https://powerbi.microsoft.com/)
[![Slicers](https://img.shields.io/badge/Interactive-Slicers%20%26%20Filters-9C27B0?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://powerbi.microsoft.com/)
[![Pages](https://img.shields.io/badge/Report%20Pages-2-4CAF50?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://powerbi.microsoft.com/)

<br/>

![Revenue](https://img.shields.io/badge/💰%20Revenue-₹3.75%20Cr-2E7D32?style=flat-square)
![Orders](https://img.shields.io/badge/🛒%20Orders-12K-6A1B9A?style=flat-square)
![Products](https://img.shields.io/badge/👕%20Products-2500-FF3F6C?style=flat-square)
![Top Tier](https://img.shields.io/badge/🏙️%20Top%20City%20Tier-Tier%202-FB8C00?style=flat-square)
![Data](https://img.shields.io/badge/📅%20Data%20as%20of-30%20Apr%202025-1A1A5E?style=flat-square)

<br/>

> *"Fashion changes every season — data tells you what's trending right now."*

</div>
Video Link -  https://drive.google.com/drive/u/0/folders/1TVddC1wxxaakbelyzyEMPRUoYqVSsjVm

---

## 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🏗️ Project Structure](#️-project-structure)
- [🔄 Project Workflow](#-project-workflow)
- [📊 Dashboard Pages](#-dashboard-pages)
  - [🛍️ Page 1 — Sales Overview](#️-page-1--sales-overview)
  - [📦 Page 2 — Product Analysis](#-page-2--product-analysis)
- [🛠️ Tech Stack](#️-tech-stack)
- [📈 Results & Insights](#-results--insights)
- [🏆 Advantages](#-advantages)
- [⚙️ How to Run](#️-how-to-run)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 📌 Overview

The **Myntra Sales & Product Analytics Dashboard** is a two-page, interactive **Power BI** report that analyzes an online fashion and beauty marketplace. It shows **orders, revenue, brand and category performance, city-tier demand, inventory by size and order status**, helping a business team see what sells, where it sells and how orders end up.

This project is designed to:
- 🛒 Track total orders and revenue with month-over-month change
- 🏷️ Compare brands and categories by orders and revenue
- 🏙️ Understand demand across **Tier 1, Tier 2 and Tier 3** cities
- 👕 Review product mix, size-wise inventory and top-selling products
- 📦 Monitor order outcomes: Delivered, Shipped, Returned and Cancelled

> 📅 **Data as of:** 30 Apr 2025 &nbsp;|&nbsp; 💱 **Currency:** ₹ (Indian Rupees)

---

## 🎯 Problem Statement

> **Objective:** Build an interactive e-commerce dashboard that helps the business understand sales performance and product mix across brands, categories and cities.

Online fashion platforms handle thousands of orders across hundreds of brands and products. Without clear visuals it is hard to answer: *"Which categories drive orders?"*, *"Which cities buy most?"*, *"Which products earn the most?"* and *"How many orders get returned or cancelled?"*

| 📂 Dashboard Page | 📄 Focus Area | 🔍 Key Question Answered |
|-------------------|---------------|--------------------------|
| 🛍️ Sales Overview | Orders & Revenue | How are sales trending and where do orders come from? |
| 📦 Product Analysis | Products & Fulfilment | What is the product mix, which products earn most and how do orders end? |

The goal is to demonstrate **end-to-end BI skills**: data modeling, DAX, visual design and storytelling for e-commerce.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 🗂️ **2 Interactive Pages** | Left icon navigation between Sales Overview and Product Analysis |
| 🎛️ **Slicers** | Brand, Category and City Tier filters |
| 🔢 **KPI Cards with Sparklines** | Total Orders and Total Revenue with mini trend lines |
| 📉 **MoM Comparison** | Change versus the previous month (Mar 2025) |
| 🍩 **Donut Charts** | City tier share, product distribution and order status |
| 📊 **Ranked Bar Charts** | Orders by category and brand, revenue by brand and city tier |
| 📦 **Inventory View** | Size-wise inventory (M, L, S, XS, XL) |
| 📋 **Top 10 Table** | Best products by revenue with brand, category and orders |
| 🎨 **Branded Theme** | Navy, pink and purple palette inspired by the Myntra look |

---

## 🏗️ Project Structure

```
📦 myntra-sales-dashboard/
│
├── 📄 Myntra_.pbix               ← Power BI report file (data model + visuals)
│
├── 🖼️ images/                    ← Dashboard screenshots
│   ├── myntra-01-sales-overview.png
│   └── myntra-02-product-analysis.png
│
└── 📄 README.md                  ← Project documentation
```

---

## 🔄 Project Workflow

```
Raw E-Commerce Data (Orders, Products, Brands, Customers, Cities)
      │
      ▼
┌──────────────────────────────┐
│  Power Query — Clean & Shape │  ← Types, dates, city tiers, categories
└────────────┬─────────────────┘
             │
             ▼
┌──────────────────────────────┐
│   Data Model (Star Schema)   │  ← Orders fact + Product, Brand, City, Date dims
└────────────┬─────────────────┘
             │
             ▼
┌──────────────────────────────┐
│    DAX Measures & KPIs       │  ← Total Orders, Revenue, MoM %, Status counts
└────────────┬─────────────────┘
             │
     ┌───────┴────────┐
     ▼                ▼
┌───────────────┐  ┌──────────────────┐
│ Sales Overview│  │ Product Analysis │
└───────────────┘  └──────────────────┘
             │
             ▼
   Insights & Business Decisions ✅
```

---

## 📊 Dashboard Pages

### 🛍️ Page 1 — Sales Overview

> Orders, revenue and demand by category, brand and city tier.

<div align="center">

![Sales Overview](images/myntra-01-sales-overview.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 Total Orders | Order count with sparkline and change vs Mar 2025 (**▼ 5.1%**) |
| 💰 Total Revenue | **₹3.75 Cr** with sparkline and change vs Mar 2025 (**▼ 3.5%**) |
| 🍩 Orders by City Tier | Share of orders across Tier 1, 2 and 3 |
| 📊 Orders by Category | Top categories ranked by orders |
| 📊 Orders by Brand | Top brands ranked by orders |
| 🎛️ Slicers | Brand, Category and City Tier |

**Highlights:**
- 🏙️ **Tier 2** cities generate the most orders (**50.76%**), followed by **Tier 1** (**37.05%**) and **Tier 3** (**12.18%**)
- 👶 **Kids Wear** is the top category with **1,613** orders, then **School Shoes** (1,485) and **Face Wash** (1,060)
- 🏷️ Among named brands, **Nike** leads with **1.3K** orders, followed by **H&M**, **Zara** and **Puma** (1.2K each)
- 📉 Both orders and revenue are lower than the previous month (−5.1% and −3.5%)

---

### 📦 Page 2 — Product Analysis

> Product mix, inventory, brand and city-tier revenue, and order status.

<div align="center">

![Product Analysis](images/myntra-02-product-analysis.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🍩 Product Distribution | Share of products by category (**2,500** total products) |
| 📊 Size-wise Inventory | Stock across M, L, S, XS and XL |
| 📊 Brand Performance (Revenue) | Revenue by brand |
| 📊 City Tier Analysis (Revenue) | Revenue by Tier 1, 2 and 3 |
| 📋 Top 10 Products by Revenue | Product, brand, category, orders and revenue |
| 🍩 Order Status Distribution | Delivered, Shipped, Returned, Cancelled |

**Highlights:**
- 🧴 Product mix: **Kids Wear** 13.28%, **School Shoes** 12.16%, **Face Wash** 8.8%, **Lipstick** 7.8%, with the rest grouped as "Others"
- 📏 Size **M** has the highest inventory, followed by **L** and **S**; **XS** and **XL** are lowest
- 💎 **Puma** (₹0.85 Cr) and **Nike** (₹0.82 Cr) lead named brands in revenue
- 🏙️ **Tier 2** cities also lead in revenue (₹3.88 Cr), ahead of **Tier 1** (₹2.83 Cr) and **Tier 3** (₹0.93 Cr)
- 📦 Order status is split almost evenly: **Delivered**, **Returned** and **Shipped** about 25.26% each, **Cancelled** 24.23%

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 📊 **Microsoft Power BI Desktop** | Report building & visualization |
| 🧮 **DAX** | Measures, MoM comparison, counts and revenue totals |
| 🧹 **Power Query (M)** | Data cleaning and transformation |
| 🔗 **Data Modeling** | Star schema with product, brand, city and date dimensions |
| 🎛️ **Slicers & Navigation** | Brand, Category, City Tier filters and icon page navigation |
| 🎨 **Custom Theme** | Navy, pink and purple e-commerce styling |

---

## 📈 Results & Insights

After exploring the dashboard, the following conclusions emerge:

- 🏙️ **Tier 2 Drives Demand** — Over half of orders and the highest revenue come from Tier 2 cities
- 👶 **Everyday Essentials Lead** — Kids Wear, School Shoes and Face Wash top the order counts
- 🏷️ **Brand Competition Is Tight** — Nike, H&M, Zara and Puma are close together at 1.2K to 1.3K orders
- 📏 **Medium Size Dominates** — Size M holds the most inventory
- ⚠️ **Fulfilment Risk** — About one in four orders is returned and about one in four is cancelled
- 📉 **Slight Monthly Dip** — Orders and revenue are below March 2025

---

## 🏆 Advantages

| Advantage | Detail |
|-----------|--------|
| 🎯 **Clear & Simple** | Two focused pages that are easy to read |
| 🔍 **Actionable Insights** | Shows top categories, brands, cities and risky order statuses |
| 🎛️ **Fully Interactive** | Slicers cross-filter every visual |
| 📉 **Trend Aware** | Sparklines and MoM change on the KPI cards |
| 🎨 **Visually Appealing** | Branded colors and consistent card layout |
| 🔄 **Refreshable** | Update the data source and all visuals refresh automatically |
| 🧪 **Extensible** | Easy to add pages such as Customers, Returns or Discounts |
| 📚 **Portfolio Friendly** | Shows data modeling, DAX and BI storytelling skills |

---

## ⚙️ How to Run

1. **Clone** this repository
   ```bash
   git clone https://github.com/your-username/myntra-sales-dashboard.git
   ```
2. **Install** [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows)
3. **Open** `Myntra_.pbix`
4. Use the **left icon bar** to switch pages and the **slicers** (Brand, Category, City Tier) to filter

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

```
MIT License — Free to use, modify, and distribute with attribution.
```

> ⚠️ *Disclaimer: This is an educational/portfolio project. The dataset is simulated, and the Myntra name and branding are used only for illustration. It is not affiliated with or endorsed by Myntra.*

---

## 👤 Author
Asvi Ambaliya
### Your Name

[![GitHub](https://img.shields.io/badge/GitHub-yourhandle-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourhandle)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/your-profile/)

> *"Every dashboard starts with a question — and ends with a decision."*

**🎓 Role:** Data Analyst | Power BI Developer \
**📍 Location:** India \
**🛠️ Skills:** Power BI · DAX · Power Query · Data Modeling · E-Commerce Analytics · Data Storytelling

</div>

---

## 🙏 Acknowledgements

Special thanks to the following resources and communities that made this project possible:

- 📚 [Microsoft Power BI Docs](https://learn.microsoft.com/en-us/power-bi/) — Official Power BI documentation
- 🧮 [DAX Guide](https://dax.guide/) — Complete DAX function reference
- 🎓 [SQLBI](https://www.sqlbi.com/) — Data modeling and DAX best practices
- 💬 [Power BI Community](https://community.fabric.microsoft.com/) — Problem-solving support
- 📖 [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi) — Power BI learning paths

---

<div align="center">
Asvi Ambaliya
</div>
