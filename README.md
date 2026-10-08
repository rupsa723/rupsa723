# Hi, I'm Rupsa 👋

**Data analyst in Bengaluru.** I take a business question from raw data through to a
recommendation someone can act on, with a cost or a return attached to it.

Master's in Applied Mathematics. Every project below follows the same discipline:
understand the problem first, then query, clean, analyse, visualise, and tell the
story clearly.

📧 rupsachaudhuri9@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/rupsa-chaudhuri/)

---

## 🛠 What I Work With

| | |
|---|---|
| **Query** | MySQL · Google BigQuery · DuckDB · Azure SQL — window functions, CTEs, UDFs |
| **Analysis** | Python — pandas, matplotlib, seaborn, scikit-learn |
| **Visualisation** | Power BI — DAX, data modelling, storytelling dashboards |
| **Workflow** | SQL → Python → Power BI → Presentation |

---

## 📂 Featured Projects

### 📊 GA4 Funnel Analysis — Where Is the Funnel Leaking?
`BigQuery` `SQL` `Power BI` `Marketing Analytics`

Three months of real GA4 event data from the Google Merchandise Store — **4.3 million
events across 92 days**, reshaped into visit and product tables in BigQuery. The
questions: where does the funnel lose people, and what is each channel actually worth?

- **The biggest revenue channel turned out not to be a channel.** 92% of Self-Referral's
  $120,125 is the store crediting visits to itself across its own hostnames — roughly a
  third of all revenue credited to traffic it already had
- **The funnel was counting the wrong thing.** 41% of orders finish something started on
  an earlier visit, a 2,000-order gap between the same-visit path and the real one
- Ranked the drop-off points by what fixing each one is worth rather than by size: one
  point at Add to Cart returns **246 orders against View Item's 223**, even though View
  Item loses four times as many sessions
- The second visit is the single biggest opportunity — people who come back once buy at
  **3.10% against 0.48%** and are worth **7.4x more**
- Reported three problems found in the data itself, including revenue that stopped being
  recorded from 26 January while orders kept coming through

→ 360,129 sessions · 4,848 orders · $362K revenue · 15 SQL files · 44 DAX measures · 4-page dashboard

🔗 **[View Project](https://github.com/rupsa723/ga4-funnel-analysis)**

---

### 👥 HR Attrition Analysis — From a 34% Crisis to a Retention ROI Tool
`Python` `SQL (DuckDB)` `Power BI` `Cost Modelling`

A company was losing **1 in 3 employees a year** — more than double the healthy
benchmark. I traced it to root causes, costed it, and turned it into an interactive
tool a leadership team could actually use.

- **$762,620 a year in turnover cost, and 93.5% of it never appears in the HR budget**
  — the cost of roles sitting empty rather than recruiting spend
- Underpaying doesn't save money: two technicians paid $0.42/hr below the minimum for
  their grade cost **17x more to replace than to fix** ($874/yr vs ~$14,800 each)
- Built a **live what-if calculator** — the recommended plan keeps 9 of 47 at-risk staff
  and returns 59% (up to 199% at the optimistic end)
- During checking I caught a date-parsing bug that had quietly corrupted a third of the
  age data and flipped a key finding — found, fixed, documented

→ 4 linked datasets · replacement-cost model · risk-of-leaving scoring · 4-page interactive dashboard

🔗 **[View Project](https://github.com/rupsa723/hr-attrition-analysis)**

---

### 🛒 RFM Customer Segmentation — Who's Worth Keeping?
`Python` `SQL` `Power BI` `Retail CRM`

A grocery chain had 2.6M transactions and no idea who its best customers were —
everyone got the same coupons. I ranked 2,500 households by how recently, how often and
how much they shop, using Dunnhumby's Complete Journey data, to find who's worth keeping
and who has already gone.

- **The top group is 20.5% of customers but brings 45.8% of revenue** — and the business
  had no record of who they were
- Coming back matters more than spending big: the top group spends *less* per trip
  ($29.28 vs $35.95) but came back 246 times over two years
- **42.7% of households are slipping away**, while 60.7% of coupons go to customers who
  already shop every two days — and 916 households have never been sent a single offer
- Rebuilt the whole calculation in a SQL database organised in three layers, then checked
  every number against the original Python version before connecting the dashboard to it

→ 2.6M transactions · 8 segments · demographic + campaign overlay · 4-page dashboard

🔗 **[View Project](https://github.com/rupsa723/Dunnhumby-RFM-segmentation)**

---

### 🚗 India EV Market Analysis — Which Segment Should You Enter?
`MySQL` `Python` `Power BI` `Market Strategy`

India sold 2M EVs in FY2022–FY2024, a 4x jump — yet 95 of every 100 vehicles sold is
still not electric. I used 3 Vahan Sewa government datasets to find where a new entrant
should play.

- The case for **cars is stronger than most assume**: they grew 116% a year against 92%
  for two-wheelers, and brought 62% of EV revenue on a fraction of the volume
- **Karnataka beats Delhi on two-wheeler uptake** (11.57% vs 9.40%) despite smaller
  subsidies, which points to real demand mattering more than government support
- The market is early enough that competition is still beatable

→ 10 SQL queries · 5 Python charts · 4-page dashboard · 2030 state-level projections

🔗 **[View Project](https://github.com/rupsa723/India_EV_Market_Analysis)**

---

## 📁 More Projects

- **[Retail Sales Analysis](https://github.com/rupsa723/RetailSales-Analysis)** `Python` `Power BI` — behaviour, trends, campaign effectiveness, segmentation
- **[Retail Analytics — Chip Category](https://github.com/rupsa723/Retail-Analytics)** `Python` `Jupyter` — buying habits surfaced from transaction data
- **[Customer Churn Analysis](https://github.com/rupsa723/Customer-Churn-Analysis)** `Power BI` — churn patterns + retention strategy
- **[Website Performance Analysis](https://github.com/rupsa723/Website-Analysis)** `Power BI` — gap analysis + improvement plan for e-commerce
- **[ATM Transaction Analysis](https://github.com/rupsa723/ATM-Transaction-Analysis)** `Power BI` — usage patterns + service opportunities
- **[Call Center Dashboard](https://github.com/rupsa723/call-center-dashboard)** `Power BI` — performance metrics

---

## 🤝 Let's Connect

💼 [LinkedIn](https://www.linkedin.com/in/rupsa-chaudhuri/) · 📧 rupsachaudhuri9@gmail.com
