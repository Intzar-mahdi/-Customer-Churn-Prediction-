# 🔁 Customer Churn Prediction

This project focuses on predicting customer churn using machine learning models. The dataset contains bank customer data, and the goal is to identify which customers are likely to leave the bank.

## 📁 Dataset

- **Name:** Churn_Modelling.csv  
- **Target Variable:** `Exited`  
- **Features:**
  - Credit Score, Age, Tenure, Balance, Gender, Geography, etc.

## 🧰 Tools & Libraries Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn (for visualization)  
- Scikit-learn (for preprocessing, modeling, and evaluation)

## 🧪 Project Steps

1. **Data Loading:**  
   Loaded the dataset using `pandas`.

2. **Data Cleaning:**  
   - Dropped unnecessary columns (`RowNumber`, `CustomerId`, `Surname`)  
   - Encoded `Gender` using `LabelEncoder`  
   - Converted `Geography` to dummy variables

3. **Train-Test Split:**  
   Split data into training and testing sets.

4. **Model Building:**  
   - Logistic Regression  
   - Decision Tree Classifier

5. **Evaluation:**  
   - Accuracy Score  
   - Confusion Matrix Visualization

## 📈 Results

Both models were compared using accuracy and confusion matrices to assess their performance in predicting customer churn.

## 📌 How to Run

1. Clone the repository
2. Add the dataset file `Churn_Modelling.csv` to your working directory
3. Open `Task3.ipynb` in Jupyter Notebook
4. Run all cells to see the full analysis

```bash
git clone https://github.com/Intzar-mahdi/Customer-Churn-Prediction.git
