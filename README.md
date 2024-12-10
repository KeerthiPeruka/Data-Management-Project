# LinkedIn Job Posting Success Analysis
The objective of this project is to analyze the factors influencing the success rate of employers in finding suitable candidates for their job postings on LinkedIn. Using a dataset from Kaggle, the project will develop models that provide detailed insights into the components driving this process. This will help employers make informed decisions on how to refine their job descriptions and implement changes to attract better-qualified applicants or increase the overall number of applications.

## Dataset 
The dataset that this project uses can be found at Kaggle: https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data

## Features 
- Data Preparation
   - Importing Libraries
   - Reading the Dataset
- Data Cleaning
   - Handling Missing Values
   - Standardizing Data Format
- Feature Engineering
   - Creating New Data Columns
   - One-Hot Encoding Categorical Features
   - Removing Outliers
- Data Storage
   - Saving Data Statistics in SQLite
   - Storing Cleaned Dataset in SQLite
- Data Visualization
   -  Bar Charts
      - Top Job Locations
      - Employment Type Distribution
   -  Histogram
      - Salary Distribution   
   -  Correlation Matrix
      - Correlation of Features with Job Applications    
   -  Scatter plot
      - Comparing Application vs. Views    
- Machine Learning
   - Splitting Data into Training and Test Data
   - Regression Models
     - Random Forest
     - Linear Regression
     - Gradient Boosting    
- SQL Components
   - Storing Model Predictions and Metrics in SQLite
   - Retrieving and Querying Data from SQLite

## File Structure 
- file_name.ipynb : Jupter notebook with main code for data analysis and model training
- cleaned_postings.csv : Cleaned dataset after preprocessing
- job_postings_encoded.csv : One hot encoded dataset for machine learning models
- linkedin_postings.db : SQLite database for storing cleaned dataset and results from the model

## Setup Instructions

### 1. Ensure Following Libraries Can Run 
  - pandas
  - numpy
  - matplotlib.pyplot
  - seaborn
  - sqlite3
  - sklearn
  - sqlalchemy

### 2. Running the Analysis Notebook 
Open and run each cell of the Jupyter Notebook linkedin_anyalsis.ipynb to observe the models and findings. 

## Demo Video 
For a more in-depth understanding of the content in this project, the demo video can be found at: 
