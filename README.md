# Reed's Portfolio 
## Project 1: Loan Default Predictions - Applied Machine Learning (https://github.com/reedlabar/Loan-Default-Predictions)

**Purpose**:
This project aimed to predict the likelihood of loan defaults using various machine learning techniques. The dataset was pulled Lending Club found on Kaggle.com. We hoped to support lending decision-making by identifying key factors that contribute to loan defaults.

**Actions Taken**:

*Data Preprocessing*: The original dataset contained over 39,000 records with 110 features, which was cut down to 49 columns after feature selection and outlier removal. We transformed both qualitative and quantitative data and normalized key features for model accuracy.

*Model Development*: Several models were tested, including Linear Regression, Artificial Neural Networks (ANN), k-Nearest Neighbors (k-NN), and Random Forests. We used feature selection techniques, including a correlation matrix and VIF, to identify important predictors such as interest rates and annual income.

*Model Evaluation*: The Random Forest model achieved the highest accuracy at 98%, with key variables like interest rate and annual income being significant predictors of loan defaults. The ANN model had lower accuracy, indicating sensitivity issues, particularly in predicting loan denials.

**Results**: The Random Forest model was the most effective, accurately predicting 38,391 loan statuses with a 98% accuracy rate. The model had a strong performance in identifying defaults, although misclassifications was seen with loans classified as fully paid but predicted as charged off. The dataset did have more records of people who did not default on their loans compared to those who did. Random Forest was good at handling such imbalances because it uses multiple decision trees and aggregates their results, reducing the bias toward the majority class.

## Project 2: Salary Prediction Model for MLB Free Agents (https://github.com/reedlabar/Salary-Predicition-Model)

**Purpose**: The purpose of this project was to develop a predictive model to determine the salaries of Major League Baseball free agents based on their on-field performance metrics. This model aimed to assist a small-market MLB team in negotiating fair contracts with free agents by identifying undervalued players using data analytics.

**Actions Taken**: 
*Data Exploration*: Initially, the dataset containing 238 rows of player statistics and salary information from 1998 to 2013 was explored to understand the variables and their relationships using correlation testing.

*Model Development*: Multiple regression models were constructed to predict player salaries. Both explanatory and predictive models were considered to ensure accuracy and interpretability. Key variables, including on-base percentage (OBP), slugging percentage (SLG), and plate appearances (PA), were included in the models.

**Results**: The model successfully identified key performance metrics that impact player salaries, with OBP being a significant predictor. The analysis also highlighted players who were either overvalued or undervalued.

## Project 3: Win Simulator (https://github.com/reedlabar/Win-Simulator)

**Purpose**:
This project was an extension of my Salary Prediction Model, designed to predict the number of wins for a sports team using the same variables that influenced player salaries. My goal was to create an interactive tool that allows users to pick three hitters and see the number of wins they would get.

**Actions Taken**: Data Collection and Preparation: I used the same dataset and variables from the Salary Prediction Model, ensuring consistency in the factors influencing both salary and team success. I organized the data to be compatible with a win prediction model.

*Model Development*: I developed a predictive model using the existing variables to estimate the number of wins out of 162 games (a full MLB season). The focus was on ensuring the model was interactive for users.

*User Interaction*: I integrated the win prediction model into a dashboard, allowing users to simulate different outcomes by adjusting the already selected variables from the salary prediction model. This interactive feature helps users understand how these key factors contribute to a team’s overall success.

**Results**: The model provided reliable win predictions based on the existing variables. By interacting with the dashboard, users can simulate how changes in key factors might affect the number of wins.



