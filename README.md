# 📊 Strategic Revenue Growth — E-Commerce Analytics Consulting

> **A full consulting engagement using CRISP-DM + MECE hypothesis testing to prescribe data-driven revenue strategies for an e-commerce business.**

---

## 🧭 Project Overview

| Item | Detail |
|---|---|
| **Module** | Consulting in Analytics — M10 |
| **Role** | Analytics Consultant |
| **Client brief** | Grow revenue from the current $484K baseline |
| **Dataset** | E-Commerce Sales (multi-region, multi-category) |
| **Tools** | Python · Power BI · CRISP-DM · MECE Framework |
| **Outcome** | 3 prescriptive strategies projecting **+41% revenue growth** |

---

## 🎯 Business Problem

The Head of Sales needed a structured, evidence-backed answer to one question:

> *"Where are our biggest revenue growth opportunities, and what should we do about them?"*

Rather than listing generic ideas, this engagement followed a consulting-grade methodology — building and testing MECE hypotheses against real transaction data before making any recommendations.

---

## 🏗️ Methodology

### CRISP-DM Lifecycle

```
Business        Data            Data           Modeling /      Evaluation      Deployment
Understanding → Understanding → Preparation → Analysis     → (Validate /  → Recommendations
                                                              Disprove)
```

### MECE Hypothesis Framework

Three hypotheses were designed to be **Mutually Exclusive and Collectively Exhaustive** — covering every possible revenue lever:

| # | Hypothesis | Lever | Outcome |
|---|---|---|---|
| H1 | Geographic cold spots represent untapped market opportunity | WHERE to sell | ✅ **Validated** |
| H2 | High discounts are causing revenue leakage without driving volume | HOW to price | ✅ **Validated** |
| H3 | Corporate/Home Office segments yield higher AOV than Consumer | WHO to target | ❌ **Disproved** |

> **Why H3 matters:** We expected Corporate to lead on order value — a common B2B assumption. The data showed the opposite: *Consumers have the highest AOV at $254.76*. This reversed our recommendation and is the most important finding in the engagement.

---

## 📈 Key Findings

### H1 — Geographic Analysis
Cold spots identified: Middle East & Africa ($45.9K) and South America ($46K) generate only **18% of total revenue**, compared to Europe's 38% ($137K). The gap isn't demand — it's logistics and payment infrastructure.

![Regional Sales](charts/01_regional_sales.png)

---

### H2 — Discount Elasticity
Regression analysis revealed that discounts are **not driving sales volume**, but are actively eroding profit margins:

- **Discount ↔ Revenue correlation: −0.046** (effectively zero — no uplift)
- **Discount ↔ Profit correlation: −0.141** (meaningful — every % discount bleeds margin)

![Discount Impact](charts/02_discount_impact.png)

Category-level breakdown confirms Furniture and Technology carry the highest average discounts:

![Category Discount](charts/05_category_discount.png)

---

### H3 — Segment AOV Analysis (Hypothesis Disproved)
Expected: Corporate > Consumer. Reality:

| Segment | AOV |
|---|---|
| 🏆 Consumer | **$254.76** |
| Corporate | $229.50 |
| Home Office | $211.30 |

![AOV by Segment](charts/03_aov_segment.png)

---

### Profitability Scatter
Technology shows the widest spread of below-break-even orders — directly linked to the discount findings:

![Sales vs Profit](charts/04_sales_profit_scatter.png)

---

### Revenue Projection
If the three recommendations below are implemented, quarterly revenue is projected to grow from $149K to $210K within two quarters — a **41% increase from baseline**:

![Revenue Projection](charts/06_revenue_projection.png)

---

## 💡 Strategic Recommendations

| # | Recommendation | Mechanism | Impact |
|---|---|---|---|
| 01 | **Localised Market Penetration** | DDP shipping + local payment gateways in ME&A and South America | +$90K potential |
| 02 | **Tiered Discount Strategy** | Replace flat-rate discounts with minimum-spend thresholds (e.g. free shipping above $500) | Margin recovery |
| 03 | **Executive Consumer Loyalty Tier** | High-margin product bundles targeting the highest-AOV segment ($254.76) | AOV & repeat purchase growth |

---

## 🔺 Minto Pyramid — Flow of Thinking

The full consulting argument follows the **Minto Pyramid Principle**: answer first, justify below.

![Minto Pyramid](charts/07_minto_pyramid.png)

| Layer | Content |
|---|---|
| **Governing thought** | Grow revenue from the $484K baseline |
| **Key lines (MECE)** | Geographic · Pricing · Segments |
| **Arguments** | Market gap · Entry barrier · No uplift · Profit bleed · H3 flip · AOV edge |
| **Evidence** | Python regression · Power BI dashboards · Correlation matrices · AOV analysis |
| **So what?** | 3 prescriptive strategies → +41% projected revenue |

---

## 📁 Repository Structure

```
📦 ecommerce-analytics-consulting
├── 📓 notebooks/
│   └── M10_AnalyticsConsulting_Strategic_Revenue_Growth_Analysis.ipynb
├── 📊 charts/
│   ├── 01_regional_sales.png
│   ├── 02_discount_impact.png
│   ├── 03_aov_segment.png
│   ├── 04_sales_profit_scatter.png
│   ├── 05_category_discount.png
│   ├── 06_revenue_projection.png
│   └── 07_minto_pyramid.png
├── 📂 presentations/
│   ├── PPT1_Consultant_Presentation.pdf
│   ├── PPT2_Approach_Methodology.pdf
│   └── PPT_Executive_Summary.pdf
├── 📄 requirements.txt
└── 📄 README.md
```

---

## ⚙️ How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/ecommerce-analytics-consulting.git
cd ecommerce-analytics-consulting

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebooks/M10_AnalyticsConsulting_Strategic_Revenue_Growth_Analysis.ipynb
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, aggregation |
| `matplotlib` | Custom charts and visualisations |
| `seaborn` | Regression plots and correlation analysis |
| `numpy` | Numerical computations |
| `Power BI` | Interactive dashboards and descriptive analytics |
| `CRISP-DM` | End-to-end analytical process framework |
| `MECE` | Hypothesis design and structured thinking |

---

## 📌 Skills Demonstrated

`Data Analytics` · `Business Consulting` · `Hypothesis Testing` · `CRISP-DM` · `MECE Framework` · `Revenue Analysis` · `Python` · `Power BI` · `Data Storytelling` · `Prescriptive Analytics` · `Minto Pyramid`

---

## 📬 Contact

Feel free to connect or reach out if you'd like to discuss the methodology or findings.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/YOUR_PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/YOUR_USERNAME)

---

*Module 10 — Consulting in Analytics | Mentor: Prasanna Rajappa*
