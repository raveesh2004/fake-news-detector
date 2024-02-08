# Fake News Detector :

## Data Analysis
- It is the process of systematically applying statistical and/or logical techniques such as cleaning, transforming, and modeling data to discover useful information for business decision-making. 

## Dataset used 
[https://github.com/raveesh2004/fake-news-detector/blob/main/True%20news%20dataset.zip
](url)

## Important instructions
- **python version should be *latest***

## Technologies used :
### Language 
- *Python*- for programming and writing logic.
  
### Python libraries 
-   matplotlib, numpy, pandas,scikit_learn,seaborn,re,string.
### Algorithms 
- Machine Learning Algorithms such as Logistic Regression ,Random Forest Classifier ,Decision Tree Classifier and Gradient Boosting Classifier.

## Working of the app :
### Import libraries and dataset.
- First of all,import all the required modules and libraries of python.
- Then, the csv file is loaded to obtain dataset.
- Since our file does not have a lot of null values, or severe issues, we will just replace extra space by null values in the dataset, and it will be ready to use.
- The basic design and menu options are created. The navigation bar, home screen and about section details are added.

### Adding functionality : 1- feature
- Next, for the visual representation feature, a select menu is created for selecting features of cars, and to choose types of graphs. 
- The different types of graphs such as bar, line, area, scatter, pie, donut chart are visualised using the plost library of streamlit.
> - **Plost**- *is a deceptively simple plotting library for Streamlit, used for depicting data in the form of beautiful charts and graphs.*
- The dataset data is worked on and processed by several computations using the NumPy and Pandas library of Python.
> - **NumPy**- *It is  a Python package used for performing the various numerical computations and processing of the multidimensional and single-dimensional array elements.*
> - **Pandas**- *It is an open source Python package that is used for data science/data analysis and machine learning tasks.*
![Screenshot (166)](https://user-images.githubusercontent.com/83575900/170860329-6aa9baf5-f199-4689-b8d5-9fe3138f9631.png)

### 2- feature
- For the Dependency and analysis, similar menu , along with few conditions are applied, and feature to select type of graph is created. 
- Again, plost library of streamlit is used for visualization.
![Screenshot (167)](https://user-images.githubusercontent.com/83575900/170860335-7cd0aedb-2fdf-4b3c-a9b0-ff62f0b97bd1.png)

### 3- feature
- For the Price prediction feature, two models of Machine learning- Linear Regression and SVM Regression are made, and their pickle files are used in the app, for the prediction of price of cars, by taking input of features of the car. 
- These models are imported from sklearn library of Python.
> - **Sklearn**- *The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction.*
> - **Linear Regression**- *It is a Machine Learning is used to predict the value of a variable based on the value of another variable.*
> - **SVM Regression**- *It is a supervised learning algorithm that is used to predict discrete values.*
![Screenshot (168)](https://user-images.githubusercontent.com/83575900/170860343-f286673b-de82-41de-9dcc-3770fb4c58ce.png)

### 4- feature 
- For the Automobile News generation, the news is shown on the app using the NewsAPI. It is extracted in a JSON format, hence converted to the readable text and all the details such as news headline, author, source, description, etc are displayed on the web page.
> NewsAPI link - [https://newsapi.org/docs/endpoints/everything](url)
![Screenshot (169)](https://user-images.githubusercontent.com/83575900/170860350-873f1207-e385-4128-80c8-ecb8a1b1a01f.png)

### 5- feature
- Next, for the resolve queries section, three queries related to automobiles are chosen and a selection menu is created, to allow the user to choose a query to resolve. 
- Specific logic is written, utilizing the dataset to solve these queries to display the maximum or minimum values of a car feature, etc. 
- For the 'Grouping and Segmentation' query, K-Clustering Algorithm to form different groups which could depict best combinations of two features which most of the automobiles uses. A scatter graph is displayed to view these groups and segmentation.
> **K-Clustering Algorithm** -*It is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabeled dataset on its own without the need for any training.*

## Functionality & features :
### 1. Visual Representation :
- You can visually represent the different features of cars such as engine size, length, width, horsepower, etc in the form of various *charts and graphs* such as bar, line, area, scatter, pie, donut chart. The charts and graphs are **interactive**; you can choose or select one or more features, and also the type of graphs.








## Application of Fake News Detection 
- In automobile industry, analyzed data is used to improve the customer experience, where data grouping and segmentation can lead to more *effective marketing and improved customer engagement , more targeted one‑to‑one offers* and can help the automobile industry to correctly manage the features and price of cars. 
-The analyzed data can be used for changing the **auto business, support mechanization, and boost automation.**
