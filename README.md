## Employee Churn Prediction

### Exploratory Data Analysis

<img width="446" alt="image" src="https://github.com/user-attachments/assets/802a6361-8da9-4304-9ec6-f575de6a73e6">

<img width="412" alt="image" src="https://github.com/user-attachments/assets/292d9bec-5bad-4a8b-9bc1-ba76f5c29ac9">

<img width="654" alt="image" src="https://github.com/user-attachments/assets/c9ed1125-a4c6-4dbf-9bef-e3837425aa9f">

This project aims to predict employee churn using various machine learning models, including XGBoost, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM). The goal is to identify patterns and factors that contribute to employee turnover, helping organizations take proactive measures to retain talent.

### Project Overview
Employee churn is a critical issue for businesses, as it directly impacts productivity, morale, and costs. This project explores different machine learning algorithms to accurately predict which employees are at risk of leaving the company.

### Models and Results
The following models were implemented and evaluated based on their accuracy:

* XGBoost: Achieved an accuracy of 79.65%.
* Random Forest: Achieved the highest accuracy of 80.49%.
* K-Nearest Neighbors (KNN): Achieved an accuracy of 78.78%.
* Support Vector Machine (SVM): Achieved an accuracy of 76.35%.

### Project Workflow
Data Collection & Preprocessing:
* Collected relevant employee data, including demographic information, job satisfaction, performance metrics, etc.
* Cleaned and preprocessed the data, handling missing values, encoding categorical variables, and normalizing features.

### Model Development:
* Implemented XGBoost, Random Forest, KNN, and SVM models using Python libraries like scikit-learn and XGBoost.
* Trained each model on the training dataset and evaluated performance on the test dataset.

### Evaluation & Comparison:

* Compared the models based on their accuracy scores to identify the best-performing model.
* The Random Forest model outperformed the others with the highest accuracy.

### Conclusion
The Random Forest model demonstrated the best performance in predicting employee churn with an accuracy of 80.49%. This model can be used by HR departments to develop strategies for retaining valuable employees and reducing turnover rates.

### Technologies Used
* Python: For data preprocessing, model implementation, and evaluation.
* Scikit-learn: For building KNN, SVM, and Random Forest models.
* XGBoost: For implementing the XGBoost model.
* Pandas & NumPy: For data manipulation and analysis.
* Matplotlib & Seaborn: For data visualization.

### How to Use
Clone the repository.
Install the required Python libraries.
Run the provided Jupyter notebook to train the models and evaluate their performance on your dataset.


