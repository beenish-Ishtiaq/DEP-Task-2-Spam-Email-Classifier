# Spam_Email_Classifier
## Overview
This repository contains code for a spam email classifier developed as part of my Machine Learning internship at Digital Empowerment Network. The goal of this project is to classify emails as spam or ham (not spam) using machine learning techniques.

## Dataset
The dataset used for this project is the mail_data.csv file, which contains the following columns:  
Category: The label of the email, either 'spam' or 'ham'.  
Message: The content of the email.  

## Steps Involved
### 1. Data Preprocessing
Cleaning the data and preparing it for model training.
### 2.Feature Extraction
Transforming the text data into numerical features using TF-IDF vectorization.
### 3.Model Training
Training a Logistic Regression model to classify emails.
### 4.Model Evaluation
Evaluating the model's performance using accuracy, classification report, and confusion matrix.

## Results
The Logistic Regression model achieved the following results:  
Accuracy on training data: 0.967  
Accuracy on test data: 0.965  

## Usage
To run the code, follow these steps:  
1. Clone this repository to your local machine.  
2. Navigate to the directory containing the code.  
3. Ensure that the mail_data.csv file is in the same directory as the code.  
4. Run the script: python spam_email_classifier.py

## Conclusion
This project demonstrates the process of building a spam email classifier using Logistic Regression. The model can accurately classify emails as spam or ham based on their content. Future improvements could include experimenting with different models and techniques to further enhance accuracy.
