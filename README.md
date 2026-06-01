#Customer Churn Prediction & Analysis
Business Problem
Customer churn is one of the most costly challenges any subscription or service-based business faces. This project builds a predictive model to identify customers most at risk of churning — enabling businesses to intervene early and protect revenue.
As a Fundraising Analyst, I recognized that donor lapse and customer churn are the same underlying problem: understanding why engaged people disengage, and predicting who is next. This project applies that lens to telecom data to demonstrate transferable retention analytics skills across industries.

Dataset

Source: IBM Telco Customer Churn Dataset via Kaggle
Size: 7,043 customers, 21 variables
Target variable: Churn (Yes/No)


What I Did
1. Data Cleaning & Validation

Identified and corrected a data type error in the TotalCharges column (stored as text instead of numeric)
Removed 11 rows with null values created by the conversion
Encoded 16 categorical variables for modeling

2. Exploratory Data Analysis

Analyzed churn rate by contract type, tenure, monthly charges, and tenure group
Identified that month-to-month customers churn at significantly higher rates than annual or two-year contract holders
Found that churned customers had notably shorter tenure but higher monthly charges — suggesting price sensitivity without loyalty

3. Key Findings

Overall churn rate: 26.5% — roughly 1 in 4 customers left
New customers (0-12 months) churn at nearly 3x the rate of long-tenured customers — a critical early engagement gap
Higher monthly charges do not drive loyalty — churned customers actually paid more on average
Contract type is the single strongest predictor of churn, followed by service engagement indicators like online security and tech support

4. Predictive Model

Built a Logistic Regression classification model using scikit-learn
80/20 train/test split
Model accuracy: 78%
Correctly identifies 52% of at-risk customers before they churn

5. Business Recommendation
Businesses should prioritize:

Early engagement programs for 0-12 month customers — this is where churn risk is highest
Incentivizing longer contract commitments — the data clearly shows retention improves dramatically with contract length
Service adoption campaigns — customers without online security or tech support are significantly more likely to leave


Tools Used

Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
Jupyter Notebook
Kaggle


Why This Matters to Me
In my work as a Fundraising Analyst, I spent years helping nonprofit organizations understand donor behavior — identifying who was at risk of lapsing, what drove retention, and how to allocate budget across channels to maximize long-term value. This project is a direct translation of that thinking into a broader analytics context. The business problem is the same. The methodology is the same. The stakes are the same.

Project by Evelynn Stephens | LinkedIn | stephensevelynn@gmail.com
