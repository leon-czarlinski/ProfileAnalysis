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

On this project, I won't cover all the steps, but the ideia is to show how Google sees the process to transform data into insights. We will focus on asking, preparing, processing, and analyzing the data, based on a given data set, available on [Kaggle](https://www.kaggle.com/datasets/datascientistanna/customers-dataset) 

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

1. **Customer ID**: Unique identifier assigned to each customer in the dataset.
1. **Gender**: The gender of the customer, either male or female. 
1. **Age**: The age of the customer, measured in years.
1. **Annual income**: The annual income of the customer, measured in a currency. In this dataset there is no currency especification.
1. **Spending Score**: A score assigned by the business based on the customer's behavior and spending nature. It goes from 0 to 100.
1. **Profession**: The occupation of the customer. 
1. **Work Experience**: The number of years of work experience of the customer. 
1. **Family size**: The size of the customer's family, measured in terms of the number of family. The min is 1, meaning the person is single. 

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

