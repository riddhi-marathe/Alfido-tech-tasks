# Alfido Tech: Data Science & Analytics Portfolio

**Author:** Riddhi Marathe

This repository contains a collection of three end-to-end data science and machine learning projects completed as part of the Alfido Tech tasks. These projects span exploratory data analysis (EDA), predictive machine learning pipelines, and relational data manipulation to drive actionable business strategies.

---

## 🍽️ Task 1: Zomato Dataset Analysis

**Objective:** Analyze restaurant and review data to extract insights on ratings, cuisines, location preferences, and the factors affecting restaurant success. 

**Expectations:** Clean messy textual data, explore relationships (cuisine vs. rating, price vs. rating), build comprehensive visualizations (heatmaps, wordclouds), and provide 5 strategic recommendations for a food-tech platform.

**Key Results & Methodology:**

* **Data Cleaning:** Handled severe formatting inconsistencies in the pricing and rating columns by building robust `try-except` parsing functions to isolate and remove dirty textual data disguised as numeric values.
  
* **Exploratory Analysis:** Mapped out the top 15 "Location Hotspots" to identify densely populated restaurant zones.
  
* **Business Insights:** * Discovered that highly-rated food does not strictly correlate with high costs, revealing an opportunity for "Budget-Friendly Top Rated" content curation.

   * Identified dominant tastes (North Indian, Chinese) via WordCloud text analysis, recommending targeted "Cuisine Weeks" for promotional campaigns.

  * Recommended verifying exceptional restaurants based on the correlation between high vote volume and sustained ratings above 4.2.

---

## 🏦 Task 2: Loan Approval Prediction

**Objective:** Build a robust supervised machine learning pipeline to predict loan approval using borrower features, with a strong focus on risk mitigation for financial institutions.

**Expectations:** Perform rigorous data preprocessing (imputing missing values, encoding categorical variables, standard scaling), handle extreme class imbalance, and compare tree-based models with linear models using advanced classification metrics.

**Key Results & Methodology:**

* **Handling Imbalance:** Applied SMOTE (Synthetic Minority Over-sampling Technique) to artificially balance the training dataset, preventing the model from becoming biased toward the majority "Approved" class.

* **Model Comparison:** Evaluated Logistic Regression and Random Forest Classifiers.

   * *Logistic Regression:* Provided high interpretability for feature impact.

   * *Random Forest:* Handled complex, non-linear borrower behaviors with higher overall accuracy.

* **Business Strategy & Deployment:** * Evaluated success using Precision, Recall, F1-Score, and ROC-AUC.

   * **Strategic Recommendation:** Advised shifting the deployment approval threshold from the default `0.5` to `0.60 - 0.65`. This reduces immediate loan volume but significantly mitigates default risk, protecting the bank's long-term capital by strictly prioritizing high-confidence approvals.

---

## 📱 Task 3: Instagram Engagement Analysis

**Objective:** Analyze Instagram interaction data to identify optimal posting times, high-engagement content, and signals for follower growth.

**Expectations:** Parse relational tables, engineer a custom engagement metric `(Likes + Comments) / Followers`, map out a posting schedule, analyze hashtags, and draft a one-page strategy document.

**Key Results & Methodology:**

* **Relational Data Merging:** Successfully unzipped and merged a fragmented relational database (linking `photos.csv`, `likes.csv`, `comments.csv`, `follows.csv`, and `tags.csv` via primary/foreign keys) into a unified master dataframe using Pandas.

* **Feature Engineering:** Extracted temporal features (Day of Week, Hour of Day) to calculate standardized engagement rates while safely handling zero-follower edge cases.

* **Business Insights:**

   * **Algorithmic Scheduling:** Mapped out an engagement heatmap, identifying the exact hours and days where the current follower base is most active, replacing arbitrary posting with precision scheduling.

  * **Hashtag Optimization:** Programmatically extracted and tracked tag frequencies, recommending the creation of mixed "hashtag banks" to capture both broad reach and niche audiences.

  * **Follower Quality vs. Quantity:** Highlighted the mathematical importance of active interactions; since empty followers dilute the engagement score, the strategy mandates CTA-driven captions (Call-To-Actions) to foster community participation.

---

### 🛠️ Tech Stack & Libraries Used

* **Languages:** Python

* **Data Manipulation:** Pandas, NumPy

* **Data Visualization:** Matplotlib, Seaborn, WordCloud

* **Machine Learning:** Scikit-Learn (StandardScaler, LabelEncoder, LogisticRegression, RandomForestClassifier)

* **Imbalanced Data Handling:** Imbalanced-Learn (SMOTE)

* **Environment:** Google Colab, Jupyter Notebooks


Would you like me to walk you through how to add a clean, professional profile bio to your GitHub account as well?
