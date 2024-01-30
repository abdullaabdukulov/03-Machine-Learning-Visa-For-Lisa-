# Welcome to the Visa for Lisa Project

## Task
<div class="row">
<div class="col tab-content">
<div class="tab-pane active show" id="subject" role="tabpanel">
<div class="row">
<div class="col-md-12 col-xl-12">
<div class="markdown-body">
<p class="text-muted m-b-15">
</p><h2>Visa For Lisa</h2>
<table>
<thead>
<tr>
<th>Technical details</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Submit file</td>
<td>*.ipynb</td>
</tr>
</tbody>
</table>
<hr>
<h1>Visa For Lisa</h1>
<p>This project is about a bank (Galaxy Bank) whose management wants to explore converting some of its deposit customers to become personal loan customers (while retaining them as depositors). In short, they want to upsell customers to purchase more banking products from Galaxy Bank.</p>
<p>The bank has had some previous success in upselling to its deposit clients. Still, unfortunately, not all clients offered a loan by Galaxy Bank accept it and become a loan customers. The bank's campaign last year for its customers showed a healthy loan acceptance conversion rate of over 9%. This data has encouraged the marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.</p>
<p>The bank wants to predict better and identify who will accept loans offered to potential loan customers. It will help make their marketing efforts more effective with higher conversion rates.</p>
<p><em>Your mission</em></p>
<p>Your mission is to help Galaxy Bank improve its marketing conversion rates by allowing them to target and predict which of their deposit clients are most likely to accept a loan offer from the bank. You will be meeting with the marketing leadership at the bank.</p>
<p>What are the success criteria?</p>
<ul>
<li>During our next meeting, you will have to show us some data (plot? report?) of what you've been building.</li>
<li>What do you think will happen to the conversion rate?</li>
</ul>
<p>Your deliverables:</p>
<ul>
<li>A presentation with slides.</li>
<li>Code that the DevOps team should be able to push to production.</li>
</ul>
<p>You've heard the CEO will be joining the meeting. It's a reminder that, if you do well, you could quickly expect the promotion you have been hoping for.</p>
<h2>Technical specification</h2>
<ul>
<li>Implement a multi-variable linear regression model on a large and complex data set</li>
<li>Analyze and evaluate the implications of your model on real-life users</li>
<li>Analyze and evaluate the risk to the business of the implications, assumptions, and decisions in your model</li>
</ul>
<p>What to expect: the five stages of your project
In this project, you should expect to cover the five major stages of working with data:</p>
<ol>
<li>Data Collecting / Cleaning</li>
<li>Data Exploration</li>
<li>Data Visualization</li>
<li>Machine Learning</li>
<li>Communication</li>
</ol>
<p>You will have to prove yourself in each of these. We are confident that you will succeed! :)</p>
<p>Where to find the data?</p>
<ul>
<li><a href="https://storage.googleapis.com/qwasar-public/track-ds/Visa_For_Lisa_Loan_Modelling.csv" target="_blank">Loan DataSet</a></li>
</ul>
<p>Reminder, this will be one of your portfolio projects. :-)</p>

<p></p>
</div>

</div>
</div>
</div>
<div class="tab-pane" id="resources" role="tabpanel">
<div class="row">
<div class="col-xl-12">
<div class="row text-center">
<div class="col p-t-10 f-12">
<p>
How To Use Jupyter In Docode
</p>
</div>
</div>
<div class="row text-center">
<div class="col">
<a frameborder="0" href="https://www.youtube.com/embed/J5MpsvScKzE">Jupyter Notebook</a>
</div>
</div>

</div>
</div>
</div>
</div>
</div>

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
