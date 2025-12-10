# 🚢 Titanic Survival Prediction
A complete Machine Learning project that predicts the survival of passengers aboard the Titanic using end-to-end data analysis, feature engineering, and multiple ML models.  
This project is built to demonstrate clean ML workflow, professional documentation, and production-ready structure — suitable for industry and AI/ML engineer roles in Europe.

---

## ⭐ Project Highlights
- Complete EDA with professional graphs  
- Feature Engineering & Data Cleaning  
- Multiple ML models tested  
- Best model saved as `.pkl`  
- Industry-style folder structure  
- MIT License included  
## 📂 Project Structure

├── data/ # Raw dataset (optional)
├── images/ # All plots and visualizations
├── titanic_model.pkl # Saved ML model
├── titanic.ipynb # Main notebook
└── README.md

## 📌 Project Features

### ✔ Data Preprocessing
- Handling missing values  
- Dropping irrelevant columns  
- Label Encoding categorical features  
- Train-test split  
- Feature scaling (optional)

### ✔ Machine Learning Model
Model Used → **Logistic Regression**

Why Logistic Regression?
- Works well for binary classification  
- Fast & interpretable  
- Gives probability of survival  

### ✔ Evaluation Metrics
The model is evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 📊 Visualizations (EDA)

Some visualizations included in this project:

- Age distribution  
- Survival count by gender  
- Passenger class and survival  
- Fare vs Age scatter plot  
- Correlation heatmap  
- Feature importance 

## 📈 Model Performance

Sample metrics:

Accuracy: ~80%
Precision: 0.76
Recall: 0.74
F1 Score: 0.75

## 💾 Saving the Model

The trained model is saved using pickle:

```python
import pickle
with open("titanic_model.pkl", "wb") as f:
    pickle.dump(model, f)


    
🚀 How to Run
Clone this repository

Install dependencies:

nginx
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn
Open the Jupyter Notebook:

nginx
Copy code
jupyter notebook
Run all cells

🎯 Key Learnings
Through this project, I learned:

Data cleaning

How logistic regression works

How ML models make predictions

Working with probabilities

Understanding evaluation metrics

Building end-to-end ML pipelines
