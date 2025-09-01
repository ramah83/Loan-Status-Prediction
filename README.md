# 💳 Loan Eligibility Prediction Using Support Vector Machine (SVM)

A machine learning project to predict whether a loan application is eligible for approval based on applicant details.  
The model is built using Support Vector Machine (SVM) with linear kernel, including preprocessing, feature encoding, scaling, exploratory analysis, and performance evaluation.

---

## 🚀 Features

📊 **Exploratory Data Analysis (EDA):** Value counts, summary statistics, count plots, and correlation heatmap  
🧮 **Preprocessing:** Handling missing values, encoding categorical variables, scaling numerical features  
🤖 **Model Training:** Support Vector Machine (SVM) with linear kernel  
📈 **Evaluation Metrics:** Accuracy on training & test sets, confusion matrix, F1 score (optional)  
🧪 **Prediction on New Samples:** Custom input reshaping and real-time loan eligibility prediction  
🔎 **Visualization:** Count plots for categorical features, heatmap for feature correlations  

---

## 🧠 Machine Learning Workflow

- Import libraries (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Load Loan dataset (CSV file)  
- Explore dataset (shape, head, info, describe, value counts)  
- Handle missing values and encode categorical variables  
- Drop unnecessary columns (Loan_ID)  
- Visualize distributions and correlations (countplots, heatmap)  
- Split dataset into training & testing sets (80% / 20%, stratified)  
- Standardize features using **StandardScaler**  
- Train **SVM model** with linear kernel  
- Evaluate performance (train/test accuracy, optional F1 score)  
- Test predictions on new input samples  

---

## 🛠️ Tech Stack

| Layer       | Technology       |
|-------------|------------------|
| Language    | Python 3.12      |
| Framework   | Scikit-learn     |
| Dataset     | Loan Eligibility Dataset |
| Tools       | NumPy, Pandas, Matplotlib, Seaborn |

---

## 📁 Project Structure

```text
├── Data/
│   └── Loan Eligibility Dataset.csv   ← Main dataset
├── Loan_Status_Prediction.ipynb       ← Jupyter Notebook (main workflow)
├── outputs/                           ← Graphs & plots (optional)
└── README.md                          ← Project documentation
