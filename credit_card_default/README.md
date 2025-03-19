### 🏦 Credit Card Default Prediction using Machine Learning  

---

### 📌 Overview  
This project predicts whether a credit card user will **default** on their monthly payment based on financial attributes like **balance, income, and student status**. Using **Logistic Regression and Linear Discriminant Analysis (LDA)**, we build a classification model to assess credit risk.  

---

### 🚀 Technologies Used  
- **Python** 🐍  
- **Scikit-learn** – Machine Learning models  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Statsmodels** – Statistical analysis  
- **Jupyter Notebook** – Development environment  

---

### 📂 Dataset  
The dataset consists of **10,000** records of credit card users, including:  
✅ **Features:**  
   - `balance` – Monthly credit card balance  
   - `income` – Annual income of the customer  
   - `student` – Whether the customer is a student (`Yes`/`No`)  

✅ **Target Variable:**  
   - `default` – Whether the customer defaulted (`Yes`/`No`)  

---

### ⚙️ Installation & Setup  
#### 1️⃣ Clone the repository  
```bash
git clone https://github.com/YourRepo/Credit-Card-Default-ML.git  
cd Credit-Card-Default-ML  
```
#### 2️⃣ Install dependencies  
```bash
pip install -r requirements.txt  
```
#### 3️⃣ Run the model  
```bash
python main.py  
```

---

### 📊 Model Training & Evaluation  
🔹 **Preprocessing:** Convert categorical variables (`student`, `default`) into numeric values (`0/1`), handle missing values, and scale features if necessary.  
🔹 **Training:**  
   ✅ Logistic Regression – Baseline model  
   ✅ Linear Discriminant Analysis (LDA) – Alternative approach  
   ✅ Confounding analysis – Comparing student and non-student default rates  

🔹 **Evaluation Metrics:**  
✅ Accuracy: **95.8%**  
✅ Precision & Recall  
✅ Confusion Matrix  

---

### 🔥 Results  
The Logistic Regression model achieved **95.8% accuracy**, effectively predicting credit card defaults. The LDA model provided similar results but was useful in understanding class separation.  

---

### 💡 Future Enhancements  
🚀 Use **Random Forest or XGBoost** for improved classification  
🚀 Implement **hyperparameter tuning** for better performance  
🚀 Handle class imbalance using **SMOTE or weighted classes**  
🚀 Deploy as a **web application** using Flask or Streamlit  

---

### 📜 License  
This project is licensed under the **MIT License**.  
