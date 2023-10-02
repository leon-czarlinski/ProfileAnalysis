## ProfileAnalysis
This is a hands-on project about profiles for different types of customers.
In this project we will cover the concept of **clustering**, which is a unsupervised learning algorithm that involves grouping similar data points togethes based on their characteristics. The goal of clustering is to find similarities within a dataset and group similar data points together while keeping dissimilar data points separate.

Think of this project from a business perspective. Based on the customer profile, the business can identify different clusters and customize the experience, offers, services, products, and others based on this clusterization.


## Data Analytics Methodology
**Transforming data into insights**: the six steps of data analytics include: ask, prepare, process, analyze, share, and act.

1. **Ask**: effective questions and collaborate with leaders and managers who are interested in the oucome.
1. **Prepare**: it all start with a solid preparation. During this step, the analysts identify what data they need to achieve the succesful resultthey identified in the previous step.
1. **Process**: in this step, the data analyst make sure how data would be collected, stored, managed, and prospected
1. **Analyse**: this is the moment where the data analyst dive into the data, cobine data from multiple sources, do the calculations and data validations.
1. **Share**: share the results with stakeholders involved in the project.
1. **Act**: The last stage of the process where the team of analysts work with stakeholders within their company and decide how best to implement suggestions and actions based on their fidings. 

On this project, I won't cover all the steps, but the ideia is to show how Google sees the process to transform data into insights. We will focus on asking, preparing, processing, and analyzing the data, based on a given data set, available on [Kaggle]([https://www.kaggle.com/datasets/datascientistanna/customers-dataset](https://www.kaggle.com/datasets/yashkmd/credit-profile-two-wheeler-loan-dataset) 

## Tasks in this project

1. Understand the problem statement
1. Import libraries and data sets
1. Clean the data, treating missing data
1. Perform exploratory analysis
1. Perform data visualization
1. Principal Component Analysis
1. K-Means Clustering

## Data Source
For this project we will be using a data set called **Shop Customer Data** available at [Kaggle](https://www.kaggle.com/datasets/datascientistanna/customers-dataset). This is a structured data set, meaning that data it's organized in a certain format, such as rows and columns. 

The data set includes 2,000 records and 8 columns, providing information about the shop's customer base. Each column represents a specific aspect of the customer's profile, including their **customer id, gender, age, annual income in $, spending score, profession, work experience and family size**. Let's dive deep into each feature:

1. Age: Represents the age of the applicant. Indicates the applicant's maturity level (from 18 to 70).
1. Gender: Gender of the applicant (Male, Female, Other).
1. Income: The applicant's income, which is critical in assessing their ability to repay the loan (multiples of 1000's).
1. Credit Score: A score quantifying the applicant's creditworthiness based on their credit history (from 300 to 850).
1. Credit History Length: Represents the number of months since the applicant's first credit line. Indicates the applicant's experience with credit management (in Months).
1. Number of Existing Loans: The number of loans the applicant currently has (from 0 to 10).
1. Loan Amount:The amount of money the applicant is requesting (from 0 to 150,000).
1. Loan Tenure: The number of months the applicant wants to repay the loan over (in Months).
1. Existing Customer:Whether the applicant is an existing customer of the finance company (Yes, No).
1. State: The state in India where the applicant resides
1. City: The city or village in India where the applicant resides.
1. LTV Ratio: The loan-to-value ratio, represents the ratio of the loan amount to the appraised value of the asset (typically a house). Higher LTVs can indicate higher risk. (from 40% to 95%)
1. Employment Profile: General employment category of the applicant (Salaried, Self-Employed, Freelancer, Unemployed, Student).
1. Occupation: Specific occupation or job title of the applicant.
1. Profile Score: A score ranging from 0 to 100 represents the overall profile of the applicant based on the actual loan repayment data. Higher values indicate better profiles (from 0 to 100). 

## Code Souce
To develop the analysis, I used the Colab notebook available on **GitHub**. [Click here](https://github.com/leon-czarlinski/ProfileAnalysis/blob/main/ProfileAnalysis.ipynb) to access the file and see the results. Feel free to fork the repository and build your own analysis. 

Check some of the libraries used to develop the analysis:

```
import pandas as pd #used for data frame manipulation
import numpy as np #used for numerical analysis
import seaborn as sns #used for data visualization
import matplotlib.pyplot as plt #used for data visualization
import warnings
warnings.filterwarnings("ignore")
```
**Enjoy the content**

