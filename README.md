# EDA for Identifying High-Quality Leads in an Online Education Business


This project explores a dataset simulating the lead generation and conversion process for an online education company, **X Education**.

The goal was to analyze user behavior, lead sources, and activities to uncover what really drives conversions—and where efforts may be wasted.

---

## Objective

X Education receives a high volume of leads daily but struggles with a low conversion rate (~30%). The task was to identify which leads are most likely to convert, so the sales team can prioritize their outreach efforts.

---

## Key Insights

- **SMS Sent as Last Activity** → Leads receiving a final SMS showed the highest conversion rate.
- **High Website Engagement** → Users spending more time and making multiple visits were more likely to convert.
- **Working Professionals Convert More** → This group had a noticeably higher enrollment rate.
- **Lead Source Matters** → Referrals and the Welingak Website brought fewer leads but with high conversion quality.
- **Some Data Fields Had No Value** → Tags like "Interested in AI" or "Newspaper Article" did not correlate with conversion and were removed.

---

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn

---

## 📂 Project Structure
```yaml
lead-conversion-analysis/
│
├── EDA for Identifying High-Quality Leads in an Online Education Business   # Jupyter notebook with full analysis
├── sample_data.csv                 # Dataset sample (if needed)
└── README.md                       # Project overview and insights
````
---

## 📁 Dataset Source

This dataset is from Kaggle and simulates real lead data:
[Kaggle – Lead Scoring Dataset](https://www.kaggle.com/datasets/amritachatterjee09/lead-scoring-dataset)

To run the notebook on your machine:

1. Visit the dataset link above.
2. Download the CSV file.
3. Create a folder named `sample_data` inside the project directory.
4. Place the downloaded CSV file inside that `sample_data` folder.

Your final project structure should look like this:

```yaml
lead-conversion-analysis/
│
├── lead_conversion_EDA.ipynb       # Jupyter notebook with full analysis
├── sample_data/
│   └── Lead Scoring.csv                   # Downloaded CSV file from Kaggle
    └── Leads Data Dictionary.xls 
└── README.md                       # Project overview and instructions




