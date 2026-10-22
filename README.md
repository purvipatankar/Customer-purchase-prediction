# Customer-purchase-prediction
Machine learning project to predict customer purchase behaviour using Logistic Regression.
# Customer Purchase Prediction Using Logistic Regression

1. Project Overview
This project uses machine learning to predict whether a customer will make a purchase based on customer-related data. Logistic Regression is used as a binary classification algorithm to support data-driven marketing decisions.

2. Dataset Name and Target Variable
- **Dataset Name:** Customer Purchase Prediction Dataset
- **Total Records:** 1,500
- **Target Variable:** `PurchaseStatus`
- **Target Values:** 0 – No Purchase, 1 – Purchase
- **Features:** Customer-related attributes used to predict purchase behaviour.

3. Technologies Used
- **Python** – Programming language
- **Google Colab** – Development environment
- **Pandas and NumPy** – Data handling and processing
- **Matplotlib and Seaborn** – Data visualization
- **Scikit-learn** – Data preprocessing, model training, and evaluation

4. Brief Methodology
- Load and explore the dataset.
- Separate input features from the target variable, `PurchaseStatus`.
- Split the dataset into 80% training data and 20% testing data.
- Standardize the features using `StandardScaler`.
- Train the Logistic Regression model.
- Evaluate the model using accuracy, precision, recall, and F1-score.


5. Project Architecture
The architecture shows how data flows through the different components of the system to generate a purchase prediction.
Dataset Input

Customer Purchase Prediction Dataset (1,500 records)

Data Preprocessing

Data inspection, feature selection, target separation and scaling

Train-Test Split

80% training data · 20% testing data

Logistic Regression Model

Train the model using the training data

Prediction and Evaluation

Predict purchase status and calculate evaluation metrics

Final Output

82.67% accuracy · Purchase (1) or No Purchase (0)


Project Pipeline
The pipeline describes the steps followed to build and evaluate the machine learning model.
1. Data Collection: Load the customer dataset into Google Colab.
2. Data Exploration: Inspect the dataset, column names, data types and missing values.
3. Feature Selection: Separate input features (X) from the target variable (PurchaseStatus).
4. Data Splitting: Divide the data into 80% training and 20% testing sets using stratified sampling.
5. Feature Scaling: Apply StandardScaler to standardize the input features.
6. Model Training: Train the Logistic Regression algorithm using the training dataset.
7. Prediction: Predict purchase status for the test dataset.
8. Model Evaluation: Calculate accuracy, precision, recall, F1-score and the classification report.
9. Result Analysis: Analyze prediction performance and identify possible improvements.
3. Pipeline Summary
Dataset → Preprocessing → Train-Test Split → Scaling → Model Training → Prediction → Evaluation
6. Model Accuracy
The Logistic Regression model achieved **82.67% accuracy** on 300 test records.

- **Correct Predictions:** 248
- **Incorrect Predictions:** 52

The model performed well overall, with better recall for the No Purchase class than for the Purchase class.

7. Conclusion and Future Improvements
The project demonstrates how Logistic Regression can predict customer purchase behaviour using machine learning. The model achieved 82.67% accuracy, showing its potential to support customer analysis and marketing decisions.

Future Improvements:
- Compare Logistic Regression with Decision Tree and Random Forest.
- Tune model parameters to improve performance.
- Explore additional customer features.
- Improve the prediction of potential buyers.

8. References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- Dataset source: (https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset/data)
