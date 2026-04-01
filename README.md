# 🍷 Wine Quality Prediction using Machine Learning

> 🚀 A machine learning project that predicts the quality of wine based on physicochemical properties using advanced regression techniques.

---

## 📌 Overview

Wine quality assessment is traditionally a subjective process performed by experts. This project leverages **machine learning algorithms** to automatically predict wine quality based on measurable chemical features.

The model is trained on real-world data and aims to provide **accurate, scalable, and data-driven predictions**, reducing human bias and effort.

---

## 🎯 Objectives

- Predict wine quality using physicochemical attributes  
- Build a high-accuracy regression model (target ≥ 90%)  
- Analyze feature importance affecting wine quality  
- Provide a scalable ML pipeline for real-world applications  

---

## 📂 Dataset

- Dataset: **Wine Quality Dataset (WineQT.csv)**

### Features:
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

### Target:
- `quality` (score ranging typically from 3–8)

---

## ⚙️ Tech Stack

- **Language:** Python 🐍  
- **Libraries:**
  - NumPy  
  - Pandas  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  
- **Environment:** Jupyter Notebook  

---

## 🧠 Machine Learning Approach

### 🔹 Data Preprocessing
- Handling missing values  
- Feature scaling (Standardization)  
- Train-test split  

### 🔹 Models Used
- Linear Regression  
- Random Forest Regressor (Primary Model)  
- Gradient Boosting (Optional)  

### 🔹 Evaluation Metrics
- R² Score  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

---

## 📊 Results

| Metric | Value |
|--------|------|
| R² Score | ~90%+ |
| RMSE | Low |
| Best Model | Random Forest |

✅ The model achieved strong predictive performance with minimal error.

---

## 📈 Key Insights

- Alcohol and sulphates positively impact wine quality  
- High volatile acidity reduces quality  
- Feature selection improves model performance  

---

## 🖥️ Project Structure


Wine-Quality-Prediction/
│
├── data/
│ └── WineQT.csv
│
├── notebooks/
│ └── wine_quality_prediction.ipynb
│
├── models/
│
├── README.md
└── requirements.txt


---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/wine-quality-prediction.git
cd wine-quality-prediction
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Notebook
jupyter notebook
🔍 Example Prediction
# Example input
sample = [[7.4, 0.7, 0.0, 1.9, 0.076, 11, 34, 0.9978, 3.51, 0.56, 9.4]]

prediction = model.predict(sample)
print("Predicted Wine Quality:", prediction)
🌟 Features
✔ High accuracy ML model
✔ Clean ML pipeline
✔ Real-world dataset
✔ Easy to extend and deploy
✔ Beginner-friendly + industry-ready
📌 Future Improvements
Deploy as a web app (Flask / Streamlit)
Add deep learning models
Hyperparameter tuning
Build REST API for predictions
🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Eswar Naidu
AI & ML Enthusiast | Developer
