# DevelopersHub Corporation — AI/ML Engineering Internship

**Intern:** Muhammad Ayaan Naeem  
**Student ID:** DHC-5016  
**Institution:** University of Engineering and Technology Lahore  
**Internship:** DevelopersHub Corporation — AI/ML Engineering Internship  
**Due Date:** 26th June, 2026  

---

## Overview
This repository contains the completed tasks for the AI/ML Engineering 
Internship at DevelopersHub Corporation. A minimum of 3 tasks were required 
and all 3 have been completed successfully.

---

## 🛠️ Tools & Technologies Used
- **Language:** Python 3.14
- **Editor:** VS Code with Jupyter Notebook extension
- **Libraries:**
  - `pandas` — for loading and manipulating data tables
  - `numpy` — for numerical calculations
  - `matplotlib` — for creating charts and graphs
  - `seaborn` — for prettier and more detailed visualizations
  - `scikit-learn` — for building and evaluating machine learning models

---

## Tasks Completed

### Task 1: Exploring and Visualizing the Iris Dataset
- **Objective:** Load, explore, and visualize the Iris dataset to understand 
  data trends and distributions across three flower species.
- **Dataset:** Iris Dataset (loaded via seaborn library)
- **Libraries Used:** pandas, numpy, matplotlib, seaborn
- **Visualizations:**
  - Scatter plot: Sepal Length vs Sepal Width by Species
  - Histograms: Distribution of all 4 features
  - Box plots: Feature spread per species
- **Key Findings:**
  - Dataset has 150 rows and 5 columns
  - 3 species: Setosa, Versicolor, and Virginica (50 each)
  - Setosa is clearly separable from the other two species
  - Petal measurements show the strongest separation between species

---

### Task 3: Heart Disease Prediction
- **Objective:** Build a classification model to predict whether a patient 
  is at risk of heart disease based on their health data.
- **Dataset:** Heart Disease UCI Dataset (Kaggle)
- **Model:** Logistic Regression
- **Libraries Used:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Visualizations:**
  - Age distribution histogram
  - Feature correlation heatmap
  - Confusion matrix
  - ROC Curve
- **Results:**
  - Accuracy: **85.25%**
  - Strong AUC score confirmed by ROC Curve
- **Key Findings:**
  - Dataset has 303 patients and 14 health features
  - No missing values found
  - Chest pain type and max heart rate are the strongest predictors 
    of heart disease

---

### Task 6: House Price Prediction
- **Objective:** Predict house sale prices based on property features 
  such as size, quality, and number of rooms.
- **Dataset:** House Prices — Advanced Regression Techniques (Kaggle)
- **Model:** Gradient Boosting Regressor
- **Libraries Used:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Visualizations:**
  - Distribution of house sale prices
  - Living area vs sale price scatter plot
  - Actual vs predicted prices plot
  - Feature importance bar chart
- **Results:**
  - Mean Absolute Error: **$19,128**
  - Root Mean Square Error: **$28,792**
  - R2 Score: **0.8919**
- **Key Findings:**
  - Dataset has 1460 houses with 7 key features selected
  - Bigger houses consistently sell for higher prices
  - Overall Quality rating and Living Area are the most important 
    predictors of house price

---

---

## How to Run
1. Clone this repository
2. Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
3. Open any task notebook in VS Code or Jupyter
4. Run all cells from top to bottom
