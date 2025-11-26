# 🎮 Mobile Games A/B Testing (Cookie Cats)

## 📌 Project Overview
This project analyzes the results of an A/B test performed on the popular mobile puzzle game, **Cookie Cats**. The goal was to determine the impact of moving the first "gate" (a mechanism to pause gameplay) from **Level 30** to **Level 40** on player retention.

Using Python and statistical methods, I analyzed data from over **90,000 players** to provide a data-driven recommendation to the product team.

## 🎯 The Business Problem
* **Control Group (A):** Gate at Level 30.
* **Test Group (B):** Gate at Level 40.
* **Key Metrics:** 1-Day Retention & 7-Day Retention.
* **Question:** Should we move the gate to level 40 to improve retention?

## 🛠️ Tools & Technologies Used
* **Python:** Data manipulation and analysis.
* **Pandas:** Data cleaning and aggregation.
* **Seaborn/Matplotlib:** Visualization of distributions and retention rates.
* **Statsmodels/Scipy:** Hypothesis testing (Z-test).
* **Bootstrapping:** Robust statistical analysis for retention rates.

## 📊 Key Analysis Steps
1.  **Data Cleaning:** Removed outliers (e.g., players with unrealistic game rounds) to ensure statistical validity.
2.  **Exploratory Data Analysis (EDA):** Visualized the distribution of game rounds and checked for data balance.
3.  **Funnel Analysis:** Tracked user drop-off rates across levels to understand player behavior.
4.  **Statistical Testing:**
    * Applied **Bootstrapping** (1000 samples) to estimate the distribution of retention rates.
    * Performed a **Z-test** to calculate the p-value and statistical significance.

## 💡 Insights & Results
* **Day 1 Retention:** Showed a slight, statistically significant decrease for the test group (Gate 40).
* **Day 7 Retention:** Showed a **significant drop** in retention for the test group (18.2%) compared to the control group (19.0%) with a p-value of **0.0008**.
* **Conclusion:** Moving the gate to level 40 negatively impacts long-term player engagement. Players tend to churn more when the first break is delayed.

## 🚀 Recommendation
**Keep the gate at Level 30.** The data provides strong evidence that the current structure supports better player retention than moving it to Level 40.

---
*Feel free to star ⭐ this repository if you find it helpful!*
