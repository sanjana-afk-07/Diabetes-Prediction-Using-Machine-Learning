# Diabetes-Prediction-Using-Machine-Learning
🩺 Diabetes Prediction Using Machine Learning

📌 Project Overview

The Diabetes Prediction Using Machine Learning project is designed to predict whether a person is likely to have diabetes based on health-related information.

This project uses Machine Learning classification algorithms to analyze input features and predict the diabetes outcome.

The main objective is to demonstrate how Machine Learning can be applied to healthcare data analysis and prediction.

Note: This project is for educational purposes only and is not a medical diagnostic tool.

🎯 Project Objectives

- To analyze diabetes-related health data.
- To clean and preprocess the dataset.
- To identify important features for prediction.
- To build Machine Learning classification models.
- To predict diabetes outcomes.
- To compare the performance of two algorithms.
- To evaluate the models using performance metrics.
- To visualize prediction results.

🧠 Algorithms Used

1. Decision Tree Classifier (Main Algorithm)

Decision Tree is a supervised Machine Learning algorithm used for classification. It makes predictions using a tree-like structure based on different input conditions.

Why Decision Tree?

- Easy to understand and interpret.
- Suitable for classification problems.
- Handles numerical and categorical features.
- Identifies decision-making patterns.
- Provides understandable prediction rules.

2. Logistic Regression (Comparison Algorithm)

Logistic Regression is a supervised Machine Learning algorithm used to predict the probability of a class.

Why Logistic Regression?

- Suitable for binary classification.
- Predicts the probability of diabetes.
- Simple and efficient.
- Provides a useful comparison with Decision Tree.

🛠️ Technologies Used

- Programming Language: Python
- IDE: Anaconda Spyder
- Libraries:
  - Pandas – Data manipulation.
  - NumPy – Numerical calculations.
  - Matplotlib – Data visualization.
  - Scikit-learn – Machine Learning algorithms.
  - StandardScaler – Feature scaling.
  - Seaborn – Data visualization, if used.

📂 Project Structure

Diabetes-Prediction/
│
├── diabetes_prediction.py
├── README.md
└── diabetes_prediction_dataset.csv

📊 Dataset Description

The project uses a diabetes prediction dataset containing health-related information.

The dataset includes features such as:

- Age
- Gender
- BMI
- Hypertension
- Heart Disease
- Smoking History
- HbA1c Level
- Blood Glucose Level
- Diabetes Outcome

Target Variable

The target variable is Diabetes.

- 0 – No Diabetes
- 1 – Diabetes

⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the diabetes dataset.
3. Display dataset information.
4. Check and clean missing values.
5. Remove duplicate records.
6. Separate input features and target variable.
7. Identify numerical and categorical columns.
8. Split the dataset into training and testing sets.
9. Preprocess the input features.
10. Train the Decision Tree model.
11. Train the Logistic Regression model.
12. Predict diabetes outcomes.
13. Evaluate both models.
14. Compare model performance.
15. Generate accuracy graphs and confusion matrices.
16. Display the final comparison result.

📈 Model Evaluation

The models are evaluated using the following performance metrics:

- Accuracy: Measures the percentage of correct predictions.
- Precision: Measures how many predicted positive cases are correct.
- Recall: Measures how many actual positive cases are identified.
- F1-Score: Balances precision and recall.
- Confusion Matrix: Displays correct and incorrect predictions.

📉 Visualizations

The project generates:

1. Model Accuracy Comparison Graph.
2. Decision Tree Confusion Matrix.
3. Model performance comparison.

These visualizations help understand the prediction performance of both algorithms.

💻 How to Run the Project

Step 1: Install Required Libraries

pip install pandas numpy matplotlib scikit-learn

Step 2: Dataset

Place the "diabetes_prediction_dataset.csv" file in your project folder.

Step 3: Open the Python File

Open "diabetes_prediction.py" using Anaconda Spyder.

Step 4: Update Dataset Path

Update the CSV file path according to your computer.

Step 5: Run the Program

Execute the Python program and view the prediction results and graphs.

📌 Expected Output

The program displays:

- Dataset information.
- Data preprocessing results.
- Decision Tree performance.
- Logistic Regression performance.
- Accuracy comparison.
- Confusion matrices.
- Final model comparison.

🌟 Applications

- Healthcare data analysis.
- Diabetes risk prediction research.
- Medical data classification.
- Health information analysis.
- Educational Machine Learning applications.

🔮 Future Enhancements

- Develop a web-based diabetes prediction application.
- Create an interactive prediction dashboard.
- Include additional health-related features.
- Test different Machine Learning algorithms.
- Improve model evaluation and validation.

👩‍💻 Author

Sanjana

Artificial Intelligence and Data Science Student

🏁 Conclusion

The Diabetes Prediction project demonstrates the use of Machine Learning in healthcare-related data analysis.

Decision Tree and Logistic Regression algorithms are implemented and compared to predict diabetes outcomes.

This project provides practical knowledge of data preprocessing, classification, prediction, model evaluation and visualization.

---

⭐ If you find this project useful, consider giving this repository a star!
