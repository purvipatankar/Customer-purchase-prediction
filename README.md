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
1. Load and explore the dataset.
2. Separate input features from the target variable, `PurchaseStatus`.
3. Split the dataset into 80% training data and 20% testing data.
4. Standardize the features using `StandardScaler`.
5. Train the Logistic Regression model.
6. Evaluate the model using accuracy, precision, recall, and F1-score.

5. Model Accuracy
The Logistic Regression model achieved **82.67% accuracy** on 300 test records.

- **Correct Predictions:** 248
- **Incorrect Predictions:** 52

The model performed well overall, with better recall for the No Purchase class than for the Purchase class.

6. Conclusion and Future Improvements
The project demonstrates how Logistic Regression can predict customer purchase behaviour using machine learning. The model achieved 82.67% accuracy, showing its potential to support customer analysis and marketing decisions.

Future Improvements:
- Compare Logistic Regression with Decision Tree and Random Forest.
- Tune model parameters to improve performance.
- Explore additional customer features.
- Improve the prediction of potential buyers.

7. References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- Dataset source: (https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset/data)
