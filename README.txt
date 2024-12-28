# Loan Classification Project

This project is designed to classify loan applicants based on their likelihood of loan repayment using machine learning techniques. It covers:
- Data Preprocessing
- Feature Engineering
- Model Training and Evaluation
- Hyperparameter Tuning
- Model Explainability using SHAP

**Dataset**: The dataset `loan_detection.csv` includes information about loan applicants, such as:
- Applicant Income
- Loan Amount
- Loan Status (Target variable)

The dataset is included in this project folder.

1. Install required libraries using:
   ```bash
   pip install -r requirements.txt


2.Open the Jupyter Notebook file Loan_Classification_Project.ipynb.

3.Run all cells in order to see the results. Ensure the dataset (loan_detection.csv) is in the same folder as the notebook.

4.The model is saved as loan_model.pkl. You can use it for predictions.

#### **5. File Descriptions**
```markdown
- `Loan_Classification_Project.ipynb`: Main Jupyter Notebook with the code and outputs.
- `loan_detection.csv`: Dataset used in the project.
- `loan_model.pkl`: Trained Random Forest model saved as a pickle file.
- `README.md`: This file, which explains the project.

Dependencies:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- shap
- xgboost