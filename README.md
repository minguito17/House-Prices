
# House Price Prediction Using XGBoost and Regression Models

## Description / Overview

This project explores the prediction of house sale prices using different regression models. Using a real estate dataset, the team performed data cleaning, outlier removal, feature engineering, and tested various models including XGBoost, Linear Regression, Random Forest, and Ridge Regression. The goal was to find a robust model that minimizes overfitting and predicts prices accurately.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Authors / Credits](#authors--credits)
- [Contact Information](#contact-information)
- [References / Acknowledgments](#references--acknowledgments)

## Installation

1. Clone the repository:  
   ```
   git clone <YOUR_REPO_URL>
   cd <YOUR_REPO_DIRECTORY>
   ```

2. Install Python dependencies:  
   ```
   pip install pandas numpy scikit-learn seaborn matplotlib xgboost scipy statsmodels
   ```

## Usage

- Load the dataset `house_sales.csv`.
- Use Python scripts or notebooks to:
  - Perform EDA and visualize outliers, correlations, and feature distributions.
  - Clean the data, handle missing values, remove outliers.
  - Select features and perform transformations.
  - Train regression models:
    - XGBoost
    - Linear Regression
    - Random Forest Regressor
    - Ridge Regression
  - Evaluate models using R², RMSE, MAE, and cross-validation.
  - Analyze feature importance.

## Features

- Exploratory Data Analysis with correlation matrices, boxplots, and histograms.
- Data cleaning with outlier detection and removal.
- Log transformations for skewed features.
- XGBoost model tuning and cross-validation.
- Comparison of multiple regression models.
- Feature importance visualization.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss proposed modifications.

## License

This project is for educational purposes only.

## Authors / Credits

- Collaboration by Jose Guarneros and Marinela Inguito

## Contact Information

For questions, please reach out through your university or course platform.

## References / Acknowledgments

- [Towards Data Science: XGBoost](https://towardsdatascience.com/a-journey-through-xgboost-milestone-3-a5569c72d72b)
- [Data Transformation in Python](https://www.visual-design.net/post/data-transformation-and-feature-engineering-in-python)
- Python libraries: pandas, scikit-learn, seaborn, matplotlib, xgboost

