# 🧠 Student Performance Analysis & Math Score Prediction

This project analyzes a dataset of students' performance and builds predictive models to estimate their **math scores** based on various factors such as gender, parental education, and preparation course completion.

---

## 📊 Dataset
- Source: [Datamanim Education Repository](https://github.com/Datamanim/datarepo)
- File: `StudentsPerformance.csv`
- Features include:
  - Gender
  - Race/ethnicity
  - Parental level of education
  - Lunch type
  - Test preparation course
  - Reading score
  - Writing score
  - Math score (target)

---

## 🔍 Project Steps

### 1. Data Cleaning & Preprocessing
- Checked for missing values
- Renamed columns to snake_case
- Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
- Analyzed impact of:
  - Gender on math scores
  - Preparation course on performance
  - Parental education level
- Visualized score distributions and correlations

### 3. Modeling
- **Target**: `math_score`
- **Models used**:
  - Linear Regression
  - Random Forest Regressor

### 4. Evaluation
| Model              | MAE  | R² Score |
|-------------------|------|----------|
| Linear Regression | 4.20 | 0.88     |
| Random Forest     | 4.71 | 0.85     |

---

## 🧠 Insights
- Students who completed the test preparation course scored significantly higher.
- Parental education shows a moderate effect on performance.
- Linear model performed slightly better than Random Forest in this case.

---

## 🚀 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📂 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the `StudentsPerformance.csv` file.
3. Run all cells from top to bottom.

---

## 📌 Author
- Your Name (replace with yours)
- [GitHub Profile](https://github.com/yourusername)

