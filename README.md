# Student Grade Determination Analysis 📊📈👀

This repository contains the code and analysis for a study aimed at determining the socio-demographic factors that influence the grades of students in secondary school math courses. The dataset used in this analysis was obtained from Kaggle and includes a rich set of socio-demographic, gender, and study-related information about the students.
![image](https://github.com/Dulajay/Student-Grade-Determination-Analysis/assets/151004273/46e3b2c5-fa69-409a-8bf5-3b69cbfbd90e)
## Kaggle Dataset

The dataset, sourced from Kaggle, can be found [here](https://www.kaggle.com/datasets/alejandraalvarado/student-mat). Please place the CSV file in the `data/` directory before running the analysis.

## Project Goals

1. Explore and Load Data: Begin by loading and exploring the Kaggle dataset to understand its structure, types of data, and potential patterns.

2. Model Selection: Assess the type of data available and choose appropriate machine learning models for analysis.

3. Model Performance Comparison: Evaluate the performance of Linear Regression, Decision Tree, Random Forest, SVM, and a naive or mean model. Perform a grid search on the training data and use cross-validation to assess each model's effectiveness.

4. Identify Best Model: Determine the best-performing model based on metrics such as RMSE, RAE, and R^2.

5. Factors Influencing Grades: Analyze the results to identify the socio-demographic factors that have the most significant influence on student grades.

## Repository Structure

- `data/`: Contains the Kaggle dataset used for analysis.
- `notebooks/`: Source code for utility functions and scripts used in the analysis and model evaluation results and analysis outputs.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Dulajay/Student-Grade-Determination-Analysis
   cd student-grade-determination
   ```
2. The Kaggle dataset you can find the CSV file in the `data/` directory.

3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the analysis workflow.

## Results and Analysis

The Random Forest model demonstrated performance in predicting student grades. Detailed results and analysis can be found in the Jupyter notebooks located in the `notebooks/` directory.

![feature_importance_plot_rainbow](https://github.com/Dulajay/Student-Grade-Determination-Analysis/assets/151004273/519cabdf-ba70-4118-a637-e2b54e2ce9be)


## Conclusion

This analysis provides insights into the socio-demographic factors that significantly impact student grades using the Kaggle dataset. The Random Forest model, identified as the best-performing model, can serve as a valuable tool for predicting and understanding student performance.

Feel free to explore the code and analysis in this repository and adapt it for your own use cases 🚀
