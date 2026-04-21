# 📊 Superstore Sales Analysis

> A professional end-to-end sales data analysis built to demonstrate
> data analytics and business intelligence skills to potential clients.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-green?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

🌐 **Idioma / Language:** English | [Español](README.es.md)

---

## 📌 Project Overview

This project analyzes **4 years of retail transaction data** (2014–2017)
from a fictional US-based superstore. The analysis covers revenue trends,
profitability by product and region, the impact of discounting, and
seasonal sales patterns.

The goal is twofold:
1. **For business owners** — deliver clear, actionable insights in plain
   language that drive better decisions.
2. **For the data analytics portfolio** — showcase a complete, professional
   workflow from raw data to business recommendations.

---

## 🔑 Key Findings

- 💻 **Technology is the star category** — it generates the highest revenue
  and the best profit margins. Expanding this category is the clearest
  growth opportunity.

- 🚨 **Discounts above 30% cause losses** — orders with discounts over
  30% generate a net loss on average. Capping discounts at 20% is the
  single highest-impact action the business can take.

- 📅 **Q4 is always the peak season** — November and December consistently
  drive the highest sales volume every single year, making early inventory
  planning and targeted Q4 marketing essential.

- 🗺️ **The West region outperforms all others** — not just in revenue, but
  in profit margin. The Central region underperforms and needs a
  discount-policy and product-mix review.

---

## 🛠️ Technologies Used

| Tool | Version | Purpose |
|------|---------|---------|
| Python | 3.10+ | Core programming language |
| Pandas | 2.0+ | Data manipulation and analysis |
| Matplotlib | 3.7+ | Base visualization library |
| Seaborn | 0.12+ | Statistical visualizations |
| OpenPyXL | 3.1+ | Excel export |
| Jupyter Notebook | 7.0+ | Interactive development environment |

---

## 📁 Project Structure

```
superstore-sales-analysis/
│
├── 📓 superstore_analysis.ipynb          # Main analysis notebook
├── 📄 README.md                          # This file
├── 📊 Sample - Superstore.csv            # Este archivo
│
├── 📈 charts/                            # Exported visualizations
│   ├── chart1_category_performance.png
│   ├── chart2_top10_products.png
│   ├── chart3_monthly_trend.png
│   ├── chart4_region_performance.png
│   ├── chart5_profitability_heatmap.png
│   ├── chart6_discount_analysis.png
│   └── chart7_yearly_growth.png
│
└── 📋 superstore_analysis_summary.xlsx   # Exported Excel report
```
---

## 🚀 How to Run the Project

### Step 1: Clone the repository
```bash
git clone https://github.com/magalanro/superstore-sales-analysis.git
cd superstore-sales-analysis
```

### Step 2: Create a virtual environment (recommended)
```bash
python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

### Step 3: Install required libraries
```bash
pip install pandas matplotlib seaborn openpyxl jupyter notebook
```

Or install from the requirements file:
```bash
pip install -r requirements.txt
```

### Step 4: Download the dataset
1. Go to [Kaggle — Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
2. Download `Sample - Superstore.csv`
3. Place it in the project root folder

### Step 5: Launch the notebook
```bash
jupyter notebook superstore_analysis.ipynb
```

### Step 6: Run all cells
In Jupyter: **Kernel → Restart & Run All**

The notebook will automatically generate all 7 charts and the Excel summary report.

---

## 📊 Visualizations Included

| # | Chart | Business Question Answered |
|---|-------|---------------------------|
| 1 | Revenue & Profit by Category | Which product category is most valuable? |
| 2 | Top 10 Products by Revenue | Which specific products drive the business? |
| 3 | Monthly Sales Trend | When do sales peak throughout the year? |
| 4 | Sales vs. Profit by Region | Which regions are most and least profitable? |
| 5 | Profitability Heatmap | Where exactly are we making or losing money? |
| 6 | Discount Impact Analysis | Are our discounts hurting profitability? |
| 7 | Year-over-Year Growth | Is the business growing sustainably? |

---

## 💼 What a Business Can Learn From This Analysis

This type of analysis answers the questions that drive real business
decisions — and it's accessible to any business owner, not just
data professionals.

### 1. Stop the bleeding from bad discounts
Many businesses discount products without tracking whether those
discounts are profitable. This analysis shows exactly at what discount
level you stop making money — and in this case, anything above 30%
is actively losing money. This insight alone could recoup thousands
of dollars per month.

### 2. Invest where the margins are best
Not all products or regions are equal. By identifying which
sub-categories and regions deliver the best return per dollar sold,
a business can redirect inventory investment, marketing spend, and
sales team focus toward what actually grows profit — not just revenue.

### 3. Plan operations around predictable seasonal patterns
When you know Q4 will always be your peak, you can prepare: hire
seasonal staff earlier, stock up inventory in September, and launch
marketing campaigns in October instead of scrambling in December.
Data makes your calendar more predictable.

### 4. Measure what matters — profit, not just sales
A common trap for growing businesses is celebrating revenue growth
while margins quietly shrink. This analysis tracks both, so you always
know whether growth is sustainable.

---

## 📬 Contact

Interested in a similar analysis for your business data?

**Marcos Galán Rodríguez**
📧 [magalanro@gmail.com](mailto:magalanro@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/marcos-galán-rodríguez-385825354)

I specialize in turning raw business data into clear, actionable
insights using Python and data visualization. Available for freelance projects.

---

## 📝 License

This project is licensed under the MIT License — see the
[LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Dataset: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) by Vivek Chavare
- Original dataset concept by Tableau's sample data
