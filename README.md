# Fuel-Efficiency-Project
Auto MPG – UEL Average Predictor (Machine Learning Project)
Project Overview

This project focuses on building a machine learning model to predict vehicle fuel efficiency (miles per gallon – MPG) using the Auto MPG dataset from Kaggle.
The main objective is to estimate the UEL average (fuel efficiency) of automobiles based on engine, weight, and performance-related features.

Fuel efficiency prediction is an important real-world problem in the automotive industry, helping manufacturers and consumers make informed decisions regarding vehicle performance and environmental impact.

Dataset Description

Dataset Name: Auto MPG Dataset

Source: Kaggle

Records: 398 vehicles

Features Used:

Cylinders

Displacement

Horsepower

Weight

Acceleration

Model Year

Origin

Target Variable: MPG (Miles Per Gallon)

Missing values in the dataset (especially in horsepower) were handled during preprocessing.

🧠 Methodology

The project follows a complete machine learning pipeline, including:

Data Loading & Exploration

Understanding dataset structure

Statistical summaries

Correlation analysis

Data Preprocessing

Handling missing values

Feature selection

Encoding categorical variables

Feature scaling (where required)

Model Building

Implemented regression-based machine learning models

Trained the model on processed data

Model Evaluation

Performance evaluated using metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

⚙️ Technologies & Libraries Used

Python

Jupyter Notebook

Pandas – data manipulation

NumPy – numerical operations

Matplotlib / Seaborn – data visualization

Scikit-learn – machine learning models & evaluation

📈 Results

The trained model successfully predicts vehicle MPG with reasonable accuracy.

Key factors influencing fuel efficiency include:

Vehicle weight

Engine displacement

Number of cylinders

The results demonstrate that machine learning can effectively model real-world automotive data.

Conclusion

This project demonstrates the application of machine learning regression techniques to predict fuel efficiency using real-world data.
It highlights the importance of data preprocessing, feature selection, and evaluation in building reliable predictive models.

The project can be further improved by:

Trying advanced models (Random Forest, XGBoost)

Hyperparameter tuning

Deploying the model as a web application
