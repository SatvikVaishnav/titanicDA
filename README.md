# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores the famous Titanic dataset to uncover patterns and insights related to passenger survival. The analysis includes data cleaning, visualization, outlier detection, and identifying variable relationships using Python libraries such as Pandas, Seaborn, and Matplotlib.

---

## 📌 Objectives

- Understand data distributions and variable types
- Identify and handle missing values
- Detect outliers and skewness
- Analyze relationships between key variables (e.g., survival vs age/class/gender)
- Generate actionable insights from the data

---

## 📂 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Files used:
  - `train.csv`

---

## 🔍 Key Steps in Analysis

### 1. 🧹 Data Cleaning
- Checked null values using `.isnull().sum()` and heatmaps
- Dropped/replaced missing values in `Age`, `Embarked`, and `Cabin`

### 2. 📊 Univariate Analysis
- Visualized distributions of `Age`, `Fare`, `Pclass`, `Survived`
- Observed right-skew in `Fare`, and normal-like distribution in `Age`

### 3. 🧪 Bivariate Analysis
- Compared survival rates across `Sex`, `Pclass`, `Embarked`
- Heatmaps to show correlation between numerical features

### 4. 📦 Outlier Detection
- Used box plots to detect outliers in `Age` and `Fare`
- Suggested log transformation for `Fare` due to extreme skew

---

## 📈 Visualizations

- Histograms, boxplots, and KDE plots for distributions
- Count plots for categorical variables vs survival
- Heatmaps for correlation

> 📸 *All plots and insights are included in the Jupyter Notebook (`titanicDA3.ipynb`)*

---

## 🧠 Key Insights

- Female passengers had a significantly higher survival rate (~75%)
- Passengers in 1st class had higher survival probability
- Children (age < 10) had better chances of survival
- Fare and Pclass showed strong influence on survival outcomes

---

## 🛠️ Technologies Use


├── titanicDA3.ipynb # Jupyter notebook with full analysis
├── README.md # Project summary and documentation
└── dataset/ # CSV files (train.csv)

---

## 👤 Author

**Satvik Vaishnav**  
[LinkedIn](https://www.linkedin.com/in/satvik-vaishnav)  
[GitHub](https://github.com/SatvikVaishnav)

---

## 📬 Feedback & Contributions

Feel free to open issues or submit PRs for improvements. Feedback is always welcome!
