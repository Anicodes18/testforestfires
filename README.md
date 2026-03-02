**lab - flask**

To run flask application:
python app.py

To access your flask application open new tab and paste the url:
http://{your_url}:5000/

📌 Problem Statement

Forest fires cause severe environmental and economic damage, making early risk prediction critical for prevention and resource planning.
This project uses the Algerian Forest Fires dataset to:
1. Predict the likelihood of forest fire occurrence based on meteorological and environmental features
2. Identify key factors influencing fire risk
3. Translate a trained machine learning model into a production-ready web application

🎯 Objective
The objective of this project was to:
1. Build and evaluate a machine learning classification model
2. Develop a user-friendly web interface for real-time predictions
3. Deploy the application to the cloud
4. Implement a CI/CD pipeline for automated updates

📂 Dataset Overview

The dataset includes environmental and weather-related features such as:
1. Temperature
2. Relative humidity
3. Wind speed
4. Rainfall
5. Fire Weather Index (FWI) (target variable)

The goal was to predict the Fire weather Index value based on these inputs.
🔍 Approach
1️⃣ Data Preprocessing
Data cleaning and handling missing values
Feature selection and transformation
Train-test split

2️⃣ Model Development
Trained regression models
Evaluated performance using appropriate metrics (Mean Absolute Error (MAE), R2-score)
Applied hyperparameter tuning to improve generalization

3️⃣ Web Application Development
Built a Flask-based web application
Designed input forms for environmental parameters
Integrated the trained ML model for real-time predictions

4️⃣ Deployment & Automation
Deployed the application using AWS Elastic Beanstalk
Configured AWS CodePipeline for continuous integration and automated deployment
Integrated version control with GitHub

🤖 Model Evaluation
Models were evaluated using regression metrics to ensure balanced performance and to reduce overfitting.
The final selected model demonstrated strong predictive capability on unseen data.

🛠 Tech Stack
Python | Scikit-learn | Flask | AWS Elastic Beanstalk | AWS CodePipeline | Git | matplotlib | seaborn

🚀 Business Impact

This project demonstrates how predictive analytics can be operationalized into a deployable decision-support system.
Potential applications include:
1. Early wildfire risk detection
2. Environmental monitoring systems
3. Forestry department planning and response optimization
4. Risk assessment for disaster management agencies

By deploying the model as a live web application with CI/CD integration, this project bridges the gap between data science experimentation and production-level deployment.
