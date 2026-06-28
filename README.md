Loan Status Prediction using Machine Learning

A Machine Learning project that predicts whether a loan application will be Approved or Rejected based on applicant details such as income, education, credit history, loan amount, and property area. This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and prediction.

📌 Project Overview

Loan approval prediction is one of the most common classification problems in Machine Learning. Financial institutions use predictive models to automate the loan approval process and reduce manual effort.

This project uses multiple Machine Learning algorithms to compare their performance and identify the best model for predicting loan status.

📂 Dataset

The dataset contains information about loan applicants.

Features
Loan_ID
Gender
Married
Dependents
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Property_Area
Target Variable
Loan_Status
Y → Loan Approved
N → Loan Rejected
🚀 Project Workflow
Import Required Libraries
Load Dataset
Data Understanding
Data Cleaning
Handle Missing Values
Exploratory Data Analysis (EDA)
Feature Engineering
Label Encoding
Feature Selection
Train-Test Split
Model Training
Model Evaluation
Accuracy Comparison
Best Model Selection
Loan Prediction System
Model Saving
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Jupyter Notebook
🤖 Machine Learning Models

The following classification algorithms were implemented:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
📊 Model Evaluation

The models were evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
Model Accuracy Comparison

The model with the highest accuracy was selected as the final prediction model.

📁 Project Structure
Loan-Status-Prediction/
│
├── loan.csv
├── Loan_Status_Prediction.ipynb
├── loan_prediction_model.pkl
├── README.md
└── requirements.txt
▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/Loan-Status-Prediction.git
2. Navigate to the Project Folder
cd Loan-Status-Prediction
3. Install Required Libraries
pip install -r requirements.txt
4. Run the Jupyter Notebook
jupyter notebook

Open Loan_Status_Prediction.ipynb and execute all cells.

📈 Results
Successfully cleaned and preprocessed the dataset.
Performed Exploratory Data Analysis (EDA).
Trained multiple Machine Learning models.
Compared model performance using accuracy.
Selected the best-performing model for loan approval prediction.
Built a prediction system for new applicant data.
📌 Future Improvements
Hyperparameter Tuning
Cross-Validation
Deployment using Flask or Streamlit
Interactive Web Application
Real-time Loan Approval Prediction
👩‍💻 Author

Prachi Dnyaneshwar Netke

GitHub: https://github.com/your-username
LinkedIn: https://linkedin.com/in/your-profile
Email: your-email@example.com
⭐ If you found this project useful, don't forget to Star the repository on GitHub!# Loan-prediction-using-machine-learning
