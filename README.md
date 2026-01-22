🔥 Calories Burnt Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting the number of calories burned during physical activity using a machine learning regression model. The model is trained on user and exercise-related data such as gender, age, height, weight, duration, heart rate, and body temperature.

A Random Forest Regressor is used to achieve highly accurate predictions, with excellent performance on both training and testing datasets.

📊 Dataset Description

Two datasets are used and merged:

calories1.csv → Contains Calories burned

calories2.csv → Contains user and exercise features

Features Used:

Gender (encoded)

Age

Height

Weight

Duration

Heart Rate

Body Temperature

Target Variable:

Calories

⚙️ Data Preprocessing

The following preprocessing steps are performed:

Merging datasets

Dropping unnecessary column (User_ID)

Encoding categorical data (Gender) using Label Encoding

Checking for missing values

Splitting data into training (80%) and testing (20%)

🤖 Model Used

Algorithm: Random Forest Regressor

Library: sklearn.ensemble

Why Random Forest?

Handles non-linearity well

Reduces overfitting

High accuracy on structured data

📈 Model Evaluation
Training Performance:

R² Score: ~0.9946

Mean Squared Error (MSE): Very low

Testing Performance:

R² Score: ~0.9992

Mean Squared Error (MSE): Very low

➡️ These results indicate excellent generalization and no overfitting.

📉 Visualization

Scatter plots are used to visualize Actual vs Predicted Calories

Separate visualization for Training vs Testing data

Strong alignment along the diagonal confirms model accuracy

🛠️ Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn

Jupyter Notebook

✅ Conclusion

This project demonstrates how machine learning can be effectively used to predict calories burned with very high accuracy. The Random Forest model performs exceptionally well and is suitable for real-world fitness and health applications.

📌 Future Improvements

Cross-validation

Feature importance analysis

Model deployment (Flask / Streamlit)

Real-time user input interface
