# Titanic Survival Prediction Notebooks

This directory contains Jupyter Notebooks for the Titanic Survival Prediction project. Each notebook focuses on a specific aspect of the machine learning pipeline, including exploratory data analysis, preprocessing, model training, and evaluation.

## Notebooks Overview

### 01_eda.ipynb
**Exploratory Data Analysis (EDA)**

- **Purpose**: Perform exploratory data analysis to understand the dataset, including the distribution of features, missing values, and initial insights into survival rates.
- **Key Tasks**:
  - Load and inspect the dataset.
  - Visualize the distribution of key features.
  - Analyze survival rates by various categories (e.g., passenger class, sex).
  - Identify patterns and relationships in the data.

### 02_preprocessing.ipynb
**Data Preprocessing**

- **Purpose**: Clean and preprocess the dataset to prepare it for modeling. This includes handling missing values, encoding categorical variables, and scaling features.
- **Key Tasks**:
  - Handle missing data.
  - Encode categorical features.
  - Normalize or standardize numerical features.
  - Prepare training and test sets.

### 03_model_training.ipynb
**Model Training**

- **Purpose**: Train various machine learning models on the preprocessed data to predict passenger survival.
- **Key Tasks**:
  - Select and implement machine learning algorithms (e.g., logistic regression, decision trees, random forests).
  - Train models using the training data.
  - Tune hyperparameters and evaluate model performance.

### 04_evaluation.ipynb
**Model Evaluation**

- **Purpose**: Evaluate the performance of the trained models and compare their results.
- **Key Tasks**:
  - Assess model performance using metrics such as accuracy, precision, recall, and F1 score.
  - Compare the performance of different models.
  - Visualize results and draw conclusions about the best-performing model.

## Additional Information

- **Dataset**: The dataset used in this project is the Titanic dataset, which can be found [here](https://raw.githubusercontent.com/Deepayan-Thakur/Machine-Learning-Projects/main/Project1/data/raw/titanic.csv).
- **Libraries Used**: 
  - `pandas` for data manipulation.
  - `seaborn` and `matplotlib` for data visualization.
  - `scikit-learn` for machine learning algorithms and evaluation.

Feel free to explore each notebook to understand the full pipeline of the Titanic Survival Prediction project. For further details or questions, please refer to the individual notebooks or contact the project maintainer.
