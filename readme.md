# 🏦 Bank Default Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a customer will default on their loan based on features such as employment status, bank balance, and annual salary. Using a real-world styled financial dataset, we apply machine learning classification models to assist banks in credit risk assessment.  

The goal is to:
- Analyze financial data.  
- Build predictive models.  
- Compare performance of multiple ML algorithms.  
- Visualize insights for better decision-making.  

---

## 📂 Dataset Information
- **File:** `Default_Fin.csv`  
- **Rows:** 10,000  
- **Columns:**  

| Column Name   | Description                                      |
|---------------|--------------------------------------------------|
| Employed      | 1 = employed, 0 = unemployed                     |
| Bank Balance  | Customer’s current bank balance                  |
| Annual Salary | Customer’s yearly income                         |
| Defaulted?    | Target variable (1 = defaulted, 0 = not defaulted)|

---

## ⚙️ Technologies Used
- **Python 3**  
- **Google Colab / Jupyter Notebook**  

**Libraries:**
- `pandas`, `numpy` → Data Processing  
- `matplotlib`, `seaborn` → Visualization  
- `scikit-learn` → ML Models & Evaluation  

---

## 🚀 Steps in the Project

### 1. Data Loading & Exploration
- Read the dataset and inspect structure.  
- Check missing values and distributions.  

### 2. Data Preprocessing
- Encode categorical values.  
- Scale numeric features.  
- Perform train-test split.  

### 3. Model Training
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

### 4. Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score  
- Confusion Matrix & ROC Curve  

### 5. Visualization
- Feature importance (Random Forest)  
- Correlation heatmap  
- ROC curve comparison  

---

## 📊 Results & Insights
- **Random Forest** performed the best with the highest accuracy and recall.  
- **Annual Salary** and **Bank Balance** were the most significant predictors of default.  
- Employed individuals had a lower default probability compared to unemployed.  

---

## 🖥️ How to Run
1. Open the project in **Google Colab**.  
2. Upload `Default_Fin.csv`.  
3. Run the notebook cells sequentially.  
4. View performance metrics and visualizations.  

---

## 📌 Future Improvements
- Incorporate more features (e.g., credit history, loan amount).  
- Apply deep learning models (Neural Networks).  
- Deploy the model as a **web app** for banks.  

---

## 📜 License
This project is for **educational purposes** and not intended for production-level banking systems.  

---

✨ **Author:** *Nimmagadda Sampreeth Chowdary*  
