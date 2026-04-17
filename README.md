# Codveda-Projects
# Customer Churn Intelligence: End-to-End Predictive Pipeline
> **Domain:** Telecom / Customer Retention  
> **Technical Focus:** Data Engineering, Predictive Modeling, Behavioral Analytics

## 🚀 Executive Summary
Developed a robust predictive framework to mitigate revenue loss by identifying at-risk customers with **95% accuracy**. This project transitions business operations from reactive reporting to proactive retention by identifying behavioral "fingerprints" of churn.

---

## 🛠️ Technical Stack & Engineering Workflow

### 1. Data Engineering (The "Analytics Engineer" Layer)
* **Wrangling:** Utilized **Pandas** and **NumPy** for vectorized data cleaning and type casting.
* **Integrity:** Implemented logic to handle null values and outliers in high-variance telecom usage data.
* **Feature Engineering:** Derived new metrics including *Usage-to-Cost ratios* and *Service Call thresholds*.

### 2. Machine Learning & Analysis (The "Technical Analyst" Layer)
* **Segmentation:** Applied **K-Means Clustering** to differentiate "Power Users" from "Low Engagement" segments.
* **Modeling:** Built and compared **Random Forest Classifiers** and **Logistic Regression** models.
* **Optimization:** Conducted hyperparameter tuning via **GridSearchCV** to maximize the F1-Score and Recall.

---

## 📈 Business Insights & Results

* **Predictive Power:** Achieved **95% Accuracy** and **91% Recall**, ensuring high-risk customers are rarely missed by the model.
* **Critical Discovery:** Customers with an **International Plan** are **3x more likely to churn**, suggesting a need for plan restructuring.
* **The "Service Wall":** Identified that churn probability spikes by **60% after 4 Customer Service calls**, providing a clear trigger for immediate human intervention.
* **Segment Risk:** 15% of "Power Users" account for 40% of churn risk; targeted retention for this group offers the highest ROI.

---

## 📂 Repository Structure
* `/notebooks`: 
    * `01_Exploratory_Stats`: Statistical profiling and distribution analysis.
    * `02_Segmentation`: K-Means clustering for behavioral grouping.
    * `03_Predictive_Model`: Random Forest implementation and hyperparameter tuning.

---

## 🔧 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/Task_1_Basic_Statistics.ipynb` 'Task_3_Clustering_Analysis.iypnb' 'Task_1_Predictive_Modeling.iypnb' in Jupyter.

**Contact:** Jyothi Valluru | LinkedIn profile Link: http://www.linkedin.com/in/jyothi-valluru-b1980a3ab
