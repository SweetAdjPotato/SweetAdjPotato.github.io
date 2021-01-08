# Arvato_Customer_Segmentation

### Table of Contents

1. [Installation](#installation)
2. [Introduction](#Introduction)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

1. Python versions 3.7
1. Library and packages: numpy, pandas, matplotlib, sklearn, seaborn, scipy,
xgboost, bayes_opt, pickle, time

## Introduction <a name="Introduction"></a>

In this project, I analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. I first used unsupervised learning techniques (PCA and K-Means) to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company.
Then, I applied what I've learned on a third dataset with demographics information for targets of a marketing campaign for the company, and use a supervised learning model (XGBClassifier) to predict which individuals are most likely to convert into becoming customers for the company. The data used is provided by Udacity partners at Bertelsmann Arvato Analytics, and represents a real-life data science task. My main deliverable for this project will be a blog post on medium reporting important findings and conclusions.

## File Descriptions <a name="files"></a>

Data cannot be shared due to a confidentiality agreement.
There is one notebook Arvato_Project_Workbook.ipynb, with all the functions needed are written in the notebook along with the code.  

## Results<a name="results"></a>

The main findings of the code can be found at a Medium post available [here](https://zhaoyunma.medium.com/customer-segmentation-and-potential-customer-prediction-943760a4f6da).
The supervised learning model is evaluated in a [Kaggle competition](https://www.kaggle.com/c/udacity-arvato-identify-customers/leaderboard).

## Licensing, Authors, and Acknowledgements<a name="licensing"></a>

Acknowledge to [Udacity](https://www.udacity.com/) and [Arvato Financial Services](https://finance.arvato.com/en-us/) for the data.  

Acknowledge to a few repos I studied on Github: [[1]](https://github.com/OliverFarren/arvato-udacity-customersegmentation), [[2]](https://github.com/pranaymodukuru/Bertelsmann-Arvato-customer-segmentation), [[3]](https://github.com/shihao-wen/Udacity-DSND).
