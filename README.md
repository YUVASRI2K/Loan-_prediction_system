# Loan-_prediction_system
##Loan Prediction using ML This project aims to predict loan approval using machine learning techniques. The dataset contains various features about loan applicants, and the goal is to determine whether a loan will be approved based on these features. Data Preprocessing Data preprocessing steps include:

Handling Missing Values:

Missing values in categorical columns like Gender, Married, Dependents, and Self_Employed are filled with the mode of the respective column. Missing values in numerical columns like LoanAmount and Loan_Amount_Term are filled with the mean or mode as appropriate. Created new features loanAmount_log and TotalIncome_log for better distribution of data. Label Encoding:

Categorical features are encoded using LabelEncoder to convert them into numerical values suitable for modeling. Feature Scaling:

Applied StandardScaler to scale the features to have mean 0 and variance 1, which helps in improving the model's performance. Modeling Train-Test Split: The dataset is split into training and testing sets using an 80-20 split. Model Used: Random Forest Classifier: A robust ensemble learning method that combines multiple decision trees to provide accurate predictions. Evaluation The model's performance is evaluated using the testing set, and results are measured by comparing predictions against the actual labels.
