# UDA Final Project - Text Analysis Tasks

This repository contains the code and data for the **UDA Final Project** by **Yanran Xu (CID: 02351471)**. The project focuses on applying Natural Language Processing (NLP) techniques, including traditional Machine Learning (ML) and Deep Learning (DL) models, to classify mutual funds based on their investment strategies.

---

## Project Description
Mutual funds are an essential component of modern investment portfolios, but understanding and categorizing their investment strategies can be challenging. This project addresses these challenges by:
1. Preprocessing mutual fund prospectus summaries.
2. Performing text clustering to explore patterns in the data.
3. Building classification models, including traditional ML models (Logistic Regression, SVM, Random Forest) and DL models (CNN, RNN).
4. Fine-tuning the CNN model for improved accuracy.

The classification task focuses on categorizing mutual funds into the following investment strategy categories:
- **Balanced Fund (Low Risk)**  
- **Fixed Income Long Only (Low Risk)**  
- **Equity Long Only (Low Risk)**  
- **Long Short Funds (High Risk)**  

---

## Repository Contents
- **UDA_FinalProject_Xu_code.ipynb**: The main Jupyter Notebook containing all the code for data preprocessing, clustering, and classification.  
- **UDA_FP_Code and Data_XU.zip**: A compressed file containing the code and fund data used for the project.  
- **README.md**: This file, providing an overview of the project.  

---

## Setup and Requirements
To run the code, you need the following:
- **Python 3.8 or later**
- Required Python libraries:  
  - `numpy`  
  - `pandas`  
  - `scikit-learn`  
  - `nltk`  
  - `tensorflow`  
  - `matplotlib`
  - `networkx`
  - `spectralcluster`

Install the libraries using:
```bash
pip install -r requirements.txt
