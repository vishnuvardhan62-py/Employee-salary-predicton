# 🧑‍💼 Employee Salary Prediction

This is a machine learning web application built with **Streamlit** that predicts an employee's salary category (`<=50K` or `>50K`) based on demographic and work-related features. The model is trained using the UCI Adult dataset.

---

## 📦 Files Included

- `app.py` – Streamlit application file  
- `adult 3.csv` – Raw dataset (original UCI data)  
- `cleaned_adult.csv` – Cleaned and preprocessed dataset  
- `model.pkl` – Trained machine learning model (if available)  
- `model_columns.pkl` – Expected input features for the model  
- `README.md` – Project documentation  

---

## 🚀 Features

✅ Predicts salary category based on user inputs  
✅ Clean Streamlit UI for interaction  
✅ Uses a trained ML model for real-time prediction  
✅ Handles both categorical and numerical inputs

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/employee-salary-prediction.git
   cd employee-salary-prediction


2. **Install the dependencies**

   ```bash
   pip install streamlit pandas numpy scikit-learn joblib
   ```

3. **Run the application**

   ```bash
   streamlit run app.py
   ```

---

## 📊 About the Dataset

* **Source**: UCI Machine Learning Repository

* **Total Rows**: 32,000+

* **Features**:

  * Age, Education, Occupation, Workclass
  * Marital Status, Relationship, Race, Gender
  * Hours-per-week, Native Country, etc.

* **Target Variable**:

  * Salary: `<=50K` or `>50K`

---

## 🧠 Model Info

* Model: Logistic Regression / Random Forest / Decision Tree
* Libraries used: `scikit-learn`, `pandas`, `numpy`, `joblib`
* Trained on preprocessed dataset (`cleaned_adult.csv`)
* Saved using `joblib` for fast loading in the app

---

## 🎯 How to Use

1. Launch the app using `streamlit run app.py`
2. Enter details like age, education, workclass, etc.
3. Click **Predict**
4. See the predicted salary category instantly

---

## 📄 License

This project is licensed under the MIT License.
Feel free to use, modify, and share.
