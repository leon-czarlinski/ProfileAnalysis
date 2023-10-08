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

On this project, I won't cover all the steps, but the ideia is to show how Google sees the process to transform data into insights. We will focus on asking, preparing, processing, and analyzing the data, based on a given data set, available on [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data).

## Tasks in this project

1. Understand the problem statement
1. Import libraries and data sets
1. Perform exploratory analysis and data visualization
1. Clustering with K-MEANS and DBSCAN
1. Conclusions

## Data Source
For this project we will be using a data set called **Mall Customer Segmentation Data** available at [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data). This is a structured data set, meaning that data it's organized in a certain format, such as rows and columns. 

The data set includes 200 records and 5 columns, providing information about the shop's customer base. Each column represents a specific aspect of the customer's profile, including their **customer id, gender, age, annual income in $, and spending score**. Let's dive deep into each feature:

1. **Customer ID**: Unique ID assigned to the customer.
1. **Gender**: Gender of the applicant (Male or Female).
1. **Age**: Represents the age of the applicant. Indicates the applicant's maturity level (from 18 to 70).
1. **Annual Income (k$)**: Annual Income of the customer.
1. **Spending Score**: Score assigned by the mall based on customer behavior and spending nature (1-100).


## Code Souce
To develop the analysis, I used the notebook available on **Kaggle**. [Click here](https://www.kaggle.com/code/leonczarlinski/clustering-k-means-and-dbscan/notebook) to access the file and see the results. Feel free to fork the repository and build your own analysis. 

Check some of the libraries used to develop the analysis:

```
  #Data
  import pandas as pd
  import numpy as np
  
  #Data Visualization
  import matplotlib as plt
  from matplotlib import style
  
  #Clustering Models
  import seaborn as sns
  from sklearn.cluster import DBSCAN, KMeans
  
  #Ignore Warnings
  import warnings
  warnings.filterwarnings('ignore')
  
  #cd to directory with file
  import os
  for dirname, _, filenames in os.walk('/kaggle/input'):
      for filename in filenames:
          print(os.path.join(dirname, filename))
```
**Enjoy the content**

