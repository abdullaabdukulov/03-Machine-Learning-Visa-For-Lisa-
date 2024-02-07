# Visa for Lisa Loan Modelling Project

## Overview
The Visa for Lisa project aims to enhance Galaxy Bank's marketing conversion rates by predicting which deposit clients are most likely to accept a loan offer. The project involves implementing a multi-variable linear regression model on a large and complex dataset.

## Key Features
- **Data Collection / Cleaning:**
  - Utilizes a dataset from a Google Cloud Storage link.
  - Removes the 'ID' column for data cleaning.

- **Data Exploration and Visualization:**
  - Custom class `DataSet` for summarizing dataset statistics and visualizing data distributions.
  - Various plots, such as displot, heatmap, pie chart, scatter plot, and pair plot, for exploration.

- **Machine Learning:**
  - Implements classification models using Scikit-learn library.
  - Custom class `MLClass` streamlines training, prediction, and evaluation processes for multiple models.
  - Evaluation metrics include accuracy score, cross-validation score, mean squared error, and confusion matrix.

- **Model Saving and Loading:**
  - Saves the most accurate models (RandomForestClassifier and GradientBoostingClassifier) using the pickle library.
  - Functions `save_model` and `open_model` are defined for saving and loading models.

## Installation
To run this project, install the required libraries using the following commands:
```bash
pip install pandas matplotlib seaborn scikit-learn pyarrow
```

## Usage
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code:**
   - Open and run the provided Jupyter Notebook or Python script.
   - Ensure that the necessary dataset is available or modify the code to use your dataset.

4. **Explore Results:**
   - Check the generated visualizations and explore the insights gained from the data.
   - Examine the machine learning model evaluation scores.

5. **Save/Load Models:**
   - Use the provided functions to save and load the most accurate models for future use.

