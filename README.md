# Logistic Regression Analysis on Wine Quality with Regularization Techniques

## Project Overview

This project explores the use of logistic regression with various regularization techniques (L1 and L2) to predict wine quality based on chemical properties. The goal is to identify the most influential factors that determine wine quality and to understand how different regularization strengths impact the model's performance and feature selection. This analysis provides valuable insights for winemakers and enthusiasts who wish to enhance the quality of their products based on data-driven evidence.

## Dataset

The dataset used in this analysis contains information on the chemical properties of wines, including attributes such as:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality** (target variable)

The dataset is preprocessed to convert the quality scores into a binary classification problem, indicating high and low-quality wines.

## Project Structure

- **`wine_quality_analysis.ipynb`**: The main analysis notebook where logistic regression models with different regularization strengths are trained and evaluated. It includes visualizations of model coefficients and performance metrics.
- **`README.md`**: The documentation file providing an overview of the project.
- **`requirements.txt`**: A list of required Python libraries to run the analysis.

## Key Features

- **Regularization Techniques**: Analysis using L1 (Lasso) and L2 (Ridge) regularization to observe their effects on feature selection and model performance.
- **Visualizations**: Comprehensive plots of feature coefficients and performance metrics across different regularization strengths.
- **Model Performance**: Evaluation of logistic regression models using F1 scores to determine the optimal regularization strength for predicting wine quality.

## Findings

- **Influential Features**: Alcohol content and volatile acidity were found to be the most significant predictors of wine quality.
- **Regularization Impact**: L2 regularization effectively reduced the influence of less important features, leading to a more robust and interpretable model.
- **Optimal Regularization Strength**: Moderate regularization (`C` values around 0.1 to 1) provided the best balance between model complexity and accuracy, preventing overfitting while retaining key information.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/pcpetty/wine-quality-logistic-regression.git

2. **Navigate to the project directory:**

    ```bash
    cd wine-quality-logistic-regression

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt

4. **Run the Jupyter notebooks:**

    ```bash
    Open data_preparation.ipynb and wine_quality_analysis.ipynb in Jupyter Notebook or JupyterLab to explore the analysis.

**Requirements**

    Python 3.7 or higher
    Jupyter Notebook or JupyterLab
    Required Python libraries (included in requirements.txt):
        numpy
        pandas
        matplotlib
        scikit-learn

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

For any questions or suggestions, please feel free to reach out at colepetty57@gmail.com.
