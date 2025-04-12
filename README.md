# 🚢 Titanic Survival Prediction

This project uses **Logistic Regression** to predict the survival of passengers aboard the Titanic, based on features like age, gender, passenger class, and more. It’s a classic beginner project in data science and machine learning.

---

## 📁 Dataset
- [Titanic dataset on Kaggle](https://www.kaggle.com/competitions/titanic/data)

---

## 🧰 Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn (for data visualization)
- Scikit-learn (for model and preprocessing)

---

## 🔍 Data Exploration & Cleaning
- Count plots for survival and gender-wise analysis
- Handled missing values (`Age`, `Embarked`)
- Dropped irrelevant columns like `Cabin`, `Name`, and `Ticket`

---

## 🔄 Preprocessing
- Replaced missing values using mean (for `Age`) and mode (for `Embarked`)
- Converted categorical columns like `Sex` and `Embarked` to numeric values
- Applied `StandardScaler` for feature scaling (Z-normalization)

---

## 📊 Model Used
- **Logistic Regression**
- Data split into training and testing sets (80/20)
- Used `random_state=42` for reproducibility
- Evaluated model using accuracy score

---

## ✅ Results
- Achieved good accuracy on both training and test sets
- Model learned survival patterns based on input features

---

## 🚀 How to Run
1. Clone this repo or download the notebook
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the Jupyter Notebook and run all cells

---

## 📌 Future Ideas
- Try other models: Decision Trees, Random Forest, etc.
- Use cross-validation for better evaluation
- Tune hyperparameters for improved accuracy

---

## 📚 Key Learnings
- Data cleaning and feature selection
- Categorical data handling
- Logistic Regression modeling
- Model evaluation using `accuracy_score`
