# 🏔️ Wildcraft India — PostgreSQL Sales Analytics

> A self-built retail analytics project inspired by
> Wildcraft India, using fictional but realistic data
> to solve real business problems with SQL.

---

## ⚠️ Disclaimer

> This project is **not affiliated with Wildcraft India**
> in any way. All data — products, customers, orders,
> and revenue figures — is **entirely fictional and
> self-created** for portfolio and learning purposes only.
> Wildcraft India is used purely as a real-world brand
> inspiration to make the business context meaningful.

---

## 📌 Project Overview

Instead of working on a generic "store database,"
I modeled this project around **Wildcraft India** —
a brand known for backpacks, trekking gear, and
outdoor accessories — to simulate what a real
retail analytics pipeline looks like.

**3 tables · 10 queries · ₹28.83 Crore in simulated revenue**

---

## 🏷️ Why Wildcraft?

Wildcraft is one of India's most recognized outdoor
lifestyle brands. Modeling this project around a real
Indian brand helped me frame business questions the
way an actual analyst inside a retail company would —
rather than solving abstract, context-free SQL problems.

---

## 🗃️ Database Schema

| Table       | Description                                    |
|-------------|------------------------------------------------|
| `products`  | Fictional catalog — categories, stock, launch year |
| `customers` | Fictional customer records with city data      |
| `orders`    | Fictional transactions with quantity & revenue |

---

## 🔍 Business Questions Solved

| # | Business Question | SQL Concept |
|---|-------------------|-------------|
| 1 | Which backpacks are in stock? | SELECT, WHERE |
| 2 | Which products launched after 2022? | Comparison Filter |
| 3 | Which customers are in Bengaluru? | WHERE, Filtering |
| 4 | Orders placed in January 2025? | BETWEEN, Date Filter |
| 5 | Total inventory across all products? | SUM() |
| 6 | Orders with quantity > 2 units? | WHERE |
| 7 | Orders generating > ₹20,000 revenue? | WHERE |
| 8 | What product categories exist? | DISTINCT |
| 9 | Which product is at lowest stock? | ORDER BY, LIMIT |
| 10 | What is total revenue? | SUM() → ₹28.83 Cr |

---

## 💡 Key Simulated Business Insights

| Metric | Finding |
|--------|---------|
| 💰 Total Revenue | ₹28.83 Crore (simulated) |
| 🚨 High-Value Orders | Transactions > ₹20,000 flagged |
| 📦 Stockout Risk | Lowest-stock product identified |
| 📍 Top Customer City | Bengaluru — high concentration |
| 📅 Demand Signal | January 2025 order volume captured |
| 🆕 Growth Products | Post-2022 launches tracked |

---

## 🛠️ Tech Stack

```
Database   →  PostgreSQL
Language   →  SQL
Concepts   →  Database Design · Data Import (COPY)
              Aggregation · Filtering · Sorting
              Date Logic · Revenue Analytics
              Inventory Risk · Customer Segmentation
```

---

## 📁 Project Structure

```
wildcraft-sales-analytics/
│
├── schema.sql       → Table creation scripts
├── import.sql       → Data import using COPY
├── queries.sql      → All 10 business queries
└── README.md        → Project documentation
```

---

## 🚀 How to Run

```sql
-- Step 1: Create the database
CREATE DATABASE wildcraft_analytics;

-- Step 2: Run schema.sql to build tables
-- Step 3: Run import.sql to load data
-- Step 4: Run queries.sql to explore insights
```

---

## 📈 What This Project Demonstrates

- Framing SQL around **real business decisions**
- Choosing a **meaningful brand context** over
  generic tutorial datasets
- Building a **clean, documented** analytics pipeline
- Thinking like an **analyst**, not just a coder

---

## 👤 Author

**Aditya Singh Rajput**
Aspiring Data Analyst | SQL · PostgreSQL · Analytics

🔗 [LinkedIn]()


---

⭐ Star this repo if it helped or inspired you!
