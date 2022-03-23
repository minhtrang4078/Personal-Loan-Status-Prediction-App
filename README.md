# Personal Loan Status Prediction App

First look of the app
![app](https://github.com/minhtrang4078/Personal-Loan-Status-Prediction-App/blob/main/images/app.png)

## Contents

  - [Short description](#short-description)
    - [Problem statement](#problem-statement)
    - [Choice of algorithm](#choice-of-algorithm)
    - [The data](#the-data)
  - [Demo video](#demo-video)
  - [Project roadmap](#project-roadmap)
  - [Model efficiency](#model-efficiency)

## Short description

### Problem statement
LendingClub company provides P2P lending, which becomes more and more popular. Investors are responsible for their own decision on lending. Even though the company has fitter borrowers who meet the minimum requirements, there is still a huge risk of non-repayment. This is the problem that this project works on by making the prediction of loan status for these people.

The final product of this project is a localhost web app that presents an explanation dashboard of a predictive model to classify which customers fall into categories of 'Fully Paid' or Charged Off'. End-users can understand the model as well as receive predictive results for a new customer.

In brief, this project is created with the purpose of:

- improving profitability for the lenders
- providing a lightweight tool to support the process of decision making
- an app with an easily used interface

### Choice of algorithm

XGBoost is chosen in this project because of some important characteristics (Chen & Guestrin, 2016):
- For a big data sample:
  - sparsity-aware split finding algorithm to handle the problem of missing values in the data
  - For a big dataset – training speed: fast

- In practice:
  - Python package of XGBoost 
  - Parallelization of tree construction
  - Out-of-Core Computing 
  - Cache Optimization

### The data
- Data is downloaded from Kaggle and unzipped into Loan_status_2007-2020Q3.gzip and LCDataDictionary.xlsx.
 (https://www.kaggle.com/ethon0426/lending-club-20072020q1?select=Loan_status_2007-2020Q3.gzip)
- Duration: 2007-2020
- Currency: USD
- Data contents:
  - Loan Characteristics such as loan amount, term and purpose
  - Demographic data such as employment status, employment length and house ownership
  - Behavioral data related to historical payments
  
## Demo video
- Deployment of Dash web app:
https://youtu.be/jhyVX7xmxlE
[![Watch the video](https://github.com/minhtrang4078/Personal-Loan-Status-Prediction-App/blob/main/images/video.png)](https://youtu.be/jhyVX7xmxlE)

## Project roadmap
This project use the most popular approach of the Cross-Industry Standard Process for Data Mining (CRISP-DM), (Wirth et al.,2000, p.6). The framework as below:

1.Problem statement/Business understanding

2.Data Understanding (Exploratory Data Analysis)

3.Data Preparation

4.Modeling development

5.Evaluation/Interpretation

6.Communication/Deployment

## Model efficiency
Overall accuracy of prediction is ~70%
This project is done within 4 months, and there are still rooms for improvement.
