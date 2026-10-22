# Customer Purchase Prediction Using Logistic Regression

Project Overview
This project uses machine learning to predict whether a customer will make a purchase based on customer-related features. Logistic Regression is used as a binary classification algorithm.

Dataset
- **Dataset Name:** Customer Purchase Prediction Dataset
- **Target Variable:** `PurchaseStatus`
- **Target Values:** 0 = No Purchase, 1 = Purchase
- **Total Records:** 1,500

Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

Methodology
1. Load and explore the dataset.
2. Separate the input features and target variable.
3. Split the data into training and testing sets using an 80:20 ratio.
4. Standardize the features using StandardScaler.
5. Train the Logistic Regression model.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a classification report.

Results
- **Model:** Logistic Regression
- **Test Records:** 300
- **Accuracy:** 82.67%
- **Correct Predictions:** 248
- **Incorrect Predictions:** 52

Conclusion
The Logistic Regression model achieved 82.67% accuracy on the test dataset. This project demonstrates how machine learning can help businesses predict customer purchase behaviour and support data-driven marketing decisions.

Future Improvements
- Compare Logistic Regression with Decision Tree and Random Forest.
- Tune model parameters to improve performance.
- Explore additional customer features.

Tools
Developed using Python in Google Colab.
