# Titanic_Survivors_Analysis_Decision_Tree

## Overview
This project involves the analysis of the Titanic dataset, exploring factors influencing survival, and building a machine learning model for prediction. The repository includes data cleaning, visualization, feature engineering, and model deployment.

## Top 5 Challenges and Solutions

### 1. Dealing with Missing Data
**Challenge:** The dataset contained missing values, especially in the 'Age' and 'Cabin' columns, impacting the analysis and model training.

**Solution:** I addressed missing values in the 'Age' column by filling them with the mean age. The 'Cabin' column was dropped due to a high number of missing values. Imputation and strategic column removal ensured a cleaner dataset.

### 2. Feature Engineering
**Challenge:** Selecting relevant features for the model was crucial. Deciding which columns to keep or drop required careful consideration.

**Solution:** I dropped unimportant features like 'PassengerId', 'Name', and others based on their limited impact on predicting survival. Feature importance analysis guided the selection process, enhancing the model's effectiveness.

### 3. Data Encoding
**Challenge:** The 'Sex' column contained categorical values, and machine learning models require numerical inputs.

**Solution:** I used LabelEncoder to convert 'Sex' values to numerical format (Male: 1, Female: 0), ensuring compatibility with the machine learning algorithm.

### 4. Model Selection and Training
**Challenge:** Choosing an appropriate model and training it effectively for accurate predictions posed a challenge.

**Solution:** I selected a Decision Tree Classifier as the model. Careful evaluation on both training and test sets ensured that the model achieved reasonable accuracy, balancing performance and generalization.

### 5. Model Deployment
**Challenge:** Deploying the model and creating a user-friendly interface for predictions required careful scripting.

**Solution:** I created a deployment script that takes user input for features ('Pclass', 'Sex', 'Age', 'Fare') and outputs a prediction for survival. This script enables users to interact with the model and obtain predictions for individual passengers.

## Project Structure

- **data:** Contains the dataset used for analysis.
- **notebooks:** Jupyter notebooks detailing the analysis process.
- **scripts:** Python scripts, including the deployment script.
- **README.md:** Overview of the project, challenges, and solutions.

## Usage
1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd Titanic-Analysis`
3. Follow the instructions in the notebooks and scripts for detailed analysis and model deployment.

Feel free to explore and contribute to the project!
