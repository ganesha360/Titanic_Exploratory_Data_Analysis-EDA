# 🛳️ Titanic Exploratory Data Analysis (EDA)

## 📘 Project Overview  
This project focuses on **Exploratory Data Analysis (EDA)** using the **Titanic dataset**.  
The goal is to understand patterns, relationships, and insights in the data through **statistical summaries and visualizations** before building any machine learning models.

---

## 🧰 Tools & Libraries Used  
- **Python**  
- **Pandas** – for data analysis  
- **NumPy** – for numerical operations  
- **Matplotlib / Seaborn** – for data visualization  
- **Plotly** – for interactive visualizations  

---

## 🧩 Steps Performed  

### 1️⃣ Generate Summary Statistics  
- Calculated mean, median, standard deviation, and count for numerical columns.  
- Checked basic info and overall dataset shape.

### 2️⃣ Visualize Numeric Features  
- Created **histograms** and **boxplots** for `Age` and `Fare` to study data distribution and outliers.

### 3️⃣ Correlation Analysis  
- Used a **heatmap** to find relationships between numerical variables like `Fare`, `Age`, and `Pclass`.

### 4️⃣ Pairplot Visualization  
- Plotted **pairwise feature relationships** to observe survival trends visually.

### 5️⃣ Feature-Level Inferences  
- Made basic interpretations from graphs (gender, class, and fare effects on survival).

---

## 📊 Visualization Samples  

| Visualization | Purpose |
|----------------|----------|
| `sns.countplot()` | Compare survival across genders or passenger classes |
| `sns.histplot()` | Show age or fare distribution |
| `sns.boxplot()` | Identify and study outliers |
| `sns.heatmap()` | Display correlation between numerical features |
| `sns.pairplot()` | Understand relationships among multiple variables |
| `px.scatter()` | Interactive plot to visualize Age vs Fare |

---

## ✅ Results  
- Clear understanding of relationships between features.  
- Identified patterns like **females and 1st class passengers having higher survival rates**.  
- Found **Fare** positively correlated with **Survival**, and **Pclass** negatively correlated.  
- Gained insights for **future feature selection** in ML models.

---

## 💾 Files Included  
- `Titanic-Dataset.csv` — Original dataset  
- `Titanic_EDA.ipynb` — EDA code and visuals  
- `README.md` — Project documentation  

---

## 📚 Learning Outcome  
From this project, I learned how to:
- Explore datasets using visual and statistical tools.  
- Identify trends, outliers, and correlations.  
- Derive meaningful insights for feature engineering.  

---

## 🧑‍💻 Author  
**Ganesh R**  
*(Junior AI/ML Engineer Trainee)*  

