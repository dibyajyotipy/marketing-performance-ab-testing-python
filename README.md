# 📊 A/B Testing: Facebook vs AdWords Campaign Performance Analysis

## 📌 Brief Summary
A data-driven A/B testing project to compare Facebook Ads and Google AdWords campaigns and determine which platform generates higher conversions and better marketing performance using statistical hypothesis testing.

---

## 🎯 Business Problem
As a marketing agency, our goal is to maximize Return on Investment (ROI) for advertising campaigns.  
We ran two campaigns on:
- Facebook Ads
- Google AdWords

We need to determine which platform delivers better results in terms of:
- Clicks
- Conversions
- Overall effectiveness

This analysis helps optimize budget allocation and improve campaign performance.

---

## 📂 Dataset
The dataset contains **365 daily observations** of both campaigns including:

- Ad Views (Impressions)
- Clicks
- Conversions
- Cost
- CTR
- CPC
- Conversion Rate

Each row represents one day of performance.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (Hypothesis Testing)
- Jupyter Notebook

---

## 📈 Methods Used

### 1. Data Cleaning
- Removed symbols ($, %)
- Converted columns to numeric
- Checked missing values

### 2. Exploratory Data Analysis
- Summary statistics
- Distribution plots
- Histograms

### 3. Distribution & Frequency Analysis
- Conversion categories (low, medium, high)
- Comparison of daily performance

### 4. Correlation Analysis
- Relationship between clicks and conversions

### 5. A/B Testing (Hypothesis Testing)
- Independent two-sample t-test (Welch’s test)
- Compared mean conversions

---

## 🔑 Key Insights

### Conversion Performance
- Facebook mean conversions = **16.65**
- AdWords mean conversions = **31.82**

### Correlation (Clicks → Conversions)
- Facebook: 0.53 (moderate)
- AdWords: 0.37 (weak)

### Hypothesis Testing
- t-statistic = **-14.31**
- p-value < **0.05**
- Statistically significant difference

---

## ✅ Final Conclusion
AdWords significantly outperforms Facebook in generating conversions.

On average, AdWords produces nearly **2× more daily conversions**, and the difference is statistically significant rather than due to random chance.

### 📌 Business Recommendation
Allocate a larger portion of the advertising budget to **Google AdWords** to maximize ROI and conversions.

---

## ▶️ How to Run This Project

### Clone repository
git clone https://github.com/dibyajyotipy/ab-testing-marketing-campaign.git

### Install dependencies
pip install -r requirements.txt

### Run notebook
jupyter notebook notebook/ab-testing-marketing-campaign-python.ipynb

---


---

## 👨‍💻 Author
**Dibyajyoti Baruah**
Data Analyst

🔗 LinkedIn: https://www.linkedin.com/in/dibyajyoti-baruah/  
💻 GitHub: https://github.com/dibyajyotipy  
📧 Email: dbaruahwork@gmail.com

---

## ⭐ If you found this helpful
Feel free to star the repository or connect with me!
