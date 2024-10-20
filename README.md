# Customer Churn Prediction Project

This project focuses on predicting customer churn using a dataset containing customer demographic, financial, and account information. The goal is to build a predictive model that can identify customers who are likely to exit the service.

## Dataset

- File: `00- Dataset CSV_Churn_Modelling.csv`
- Description: The dataset contains information about customers of a bank, including demographic and financial data, and whether they have churned (exited) the service.
  
### Key Variables:
- `RowNumber`: Unique identifier for each record.
- `CustomerId`: Unique identifier for each customer.
- `Surname`: Customer's surname.
- `CreditScore`: Credit score of the customer.
- `Geography`: The country where the customer resides.
- `Gender`: Gender of the customer (Male/Female).
- `Age`: Age of the customer.
- `Tenure`: Number of years the customer has been with the bank.
- `Balance`: The customer's account balance.
- `NumOfProducts`: Number of products the customer uses.
- `HasCrCard`: Whether the customer has a credit card (1: Yes, 0: No).
- `IsActiveMember`: Whether the customer is an active member (1: Yes, 0: No).
- `EstimatedSalary`: The estimated salary of the customer.
- `Exited`: Whether the customer has churned (1: Yes, 0: No).

## Project Workflow

1. Data Loading:  
   The dataset is loaded from the provided CSV file and inspected for missing values and basic statistical summaries.

2. Data Preprocessing:  
   - Handling missing or inconsistent data if necessary.
   - Encoding categorical variables such as `Geography` and `Gender` into numerical values.
   - Feature scaling for numerical variables to improve model performance.

3. Exploratory Data Analysis (EDA):  
   - Analyze trends and relationships between different features and the `Exited` target variable.
   - Visualize the distribution of key variables such as age, credit score, and balance to gain insights into churn behavior.

4. Model Building:  
   - Train machine learning models such as logistic regression, decision trees, random forests, or neural networks to predict customer churn.
   - Evaluate model performance using accuracy, precision, recall, F1-score, and other metrics.

5. Model Evaluation and Tuning:  
   - Apply cross-validation and hyperparameter tuning to optimize the chosen model's performance.
   - Evaluate the model using a test set to measure its ability to generalize to unseen data.

## Requirements

To run the project, you will need the following dependencies:
- Python 3.8+
- Pandas
- Scikit-learn
- Matplotlib (optional for visualization)
- Seaborn (optional for visualization)

You can install the necessary Python packages using the following command:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Running the Project

1. Step 1: Data Preparation 
   - Place the dataset file `00- Dataset CSV_Churn_Modelling.csv` in the project directory.
   
2. Step 2: Data Preprocessing  
   - Run the provided Jupyter notebook to preprocess the data, including feature encoding and scaling.
   
3. Step 3: Model Training
   - Train machine learning models using the processed dataset and evaluate their performance.

4. Step 4: Prediction 
   - Use the trained model to predict whether new customers will churn based on their data.
