# Estimation of Obesity Levels – Complete ML Pipeline  
## README.md

## 📘 Project Overview  
This project provides a complete, end‑to‑end Machine Learning pipeline for the **Estimation of Obesity Levels dataset (UCI ID: 544)**.  
It includes data loading, preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, hyperparameter tuning, and final evaluation — all in a single reproducible Google Colab notebook.

---

## 📂 Project Structure
- `notebook.ipynb` — Complete technical implementation (Python)
- `requirements.txt` — Dependencies required to run the notebook
- `README.md` — Project documentation and overview  
- (Optional) Generated visuals & exports from EDA and model evaluation

---

## ⚙️ Installation

1. **Clone or download the repository**
```
git clone <your_repo_url>
cd <repo_folder>
```

2. **Install dependencies**
```
pip install -r requirements.txt
```

3. **Open the notebook**
You can run the notebook locally or upload it to **Google Colab**.

---

## 📊 Dataset Description  
- **Name**: Estimation of Obesity Levels Based on Eating Habits and Physical Condition  
- **Source**: UCI Machine Learning Repository  
- **Type**: Classification  
- **Objective**: Predict the obesity level of individuals based on lifestyle, dietary habits, and physical condition.

The dataset contains both **numeric** and **categorical** variables, making it suitable for supervised machine learning using preprocessing pipelines.

---

## 🧪 Notebook Workflow Summary

### ✔️ 1. Data Loading  
The dataset is fetched automatically using the `ucimlrepo` library.

### ✔️ 2. Preprocessing  
Includes:
- Duplicate removal  
- Missing value imputation  
- One‑hot encoding of categorical features  
- Standardization of numerical features  

### ✔️ 3. Feature Engineering  
A synthetic variable (`numeric_risk_score`) is created to capture aggregated risk patterns.

### ✔️ 4. Exploratory Data Analysis (EDA)  
The notebook provides:
- Distributions of numerical features  
- Target class distribution  
- Boxplots  
- Correlation heatmap  

### ✔️ 5. Machine Learning Models Tested  
The following models were compared using **cross‑validation (Accuracy)**:
- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting Classifier  

### ✔️ 6. Hyperparameter Optimization  
A **RandomizedSearchCV** was used to optimize a Random Forest model.

### ✔️ 7. Final Evaluation  
The best model (optimized Random Forest) was evaluated on the test set with:
- Classification report  
- Confusion matrix  
- AUC‑ROC (multiclass OVR)

---

## 🏆 Results Summary

- The optimized **Random Forest** model achieved the **best accuracy** during cross‑validation.
- The **test set evaluation** showed strong predictive performance, balanced across obesity classes.
- Feature engineering and preprocessing pipelines contributed significantly to model stability.
- The workflow is fully automated and ready for production-level enhancement.

---

## 🚀 How to Use This Project  
1. Install dependencies  
2. Run the notebook from start to finish  
3. Use the model template to extend experiments or deploy the classifier  

---

## 📜 License  
This project is provided for academic and research purposes.

---

## 👤 Author  
Generated automatically using ChatGPT — ready for academic submission or professional ML documentation.
