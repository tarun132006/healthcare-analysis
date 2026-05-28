# 🏥 Diabetes Risk Factor Analysis
### Exploratory Data Analysis on the Pima Indians Diabetes Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.x-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-red)
![Dataset](https://img.shields.io/badge/Dataset-NIDDK-lightgrey)

---

## 📌 Project Overview

This project analyses a real clinical dataset collected by the **National Institute of Diabetes
and Digestive and Kidney Diseases (NIDDK)** to identify patterns and risk factors associated
with Type 2 diabetes in female patients of Pima Indian heritage.

The goal is not to build a machine learning model — but to deeply understand the data through
cleaning, exploration, and statistical analysis, and communicate findings through clear visuals.

---

## ❓ The Core Question

> *"What factors most strongly predict whether a patient has diabetes —
> and what patterns exist across the patient population?"*

---

## 📂 Project Structure

```
diabetes-analysis/
│
├── data/
│   └── diabetes.csv              # Raw dataset (never modified)
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb    # Load, inspect, fix data quality issues
│   ├── 02_eda.ipynb              # Exploratory analysis & questions
│   ├── 03_statistical_analysis.ipynb  # Correlations & comparisons
│   └── 04_visualizations.ipynb  # Final publication-quality charts
│
├── outputs/
│   └── charts/                   # Saved PNG plot files
│
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```

---

## 📊 Dataset

| Property      | Details                                              |
|---------------|------------------------------------------------------|
| Source        | National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) |
| Available at  | [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| Patients      | 768 female patients, aged 21 and above               |
| Features      | 8 medical attributes + 1 target column               |
| Target        | `Outcome` — 1 = Diabetic, 0 = Not Diabetic           |

**Features:** Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI,
DiabetesPedigreeFunction, Age

---

## 🔧 What I Did

### 1. Data Cleaning
- Found invalid zeros in 5 columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI)
- Insulin had the most — 374 zeros (48.7% of the dataset)
- Replaced all invalid zeros with column medians
- Saved cleaned dataset to data/diabetes_cleaned.csv

### 2. Exploratory Data Analysis
<!-- FILL IN: What questions did you ask? What did you find? -->
<!-- Example: "Diabetic patients had an average glucose of X vs Y in healthy patients" -->
- [ ] Add your findings here after Day 3 & 4

### 3. Statistical Analysis
<!-- FILL IN: What correlations did you find? Which features mattered most? -->
<!-- Example: "Glucose had the strongest correlation with Outcome (r = 0.47)" -->
- [ ] Add your findings here after Day 5

### 4. Key Visualisations
<!-- FILL IN: List your best charts and what they show -->
<!-- Example: "Correlation heatmap showing top predictors of diabetes" -->
- [ ] Add your charts here after Day 6

---

## 💡 Key Findings

<!-- FILL IN THIS SECTION LAST — after your full analysis on Day 7 -->
<!-- This is the most important part of the README for recruiters -->
<!-- Write 3-5 bullet points of the most interesting things you discovered -->

- 🔍 Finding 1: ...
- 🔍 Finding 2: ...
- 🔍 Finding 3: ...
- 🔍 Finding 4: ...
- 🔍 Finding 5: ...

---

## 📈 Sample Visualisations

<!-- FILL IN: Add your best chart images here after Day 6 -->
<!-- To add an image: ![Chart Title](outputs/charts/your_chart.png) -->

*Coming soon — charts will be added after analysis is complete.*

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/diabetes-analysis.git
cd diabetes-analysis
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Download the dataset**
   - Go to [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
   - Download `diabetes.csv`
   - Place it inside the `data/` folder

4. **Run the notebooks in order**
```
01_data_cleaning.ipynb  →  02_eda.ipynb  →  03_statistical_analysis.ipynb  →  04_visualizations.ipynb
```

---

## 🛠️ Requirements

```
numpy
pandas
matplotlib
seaborn
jupyter
```

---

## 👤 Author

**Your Name**
- GitHub: [@your_username](https://github.com/your_username)
- LinkedIn: [your_linkedin](https://linkedin.com/in/your_linkedin)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

*Dataset originally collected by the NIDDK and made available via the
UCI Machine Learning Repository.*