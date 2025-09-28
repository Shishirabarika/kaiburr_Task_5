# Consumer Complaint Classification

This project classifies consumer complaints into four categories:  
**Credit Reporting, Debt Collection, Consumer Loan, and Mortgage**.  

It uses **TF-IDF vectorization** and **Logistic Regression** to predict the category of a complaint from its text.

---

## Features

- Cleans and preprocesses complaint text (lowercasing, punctuation removal, stopword removal)  
- Converts text to TF-IDF vectors  
- Trains a Logistic Regression model  
- Evaluates model performance with classification report and confusion matrix  
- Allows easy prediction for new complaint texts  

---

## Installation

1. Clone this repository: 

```bash
git clone https://github.com/Shishirabarika/consumer-complaint-classifier.git
cd consumer-complaint-classifier
pip install -r requirements.txt
