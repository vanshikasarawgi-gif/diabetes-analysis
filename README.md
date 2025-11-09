
# Diabetes Data Analysis

## Overview

This project analyzes the **Pima Indians Diabetes dataset** using Python to explore the relationship between patient health metrics and diabetes outcomes. The analysis includes data preprocessing, handling missing/zero values, and visualizations to reveal trends and correlations.

## Dataset

* The dataset contains health measurements such as:

  * **Pregnancies**
  * **Glucose**
  * **BloodPressure**
  * **SkinThickness**
  * **Insulin**
  * **BMI**
  * **DiabetesPedigreeFunction**
  * **Age**
  * **Outcome** (1 = diabetes, 0 = no diabetes)
* Source: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## Features

* **Data Cleaning:** 
* **Grouping & Analysis:** Used `groupby` to explore how features like BMI, glucose, pregnancies, and blood pressure relate to diabetes.
* **Visualizations:**

  * Scatter plots, line plots, and bar plots
  * correlation heatmap to show relationships between all features
  * Examining relationships between patient health factors and diabetes outcomes.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/vanshikasarawgi-gif/diabetes-analysis.git
```

2. Open `diabetes_analysis.ipynb` in **Jupyter Notebook** or **JupyterLab**.
3. Run the cells sequentially to see the data analysis and visualizations.

## Notes

* FutureWarnings in Pandas for categorical groupby operations have been handled using `observed=True`.

