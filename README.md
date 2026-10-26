<div align="center">

# 🛒 Superstore Sales Performance
### Why $2.3M in sales produced only a 12.47% profit ratio, and how to fix it

**Data Analysis · Tableau · SQL · Project Management** · Orders Jan 2014 – Dec 2017 · Completed July 2025

[![Dashboard](https://img.shields.io/badge/Dashboard-Tableau_Public-E97627?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/shared/MP44DZ8ZT?%3Adisplay_count=n&%3Aorigin=viz_share_link)
[![Story](https://img.shields.io/badge/Case_Study_Story-Tableau_Public-E97627?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/views/SuperstoreSalesPerformanceCaseStudy/SuperstoreSalesPerformanceCaseStudy?%3Alanguage=en-US&publish=yes&%3Asid=&%3Aredirect=auth&%3Adisplay_count=n&%3Aorigin=viz_share_link)
[![Case Study](https://img.shields.io/badge/Case_Study-PDF-B31B1B?style=flat&logo=adobeacrobatreader&logoColor=white)](Case%20Study/Case%20Study-%20Optimizing%20Superstore%20Sales%20Performance%20for%20Enhanced%20Profitability.pdf)
[![Data Portfolio](https://img.shields.io/badge/Data_Portfolio-View-2EA44F?style=flat&logo=github&logoColor=white)](https://github.com/LashawnFofung/Data-Analysis-Portfolio)

[![Superstore Sales Performance Dashboard](Images/Superstore%20Sales%20Performance%20Dashboard.png)](https://public.tableau.com/shared/MP44DZ8ZT?%3Adisplay_count=n&%3Aorigin=viz_share_link)

</div>

---

## Contents
[TL;DR](#tldr) · [The Question](#the-question) · [Data](#data) · [Key Findings](#key-findings) · [Recommendations](#recommendations) · [Caveats](#caveats--open-questions) · [Project Management](#project-management) · [Files](#files) · [My Role](#my-role)

---

## TL;DR

| | |
|---|---|
| **Question** | Superstore's profit is inconsistent across regions, products, and customer segments. What drives profit, and where is money being lost? |
| **Data** | 9,994 orders (2014–2017), plus returns and regional manager tables |
| **Headline** | **$2.3M in sales but only $286,397 in profit (12.47%).** High sales don't guarantee profit. |
| **Biggest leak** | Heavy discounting in Furniture: **Tables lost $17,725** at an average **32% discount**, and Furniture's margin is just **3.5%** |
| **Recommendation** | A **profitability-first strategy:** rein in discounts, invest in high-margin categories, and fix the Central region |
| **Delivered** | Interactive Tableau dashboard and story, a written case study, and a full project plan with WBS |

---

## The Question

Superstore Inc. sells Furniture, Office Supplies, and Technology across the U.S. to Consumer, Corporate, and Home Office customers. Leadership saw strong sales but uneven profit, and wanted to know:

1. **What drives sales and profit?**
2. **Where is the business underperforming** — by region, product, and segment?
3. **What should change** to improve margins?

---

## Data

Three related tables from `sample_superstore.xls`:

| Table | Rows | What it holds | Relationship |
|---|---|---|---|
| **Orders** | 9,994 | Each order: date, customer, segment, product, state, sales, quantity, discount, profit | Central table |
| **Returns** | 800 (296 unique orders) | Orders that were returned | Many returns → one order |
| **People** | 4 | Regional manager for each region | One manager → many orders |

<img src="Images/Sample%20Superstore%20Dataset%20ERD.png" width="600" alt="Entity relationship diagram of the Orders, Returns, and People tables">

📄 [Data structure overview](Data/Data_Structure_Overview.md)

---

## Key Findings

### 💰 Profitability: sales don't equal profit
- **$2.3M** in total sales produced **$286,397** in profit, a **12.47%** profit ratio.
- **Discounts erode margin.** Higher discounts track closely with lower profit.
- **Tables lost $17,725** with an average discount of **32%**.

### 🗺️ Regions: two engines, one problem area

| Region | Profit | Takeaway |
|---|---|---|
| **West** | ~$108,418 | Top profit center |
| **East** | ~$91,489 | Strong second |
| **Central** | ~$39,706 | Underperforms, driven by discounted, unprofitable Furniture orders |

- **Top states by sales:** California (~$457.7K), New York (~$310.9K), and Texas (~$170.2K). Texas sells a lot but earns little profit.

### 📦 Products: where the margin is

| Category | Profit margin | Takeaway |
|---|---|---|
| **Technology** | 18.7% | Highest margin; Phones and Copiers lead |
| **Office Supplies** | 17.9% | Strong margin; Storage leads |
| **Furniture** | 3.5% | Drags down profit; Tables are a net loss, and Bookcases underperform |

- **Phones and Chairs** bring in the most sales, but Chairs, Tables, and Bookcases show that high sales don't guarantee profit.

### 👥 Customers
- The **Home Office** segment stands out as profitable.

---

## Recommendations

| Area | Recommendation |
|---|---|
| **💰 Discounting** | Scale back heavy discounts on Furniture, especially Tables and Bookcases. Move to data-backed pricing that protects margin. |
| **🗺️ Regions** | Use region-specific plans: expand proven product lines in the West and East, and investigate the root cause of low profit in Central. |
| **📦 Products** | Shift marketing and budget toward high-margin Technology and Office Supplies. |
| **📅 Timing** | Plan promotions around seasonal sales peaks. |
| **↩️ Returns** | Address hidden costs from returns. |

**The shift:** from a sales-driven approach to a **profitability-first** one.

---

## Caveats & Open Questions

**Questions for stakeholders before acting:**
- Is 2014–2017 data still representative? Is newer data available to validate these findings?
- How does the return policy affect return rates by category?
- Is there a known reason for the Central region's performance?

**Limitations:**
- **Correlation, not causation.** Discounts and low profit move together, but shipping or supplier costs could also play a role.
- **Missing cost data.** No marketing spend, supplier costs, or inventory costs by region.
- **Data accuracy is assumed** to be complete for the period.

---

## Project Management

I ran this as a real project, not just an analysis, acting as project manager, business analyst, Tableau developer, and QA.

| Artifact | What it covers |
|---|---|
| [Business Requirements](Project%20Management/Business%20Requirement/Capstone%20Project%20-%20Superstore%20Sales%20Performance%20Business%20Requirements.pdf) | Eight dashboard views (KPIs, regional pie, top-N states, sub-category bubbles, sales trend), filters, formats, and layout |
| [Project Management Plan](Project%20Management/PM%20Plan/SSP_Dashboard_Project_Plan.pdf) | Scope, deliverables, stakeholders, timeline, resources, risks, communication plan, and success metrics |
| [Work Breakdown Structure (Smartsheet export)](Project%20Management/WBS/Superstore_Sale_Performance_Dashboard_WBS.xlsx) | Every task, broken down and scheduled |
| [WBS & Timeline Walkthrough (video)](https://youtu.be/t5fny7NXkSs) | A tour of the plan and schedule |

---

## Files

| Folder / file | What's inside |
|---|---|
| [`Case Study/`](Case%20Study) | The full written case study (PDF) |
| [`Tableau/`](Tableau) | [Dashboard workbook](Tableau/Superstore%20Sales%20Performance.twbx) and [case study story workbook](Tableau/Superstore%20Sales%20Performance%20Case%20Study.twbx) (open in Tableau Desktop or Tableau Public) |
| [`Data/`](Data) | [`sample_superstore.xls`](Data/sample_superstore.xls) and the [data structure overview](Data/Data_Structure_Overview.md) |
| [`Images/`](Images) | Dashboard and ERD images |
| [`Project Management/`](Project%20Management) | Requirements, project plan, and WBS |

**Tools:** MySQL Workbench (cleaning and analysis) · SQL · Tableau Desktop and Tableau Public · Excel · Smartsheet

---

## My Role

**Solo project:** project manager, business analyst, Tableau developer, and QA.

- Defined the business requirements and wrote the project plan and WBS
- Cleaned and analyzed the data with SQL
- Built the dashboard and case study story in Tableau and published them to Tableau Public
- Wrote the case study with findings, recommendations, and caveats

<div align="center">

**Lashawn Fofung** · Technical Product Manager · [LinkedIn](https://www.linkedin.com/in/lashawnfofung/) · [Data Portfolio](https://github.com/LashawnFofung/Data-Analysis-Portfolio) · [All Projects](https://github.com/LashawnFofung/LashawnFofung-Portfolio)

</div>
