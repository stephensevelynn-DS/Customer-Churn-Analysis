# Customer Churn Prediction & Analysis
 ![Project Thumbnail]churn_thumbnail.jpg
## Business Problem
Customer churn is one of the most costly challenges any subscription or service-based business faces. This project builds a predictive model to identify customers most at risk of churning — enabling businesses to intervene early and protect revenue.
 
As a Fundraising Analyst, I recognized that donor lapse and customer churn are the same underlying problem: understanding why engaged people disengage, and predicting who is next. This project applies that lens to telecom data to demonstrate transferable retention analytics skills across industries.
 
---
 
## Dataset
- **Source:** IBM Telco Customer Churn Dataset via Kaggle
- **Size:** 7,043 customers, 21 variables
- **Target variable:** Churn (Yes/No)
 
---
 
## Key Findings
 
| Finding | Detail |
|---|---|
| Overall churn rate | 26.5% — roughly 1 in 4 customers left |
| Highest risk group | 0-12 month customers churn at nearly 3x the rate of long-tenured customers |
| Spend vs loyalty | Churned customers paid more on average — higher charges do not drive retention |
| Top churn predictor | Contract type — month-to-month customers are significantly more likely to leave |
 
---
 
## Predictive Model
 
| Metric | Result |
|---|---|
| Model type | Logistic Regression |
| Train/test split | 80/20 |
| Overall accuracy | 78% |
| Churn detection rate | 52% of at-risk customers correctly identified |
 
---
 
## Top Predictors of Churn
 
| Feature | Importance | Business Meaning |
|---|---|---|
| Contract type | 0.77 | Month-to-month = highest risk |
| Phone service | 0.51 | Service adoption signals loyalty |
| Senior citizen | 0.33 | Different retention needs |
| Online security | 0.32 | Low service adoption = higher churn |
| Tech support | 0.31 | Engagement indicator |
 
---
 
## Business Recommendations
1. **Early engagement programs** for 0-12 month customers — this is where churn risk is highest
2. **Incentivize longer contract commitments** — retention improves dramatically with contract length
3. **Service adoption campaigns** — customers without online security or tech support are significantly more likely to leave
 
---
 
## Tools Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Kaggle
 
---
 
## Why This Matters
In my work as a Fundraising Analyst, I spent years helping nonprofit organizations understand donor behavior — identifying who was at risk of lapsing, what drove retention, and how to allocate budget across channels to maximize long-term value. This project is a direct translation of that thinking into a broader analytics context. The business problem is the same. The methodology is the same. The stakes are the same.
 
---
 
*Project by Evelynn Stephens | [LinkedIn](https://www.linkedin.com/in/evelynn-stephens-datascience/) | stephensevelynn@gmail.com*
