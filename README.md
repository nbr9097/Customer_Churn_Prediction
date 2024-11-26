# Customer Churn Prediction
This project aims to predict customer churn for a telecom service provider using machine learning techniques. Customer churn is a critical business problem, and by identifying customers likely to leave, companies can improve retention strategies and profitability.

## Features of the Project
### EDA & Visualization:

- Analyzed key features impacting churn, such as monthly charges, tenure, payment methods, and internet services.
- Explored relationships between churn and customer demographics, contract type, and service usage using data visualization libraries like Seaborn, Matplotlib, and Plotly.
### Data Preprocessing:

- Handled missing values and dropped irrelevant columns.
- Encoded categorical features using one-hot encoding and label encoding.
- Standardized numerical features for model stability.
### Models Tested and Accuracy Results:

- Logistic Regression: 79.35%
- Random Forest: 81.29%
- Gradient Boosting: 80.21%
- K-Nearest Neighbors: 78.57%
- AdaBoost: 80.48%
- Decision Tree: 73.45%
- Support Vector Machine (SVM): 76.89%
- Final Voting Classifier (Ensemble Model): 82.51%

## Tech Stack
- Python
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn, XGBoost

## How to Run the Code
- Clone this repository.
- Install required libraries using pip install -r requirements.txt.
- Run the customer_churn.py script to execute preprocessing, visualization, and model training.
- Use your dataset or the provided customer_churn.csv file.
## Results
- Achieved the highest accuracy of 82.51% with the Voting Classifier, combining predictions of Gradient Boosting, Logistic Regression, and AdaBoost.
- The final confusion matrix and performance metrics highlighted a significant improvement in churn prediction.
## Future Improvements
- Enhance feature engineering (e.g., interaction terms, feature selection).
- Incorporate advanced algorithms like CatBoost or LightGBM.
- Experiment with deep learning models for better predictions.
