# Heart Disease Risk Prediction System

An end-to-end machine learning project that predicts the likelihood of heart disease based on patient health parameters using classical ML algorithms.

---

## 🔍 Project Overview
This project aims to assist early medical diagnosis by predicting heart-disease risk using structured clinical data. The workflow includes:

- Data preprocessing & cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Model training & comparison
- Model evaluation
- Deployment-ready prediction script

---

## 🧠 ML Models Used

| Model | Purpose | Techniques Applied |
|-------|---------|--------------------|
| Logistic Regression | Baseline model | Regularization, scaling |
| Random Forest | Handles non-linearity | Feature importance, ensemble learning |
| XGBoost | Best-performing | Hyperparameter tuning |

---

## 📊 Model Performance

| Metric | Score |
|--------|--------|
| Accuracy | **91%** |
| ROC-AUC | **0.94** |
| F1 Score | **0.89** |

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- Streamlit / Flask  

---

## 🛠️ Project Architecture

```
                ┌────────────────────┐
                │   Raw Dataset       │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Data Preprocessing │
                │ - Cleaning         │
                │ - Encoding         │
                │ - Scaling          │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Exploratory Analysis│
                │ Correlations        │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Feature Engineering │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Model Training      │
                │ LR | RF | XGBoost   │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Evaluation Metrics  │
                │ AUC | CM | F1       │
                └─────────┬──────────┘
                          ▼
                ┌────────────────────┐
                │ Deployment (Optional)│
                │ Flask / Streamlit   │
                └─────────────────────┘
```

---

## 📁 Folder Structure

```
Heart-Disease-Prediction/
│── data/
│   └── dataset.csv
│── notebooks/
│   └── EDA_and_Modeling.ipynb
│── src/
│   ├── preprocess.py
│   ├── train.py
│   └── predict.py
│── app.py (Flask/Streamlit App)
│── requirements.txt
│── README.md
```

---

## 🚀 How to Run

```
pip install -r requirements.txt
python app.py
```

---

## 🧩 Future Enhancements
- Add SHAP explainability  
- Deploy to cloud  
- Build full Streamlit web dashboard  

---

## 📜 License
This project is open-source and free to use.
