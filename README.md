# Foodelicious Growth Opportunity Analysis 🍎📈

This project explores customer transaction data from a fictional national grocery chain, **Foodelicious**, to identify revenue growth opportunities using data wrangling and exploratory data analysis.

## 📌 Objective

To find an underperforming area of the business that could benefit from targeted investment. We investigated whether specific demographics are under-engaged with health-related product categories.

## 💡 Business Question

> Why is the 55+ age demographic generating significantly less revenue in health-related categories, and what can we do to improve engagement and sales?

## 🧠 Methodology

- Imported and wrangled datasets from the `completejourney_py` package
- Joined transactions, products, and demographic data
- Explored product sales by age group
- Aggregated and visualized total sales in key categories (e.g., vitamins)
- Proposed actionable strategies to address gaps

## 📊 Key Findings

- The **55+ demographic** has the **lowest sales in vitamin-related products**
- Despite likely demand, sales are weak — indicating an engagement/marketing gap
- Bar charts and summaries support a clear opportunity to target this group

## ✅ Recommendations

- Launch **senior citizen discounts** or personalized coupons
- Run **targeted advertising campaigns** for health categories
- Improve **in-store placement** and accessibility for this demographic

## 📁 Files

- `Foodelicious_GrowthOpportunity_Analysis.ipynb` – Full analysis notebook
- `Foodelicious_GrowthOpportunity_Analysis.pdf` – Exported report
- `README.md`, `.gitignore`, `LICENSE`

## 🛠️ Tools Used

- Python (pandas, matplotlib)
- `completejourney_py` package
- Jupyter Notebook

## 👥 Team

Group 7 – BANA7025  
Author: Your Name

## 📄 License

This project is licensed under the MIT License.

---

## 📦 Dataset Source

This project uses the [Complete Journey dataset](https://bradleyboehmke.github.io/completejourney/index.html), a realistic retail transaction dataset commonly used for retail analytics projects.

You can install and access the dataset using the `completejourney-py` Python package:

```bash
pip install completejourney-py
```

Example usage in Python:

```python
from completejourney_py import get_data

data = get_data()
transactions = data["transactions"]
promotions = data["promotions"]
```

This dataset includes household-level transactions, product metadata, demographic information, and promotional campaigns.