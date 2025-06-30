# Heart Disease Prediction

This project demonstrates a machine learning pipeline to predict heart disease risk from patient health data, using the **UCI Heart Disease** dataset.

---

## Objective

- Predict whether a person has heart disease (binary classification).
- Use features such as age, sex, chest pain type, cholesterol, etc.
- Train a Logistic Regression model.
- Visualize data with separate heatmaps for males and females.
- Evaluate using accuracy, confusion matrix, and ROC curve.
- Analyze feature importance.

---

## Dataset

- [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci)  
- Includes features:
  - Age
  - Sex
  - Chest pain type
  - Resting blood pressure
  - Serum cholesterol
  - Fasting blood sugar
  - Resting ECG results
  - Maximum heart rate achieved
  - Exercise-induced angina
  - ST depression
  - Slope of peak exercise ST segment
  - Number of major vessels
  - Thalassemia
  - and the **target** (presence of heart disease)
 
 ---

## ⚙️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

---

## How it Works

1. Load and clean the dataset
2. Encode categorical columns
3. Perform exploratory data analysis

   * Overall correlation heatmap
   * Separate heatmaps for males and females
4. Split data into training and testing sets
5. Train a Logistic Regression model
6. Evaluate performance

   * Accuracy
   * Confusion matrix
   * ROC curve
7. Visualize feature importance

---

## Results

* The model achieves reasonable accuracy on the test set.
* Separate correlation heatmaps allow comparing male and female patients.
* Coefficients provide insight into important risk factors.

---

## Possible Extensions

* Try Decision Tree or Random Forest models
* Perform hyperparameter tuning
* Use SHAP or LIME for better feature explanations
* Add more visualization dashboards
---

## Acknowledgments

* [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease)
* Kaggle community
* scikit-learn
* seaborn

>  **Disclaimer:** This is a demonstration project for educational purposes only. It should not be used as a medical diagnostic tool.

