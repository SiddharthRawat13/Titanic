# 🚢 Titanic Passenger Survival Dashboard Project

## 📊 Project Overview

This project provides a comprehensive analysis of the **Titanic passenger survival data** using:

* **Power BI for dashboard visualization**
* **Python (Pandas, Seaborn, Matplotlib) for EDA & feature engineering**
* **Jupyter Notebook for code transparency and reproducibility**

👉 The goal was to analyze survival patterns based on features like **gender, class, title, age group, family size**, and **embarked country**.

---

## 🧠 Key Visual Insights from Dashboard
![Titanic Dashboard Screenshot](./titanic%20db%20ss.png)

1️⃣ **Survived vs Non-Survived (Pie Chart)**
• \~38% of passengers survived, while \~62% did not.
• Offers a high-level survival overview.

2️⃣ **Survival by Gender (Donut Chart)**
• **Females** had a significantly higher survival rate (\~68%) compared to **males** (\~32%).

3️⃣ **Survival by Class (Bar Chart)**
• **First-class** passengers had the highest number of survivors (136), followed by **third-class (119)** and **second-class (87)**.

4️⃣ **Survival by Age Category (Bar Chart)**
• **Adults** had the highest number of survivors and non-survivors.
• Smaller groups like **children**, **teenagers**, and **seniors** showed unique patterns worth noting.

5️⃣ **Survival by Embarked Country (Waterfall Chart)**
• Most passengers embarked from the **UK**, followed by **France** and **Ireland**.
• French passengers had relatively higher survival ratios.

6️⃣ **Survival by Title (Bar Chart)**
• Titles like **'Miss'**, **'Mrs'**, **'Mr'**, and **'Boy'** reveal survival disparities — showcasing how **social status** influenced outcomes.

7️⃣ **Survival by Age Groups (Bar Chart)**
• Survival trends across **age bands** (e.g., 0–10, 21–30, 31–40) highlight risk levels for different life stages.

8️⃣ **Survival by Family Size (Line/Bar Chart)**
• Passengers with **1–3 family members** had better chances of survival.
• Those **traveling alone** or with **larger families** had lower survival rates.

---

## 🔗 Project Links

* 📁 **[Raw Dataset](https://www.kaggle.com/competitions/titanic/data)** (Kaggle)
* 📊 [Power BI Dashboard (Hosted powerbi workspace)](https://app.powerbi.com/groups/me/reports/b74902d9-008d-4619-bb0d-db98e56b138e/98b7953f60da000006b7?experience=power-bi)
* 📄 **[Jupyter Notebook - EDA & Feature Engineering]([link_to_your_notebook_in_repo](https://github.com/SiddharthRawat13/Titanic-survival-dashboard/blob/main/titanic_jupyter_code.ipynb))**

---

## 🧪 Exploratory Data Analysis (EDA)

The EDA was done using **Pandas, Seaborn, and Matplotlib** in Jupyter Notebook. Key steps included:

* Checking for missing values
* Filling missing values (age, embarked)
* Visualizing feature distributions
* Analyzing survival correlations

📸 **Jupyter EDA Screenshots**:

```markdown
![Age Distribution](./images/age_distribution.png)
![Survival by Class](./images/survival_class.png)
![Correlation Heatmap](./images/correlation.png)
```

---

## 🛠 Feature Engineering

To prepare the data for modeling and insights:

* Extracted **Title** from Name column (Mr., Mrs., etc.)
* Created **Family Size** column
* Binned **Age** into categories (child, teenager, adult, senior)
* Encoded **categorical variables**

📘 *These steps are documented with code and explanations in the Jupyter notebook.*

---

## 🗂 Files Included in Repository

| File/Folder                    | Description                                                       |
| ------------------------       | ----------------------------------------------------------------- |
| `titanic_raw_data.csv`         | Original Titanic dataset from Kaggle                              |
| `titanic clean dataset utf.csv`| Cleaned version after preprocessing                               |
| `titanic_jupyter_code.ipynb`   | Jupyter notebook with data cleaning, EDA, and feature engineering |
| `Titanic Dashboard.pbix`       | Power BI report file                                              |
| `titanic db ss.png`            | Power BI dashboard screenshot                                     |
| `README.md`                    | This file                                                         |

---

## ✅ Skills Demonstrated

* 📊 Data Visualization (Power BI)
* 🐍 Python (Pandas, Seaborn, Matplotlib)
* 🔍 EDA & Data Cleaning
* 🧱 Feature Engineering
* 📁 Dashboard Design for Business Understanding

---

## 💼 Why This Project Matters.

This project showcases:

* The **end-to-end data analytics lifecycle**
* **Clear storytelling** through dashboards
* **Business-relevant KPIs** extracted from real-world data
* Ability to **communicate insights visually and technically**

---

