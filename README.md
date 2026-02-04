# 🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This project demonstrates **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset from Kaggle. It is part of Task 2 of a Data Science learning track.

---

## 📌 Objective

- Perform data cleaning to handle missing values and remove irrelevant or duplicate data.
- Conduct exploratory data analysis (EDA) to uncover patterns and insights using visualizations.

---

## 📁 Dataset

The dataset used is the **Titanic Dataset** from Kaggle:  
[Titanic-Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🧹 Data Cleaning Steps

- Filled missing `Age` values with the median.
- Filled missing `Embarked` values with the mode.
- Dropped the `Cabin` column due to excessive missing values.
- Removed duplicate rows.

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created using Seaborn and Matplotlib:

1. **Survival Count** – How many passengers survived.
2. **Survival by Gender** – Comparing survival rates of males and females.
3. **Age Distribution by Survival** – Age histogram with survival split.
4. **Passenger Class vs Survival** – Class-based survival distribution.
5. **Correlation Heatmap** – Correlation between numerical features.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas 📊
- Seaborn 🎨
- Matplotlib 📈
- Jupyter Notebook

---

## 📸 Example Plots

| Survival Count | Survival by Gender |
|----------------|--------------------|
| ![Survival](images/survival_count.png) | ![Gender](images/survival_gender.png) |

_Add plot images here if available in `/images` folder._

---

## 💡 Insights

- Females had a much higher survival rate than males.
- 1st class passengers were more likely to survive.
- Younger passengers had a slightly higher survival rate.

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Suleman2004k/titanic-eda.git
   cd titanic-eda
