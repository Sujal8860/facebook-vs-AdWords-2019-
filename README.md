# 📊 A/B Testing & Regression Analysis — Marketing Campaign Performance

This project analyzes and compares the performance of two ad platforms — **Facebook Ads** vs **Google AdWords** — to answer a key business question:

> **Which ad platform drives more conversions and is more cost-effective?**

It covers the full analytics workflow from raw marketing data to actionable insights and predictions.

---

## 🚀 Project Overview

* **Business goal**: Help a marketing agency decide where to invest more ad spend by comparing Facebook and Google AdWords campaigns.
* **Key questions**:

  * Which platform converts better (A/B testing)?
  * How do ad clicks relate to conversions (Regression Analysis)?
  * What are the cost efficiency metrics (CPC, CPA, CTR)?

---

## 🛠️ Steps Performed

1. **Data Cleaning & Preparation**

   * Converted cost & percentage columns to numeric values.
   * Handled missing/invalid data and standardized column types.

2. **Exploratory Data Analysis (EDA)**

   * Checked data distributions.
   * Compared key metrics — daily clicks, conversions, CTR, CPC, CPA.
   * Created monthly trend visualizations.

3. **A/B Testing (Hypothesis Testing)**

   * Tested if **Facebook Ads** lead to significantly more conversions than **AdWords** using **Welch’s t-test** (one-tailed).
   * **Result**: p-value ≈ 0, strongly rejecting the null — Facebook outperforms AdWords in conversions.

4. **Regression Analysis**

   * Built a **simple linear regression** to predict Facebook conversions based on clicks.
   * Model R² ≈ **0.76** — Facebook ad clicks explain ~76% of conversion variation.
   * Added prediction intervals to estimate future performance.

---

## 📈 Key Insights

* Facebook Ads consistently deliver **higher conversions** and more **cost-effective results** (lower CPA) compared to AdWords.
* Regression shows a **positive relationship** between clicks and conversions — more clicks usually mean more sales.
* Current model has **76% explanatory power** — good for a first iteration. Advanced modeling (feature engineering, scaling, multiple regression) could improve this.

---

## 💡 Future Improvements

* Explore **multiple regression** by adding more predictors (CTR, cost per click, weekday/seasonality).
* Feature scaling or polynomial terms to improve prediction accuracy.
* A/B test different ad creatives or time segments for deeper insights.

---

## 🛠️ Tech & Libraries

`Python` • `Pandas` • `Matplotlib` • `Seaborn` • `SciPy` • `Scikit-learn` • `Statsmodels`

---

## 🏆 Author’s Note

This is my **first A/B testing & regression project** — the aim was to understand the full analysis pipeline rather than perfect the model. R² = ~76% was considered sufficient for a first pass; future projects will aim for deeper feature engineering and model tuning.

---

## 📬 Connect & Feedback

If you have suggestions to improve this analysis or want to discuss marketing data analytics, let’s connect!
gmail- priyambarman28@gmail.com

