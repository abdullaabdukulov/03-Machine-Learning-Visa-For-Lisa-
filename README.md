# Welcome to the Visa for Lisa Project

## Description
The Visa for Lisa project focuses on helping Galaxy Bank enhance its marketing conversion rates by predicting which deposit clients are most likely to accept a loan offer. This project involves implementing a multi-variable linear regression model on a large and complex dataset, with the goal of improving the effectiveness of targeted marketing campaigns.

### Key Project Stages
1. **Data Collection / Cleaning:**
   - Utilizes a dataset from a Google Cloud Storage link.
   - Pandas library is used for loading and cleaning the dataset, removing the 'ID' column.

2. **Data Exploration and Visualization:**
   - Custom class `DataSet` provides methods for summarizing dataset statistics and visualizing data distributions.
   - Various plots such as displot, heatmap, pie chart, scatter plot, and pair plot are used for exploration.

3. **Machine Learning:**
   - Scikit-learn library is employed for implementing classification models.
   - Custom class `MLClass` streamlines the training, prediction, and evaluation processes for multiple models.
   - Evaluation metrics include accuracy score, cross-validation score, mean squared error, and confusion matrix.

4. **Model Saving and Loading:**
   - Most accurate models (RandomForestClassifier and GradientBoostingClassifier) are saved using the pickle library.
   - Functions `save_model` and `open_model` are defined for saving and loading models.

## Installation
To run this project, you need to install the required libraries. Use the following commands:

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
