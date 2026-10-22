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


5. The system follows a structured machine learning workflow, transforming raw customer data into meaningful purchase predictions.

flowchart TD
    A["📂 Customer Dataset<br/>1,500 Records"] --> B["🔍 Data Exploration<br/>& Preprocessing"]
    B --> C["🎯 Feature & Target Selection<br/>PurchaseStatus"]
    C --> D["✂️ Train-Test Split<br/>80% Training | 20% Testing"]
    D --> E["⚖️ Feature Scaling<br/>StandardScaler"]
    E --> F["🤖 Logistic Regression<br/>Model Training"]
    F --> G["🔮 Purchase Prediction"]
    G --> H["📊 Model Evaluation<br/>Accuracy, Precision, Recall, F1-Score"]
    H --> I["✅ Results<br/>82.67% Accuracy"]

    style A fill:#E8F0FE,stroke:#4285F4,color:#202124
    style F fill:#E6F4EA,stroke:#34A853,color:#202124
    style I fill:#D1FAE5,stroke:#059669,color:#064E3B
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
