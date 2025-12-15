# Fuel-Efficiency-Project


# UEL Average (MPG) Predictor using Machine Learning

* In this project, I developed a **machine learning–based fuel efficiency (MPG) prediction system** using Python.
  The model predicts the **UEL average (miles per gallon)** of vehicles based on their technical and performance attributes.
  The project uses the **Auto MPG dataset from Kaggle** and follows a complete machine learning workflow.

* Below is an overview of the project’s key steps:

---

##🔹 Dataset Used

* **Dataset Name:** Auto MPG Dataset
* **Source:** Kaggle
* The dataset contains automobile data including engine specifications, vehicle weight, and performance indicators.

---

##🔹 Data Loading

* The dataset is loaded using **Pandas**.
* Initial exploration is performed to understand:

  * Dataset structure
  * Data types
  * Presence of missing values

---

##🔹 Data Preprocessing

* Missing values (especially in the *horsepower* feature) are identified and handled.
* Irrelevant columns are removed where necessary.
* Categorical data is encoded for machine learning compatibility.
* Feature scaling is applied to improve model performance.

---

##🔹 Feature Selection

* Important features used for prediction include:

  * Cylinders
  * Displacement
  * Horsepower
  * Weight
  * Acceleration
  * Model Year
  * Origin
* The **target variable** is **MPG (Miles Per Gallon)**.

---

##🔹 Model Training

* A regression-based machine learning model is trained on the processed dataset.
* The data is split into **training and testing sets** to evaluate model performance fairly.

---

##🔹 Model Evaluation

* The model is evaluated using standard regression metrics such as:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)
  * R² Score
* These metrics help measure how accurately the model predicts fuel efficiency.

---

##🔹 Results

* The model successfully predicts vehicle MPG with reasonable accuracy.
* Analysis shows that **vehicle weight and engine size** have a strong impact on fuel efficiency.
* The results confirm that machine learning is effective for real-world automotive data prediction.

---

##🔹 User Interaction

* The system allows predictions based on input vehicle features.
* Users can estimate fuel efficiency without manual calculations.

---

##🔹 Conclusion

Overall, this project demonstrates my ability to:

* Preprocess real-world datasets
* Apply machine learning regression techniques
* Evaluate model performance
* Build a practical predictive system using Python

This project provides a strong foundation for further enhancements such as:

* Using advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploying the model as a web application

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn


Just tell me.
