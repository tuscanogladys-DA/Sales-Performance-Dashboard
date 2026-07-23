# <h1 align="center">Adventure Works Sales Dashboard</h1>
<p align="center"><i>An end-to-end Power BI portfolio project by Gladz</i></p>

![AdventureWorks Dashboard](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/AdventureWorks%20Sales%20Dashboard%20GIF.gif)

## 📊 Project Overview: AdventureWorks Sales Performance Analysis Dashboard

**Tools used:** Power BI Desktop · Power Query (ETL) · DAX · Excel

## <h1 align="center">The Why</h1>
Adventure works is a bike company that needed help to gain a better understanding as to what was going on within the business. Thus our goal with this report was to help provide insights for our stakeholders to things such as:
- Provide insight into key KPI's
- Compare regional performance
- Analyze product level trends
- Identify high-value customers
- key drivers of return rate

## <h1 align="center">The Dataset</h1>
Three years (2020–2022) of AdventureWorks order-line transactions, joined against product, customer, territory, and calendar dimension tables, plus a separate returns feed — roughly **56,000 order-line records** across **17,000+ customers** in **6 countries**.

## <h1 align="center">The Build Process</h1>
1. **Extract & clean** — imported ten source CSV files into Power Query; standardized inconsistent date formats, removed footer/export metadata rows from the customer file, and fixed a key-name mismatch between the territory table and the fact tables.
2. **Data Model** — built a star schema design 
- **Fact tables**: Sales, Returns
- **Dimension tables**: Calendar, Product, Subcategories, Categories, Territory, Customer
 and supporting measure tables (`Aggregators` and `Time Intelligence`/`Variance KPI`) to keep all DAX measures organized separately from the data tables.
3. **Calculate** — added calculated columns (Age Group, Full Name, Income Bracket,etc.) and 20+ DAX measures covering revenue, profit, returns, and year-over-year growth.
4. **Design** — five report pages plus a home/navigation page, using a custom earth-tone theme (deep green `#1C2B1A` / `#3A5C2E` with amber accents) and a consistent button-based page navigator.

**Why this matters:** this project demonstrates the same skill set I use professionally — ETL cleanup of messy real-world data, relational modeling, DAX-driven KPIs, and dashboard storytelling — applied to a retail sales scenario end to end.

---

## <h1 align="center">🏠 Home / Navigation</h1>

A clean landing page with a title, my profile summary, a short project description, and button-based navigation to each of the four analytical pages plus the Executive Summary. This mirrors how I structure real client deliverables: a cover page that orients a non-technical stakeholder before they dive into the numbers.

---

## <h1 align="center">📈 Executive Summary</h1>

![Executive Summary](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Executive%20Summary.jpg)

**Goal:** Give leadership a single-page, at-a-glance view of overall business health — revenue, profit, orders, and returns — with year-over-year comparison built in.

**Business problem it solves:** This page answers "how is the business health? in one glance"

---

## <h1 align="center">🗺️ Location</h1>

![Location](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Location.jpg)

**Goal:** To answer where are we winning? Break down where revenue is actually coming from geographically, to guide market-level investment and business expansion decisions.

**Business problem it solves:** Sales and marketing teams need to know where to focus expansion budget and where existing coverage isn't converting. A flat country list in a spreadsheet doesn't show this gap as clearly as a geographic comparison does.

---

## <h1 align="center">🚲 Product & Category</h1>

![Product & Category](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Product%20%26%20Category.jpg)


**Goal:** To answer what's selling? and what's dragging? Identify which products and subcategories are actually generating revenue and margin, versus which are just taking up shelf/catalog space.

**Business problem it solves:** Category managers need to know where to prioritize inventory investment and promotional spend — this page turns "we sell a lot of stuff" into "we sell these specific bikes."

---

## <h1 align="center">👥 Customer Insights </h1>

![Customer Insights](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Customer%20Insights.jpg)

**Goal:** To answer who is actually buying? A clear customer demographics to inform marketing segmentation and targeting.

**Business problem it solves:** Marketing can't personalize campaigns without knowing the core customer profile. This page replaces guesswork with an actual segmentation view: who buys, and which segments are under-monetized relative to their size or income.

---

## <h1 align="center">↩️ Return Analysis </h1>

![Return Analysis — Returns by Category](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Return%20Analysis.jpg)

**Goal:** To answer where is value leaking out? Quantify the scale and cost of product returns, and pinpoint which products are driving them, to reduce revenue leakage.

**Business problem it solves:** A 2% return rate sounds trivial in isolation, but this page shows *where* that risk concentrates — critical for a quality or supply chain team deciding where to focus a fix.

---

## <h1 align="center">🎯 Data Model </h1>
![Data Model Design](https://github.com/tuscanogladys-DA/Sales-Performance-Dashboard/blob/main/Aw%20Images/Model%20view.jpg)
The dashboard uses a **star schema** design:
- **Fact tables**: Sales, Returns
- **Dimension tables**: Calendar, Product, Subcategories, Categories, Territory, Customer
- Product hierarchy introduces a slight **snowflake characteristic** (Product → Subcategory → Category).

## <h1 align="center">**Key Takeaways:**</h1>
- Bikes carries almost the entire revenue base.
- Regional seasonality tracks the global pattern fairly consistently, suggesting demand drivers are more product/seasonal than region-specific.
- Professionals drive the most revenue by occupation from customers age range 50+, concentrated in the middle-income bracket.
- Accessories account for the majority of returned units

## <h1 align="center">🎯 Personal Insights </h1>

This project let me apply the same analytical rigor I use in health and benefits consulting — clean data, model it right, build measures that answer real questions — to a completely different industry. The result: a five-page dashboard that takes a leadership team from "how's the business doing?" down to "which products and which regions actually generates income?" in a few clicks.

---

**Let's connect** if you're hiring for a Data Analyst or BI role, or just want to talk shop about Power BI, DAX, or Data Analytics.

📩 tuscano.gladys@gmail.com | 🔗 [LinkedIn](www.linkedin.com/in/gladys-tuscano-data-analyst)
