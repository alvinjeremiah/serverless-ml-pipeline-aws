🚀 AWS End-to-End Machine Learning Pipeline

📌 Overview

This project demonstrates an end-to-end serverless machine learning pipeline built using AWS services. The pipeline ingests data, preprocesses it automatically, trains a regression model, and generates predictions within a managed cloud environment.

Built as a hands-on implementation after completing AWS AI Practitioner certification.

🏗 Architecture

Services Used:

  Amazon S3 – Data storage
  
  AWS Lambda – Automated preprocessing
  
  Amazon SageMaker – Model training & inference
  
  IAM Roles – Secure service communication

🔄 Workflow

User uploads CSV to S3 (raw folder)

S3 triggers Lambda

Lambda cleans and preprocesses data

Processed data stored in S3

SageMaker Notebook loads processed data

Model training using Scikit-learn

Predictions generated

🧠 Machine Learning Details

Model: Linear Regression

Feature Engineering: Basic preprocessing & encoding

Evaluation Metric: R² Score

🔐 Security

Implemented IAM roles with least privilege access

Configured trust policies for SageMaker execution role

🛠 Technologies

Python

Pandas

Scikit-learn

AWS Cloud Services

📚 Key Learnings

Designing serverless ML workflows

Handling IAM permissions & trust policies

📌 Future Improvements

Deploy real-time SageMaker endpoint

Integrate API Gateway

Add automated monitoring

👨‍💻 Author

Alvin Jeremiah
