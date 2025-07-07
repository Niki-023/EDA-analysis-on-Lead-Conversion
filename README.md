# EDA for Identifying High-Quality Leads in an Online Education Business

This project explores a real-world-style dataset simulating the lead generation and conversion process for an online education company, **X Education**.

The aim was to analyze lead behavior, sources, occupation, and engagement patterns to discover what **truly drives conversions** — and where time and effort might be wasted.

---

##  Objective

X Education receives a high volume of leads daily, but the conversion rate remains around **30%**.  
The business challenge was to:

- **Identify which leads are most likely to convert**
- Help the sales team prioritize their outreach efforts
- Work toward increasing the conversion rate closer to **80%**

---

##  Key Insights

- **SMS Sent as Last Activity**  
  Leads whose last recorded activity was an SMS had the highest conversion rate — even more than emails or page visits.  
  _Direct, simple communication often works better than automated campaigns._

- **High Website Engagement**  
  Users who spent more time and visited the website frequently were more likely to convert.  
  _Engaged users = serious intent._

- **Working Professionals Convert More**  
  Among all occupations, working professionals had the highest conversion rate — likely due to career focus and financial independence.

- **Lead Source Matters**  
  Leads from referrals and the Welingak website showed much higher conversion quality than those from generic ad campaigns.

- **Irrelevant Fields Found**  
  Tags like _"Interested in AI"_ or _"Newspaper Article"_ had no predictive value. These were removed to improve clarity and reduce noise in the model.

---

##  Tools & Technologies Used

- **Language:** Python  
- **Notebook:** Jupyter  
- **Libraries:** Pandas, Matplotlib, Seaborn

---

## 📁 Dataset Source

The dataset used in this project is publicly available on Kaggle:  
🔗 [Kaggle – Lead Scoring Dataset](https://www.kaggle.com/datasets/amritachatterjee09/lead-scoring-dataset)

###  To Run This Project Locally:

1. Visit the Kaggle link above and download the dataset.
2. Create a folder named `sample_data` in your project directory.
3. Place the following files inside that folder:
   - `Lead Scoring.csv`
   - `Leads Data Dictionary.xls`
4. Open the Jupyter Notebook and run it step by step.

---

## 📂 Project Structure

```yaml
EDA-analysis-on-Lead-Conversion/
│
├── sample_data/
│   ├── Lead Scoring.csv            # Downloaded CSV file from Kaggle
│   └── Leads Data Dictionary.xls   # Data dictionary provided with the dataset
│
├── EDA for Identifying High-Quality Leads in an Online Education Business.ipynb
│                                   # Jupyter notebook with full analysis
│
└── README.md                       # Project overview and insights
