# Recommendations-with-IBM
Udacity Data Science Nanodegree

## Table of contents
* [Dataset](#dataset)
* [Context](#context)
* [Setup](#setup)
* [Results](#results)

## Dataset
This data is taken from Udacity from data science nanodegree program for the capstone project.                    
There are 286000 logs for 225 customers activities on the service in this dataset. 

## Context
Analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

I. Exploratory Data Analysis

Before making recommendations of any kind, we have to explore the data we are working with for the project. Dive in to see what we can find. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. 

II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

IV. Matrix Factorization

Finally, complete a machine learning approach to building recommendations. Using the user-item interactions, We will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). Finally discuss which methods you might use moving forward, and how you might test how well the recommendations are working for engaging users



## Setup
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

* Pyspark
* NumPy                                         
* pandas                                                   
* Matplotlib                                 
* Seaborn                                      
