# MPG-Dataset-Analysis
This project involves the analysis of the MPG (Miles Per Gallon) dataset using Python. The dataset is loaded from Seaborn and includes various features related to car specifications, which are used to predict the MPG.
## Project Overview
The goal of this project is to:
- Perform exploratory data analysis (EDA) and data preprocessing
- Conduct bivariate analysis and multivariate analysis
- Build an initial Linear Regression model and evaluate it
- Use advanced techniques such as Cross-Validation and Visualizations to assess the model's performance.

## Requirements
- Python 3.x
- Jupyter Notebook
- Anaconda (recommended for managing packages and environments)
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - yellowbrick
## Project Structure
- mpg_analysis.ipynb: The Jupyter Notebook containing the analysis code.
# Key Steps in the Project
# 1. Exploratory Data Analysis (EDA):
  - Univariate, bivariate, and multivariate analysis of key variables (e.g., `mpg`, `cylinders`, `horsepower`, `origin`).
  - Visualizations using Seaborn and Matplotlib for better understanding of variable distributions and relationships.
# 2. Feature Engineering:
  - Derived a new feature `age` from `model_year`.
  - Converted categorical variables `origin` to dummy variables for easier model processing.
# 3. Linear Regression Model:
  - Built an initial Linear Regression model.
  - Evaluated the model using:
    - R-squared Score
    - Mean Absolute Error (MAE)
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
  - Results show an R2 score of 0.78 on the test data.
# 4. Cross-Validation:
  - Implemented 10-fold cross-validation to evaluate model consistency.
  - Improved the R2 score to 0.81 with cross-validation.
  - Analyzed negative MSE for further insights.
# 5. Visualizations:
  - Used Yellowbrick to visualize prediction errors and residuals, improving the understanding of model performance and highlighting potential overfitting.
# Contributing
Feel free to submit issues or pull requests if you have any improvements or suggestions for the project.
