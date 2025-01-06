# Iris Flower Classification Project

This repository contains the code and resources for the **Iris Flower Classification** project, which was my first task during my internship at **Code Alpha**. The objective of this project was to classify iris flowers into one of three species (**Setosa**, **Versicolor**, **Virginica**) based on their sepal and petal measurements using **Machine Learning** techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Acknowledgements](#acknowledgements)

## Introduction
The Iris dataset is a classic in machine learning and statistics, often used as a beginner's dataset. This project aimed to:
- Preprocess and analyze the dataset.
- Train and evaluate machine learning models to classify iris species.
- Visualize and interpret model results using explainable AI techniques like **SHAP**.

## Dataset
The Iris dataset contains 150 samples with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Each sample belongs to one of three species:
1. **Setosa**
2. **Versicolor**
3. **Virginica**

The dataset is publicly available through the [Scikit-learn library](https://scikit-learn.org/stable/).

## Project Workflow
1. **Data Preprocessing:**
   - Handled missing values (if any).
   - Scaled the features for better model performance.
   - Encoded the target variable using one-hot encoding.

2. **Exploratory Data Analysis (EDA):**
   - Visualized the relationships between features using pair plots.
   - Examined the distribution of species in the dataset.
   - Analyzed correlations with heatmaps.

3. **Model Training:**
   - Trained various classifiers, including:
     - Logistic Regression
     - Random Forest
     - Gradient Boosting
   - Performed hyperparameter tuning for optimal performance.

4. **Model Explainability:**
   - Used **SHAP** to interpret the model's predictions and identify key features influencing the classifications.

## Results
- Achieved **95%+ accuracy** in classifying the iris species.
- Identified **petal length** and **petal width** as the most significant features for classification.
- Generated SHAP visualizations to interpret model predictions.

## Technologies Used
- **Python**
- **Scikit-learn**: For model training and evaluation.
- **Matplotlib** and **Seaborn**: For data visualization.
- **SHAP**: For explainable AI.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/iris-flower-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd iris-flower-classification
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python scripts to explore the project:
   ```bash
   jupyter notebook
   ```

## Acknowledgements
- A big thank you to **Code Alpha** for this opportunity to apply my skills and learn.
- The Scikit-learn library for providing the Iris dataset and powerful tools for machine learning.

---
Feel free to explore, fork, and contribute to this project! If you have any feedback or suggestions, please open an issue or contact me on [LinkedIn](https://www.linkedin.com/in/yourprofile/).
