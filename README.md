# Covid-19 Tweet Analysis

![covidd](https://user-images.githubusercontent.com/109813094/213919400-65a6815b-5ffd-45f2-a8e4-1662b3c25ed8.jpg)


# Problem Statement

The pandemic illnesses that are currently plaguing the world, in particular, pose major issues for the population on all fronts: economic, emotional, status, planning, and politics, in addition to the complexity of customs, ethics, personal psychology, and social behaviour of individuals. Therefore, when difficult situations happen, it is essential and required to analyse people's views. Observing how people respond to this threat can reveal crucial details about how society behaves and responds to unforeseen events, whether positively or negatively. At the moment, the internet and social media have evolved into potent tools for gathering people's opinions and comments on a variety of subjects. The major goal is to create a prediction model that could aid in anticipating a tweet's sentiment.

Links: Project Presentation: Slideshow Dataset : Dataset

# Attribute Information
 Location
 Tweet at
 Original Tweet
 Sentiments
 
# Project Flowchart:

 Loading data and Diagnosing the data
 Data Filtering
 EDA of Row data to understand inside correlations
 Feature Engineering
 Feature Selection 
 Model Building
 Model Training and Testing
 Model Evalution & Hyper Perameter tuning
 
# Steps involved doing this project:-

Null values treatment and data cleaning: Data cleaning is a crucial phase in the data analytics process where you either update or eliminate information that is inaccurate or badly formatted. Zero values treatment using various techniques. We currently have our dataset, which is unprocessed and raw. In this phase, we'll clean up our data by removing the columns that won't be used in our study. Our dataset consists of about 8760 rows and 14 columns. We left it alone because there were no null values.
Exploratory Data Analysis: Exploratory data analysis is a method of data analysis that involves gathering and summarising the information's key features and employing straightforward visualisation to make it easier to understand.
importing the essential libraries and modules

The following libraries are being imported for their respective applications:

Pandas: Pandas is a tool for data analysis. It offers tools for data exploration, cleaning, analysis, and manipulation.

Matplotlib:- Matplotlib is a graph plotting library in python that serves as a visualization utility. Most of the Matplotlib utilities lie under the pyplot submodule.

Numpy:- NumPy is a Python library used for working with arrays. It also has functions for working in the domain of linear algebra, Fourier transform, and matrices.

SciKit:- Scikit-learn (Sklearn) is the most useful and robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistent interface in Python. This library, which is largely written in Python, is built upon NumPy, SciPy and Matplotlib.

Plotly:- The plotly is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.

Seaborn:- Seaborn is a library that uses Matplotlib underneath to plot graphs. It will be used to visualize random distributions.

Datetime:- The Datetime module supplies classes for manipulating dates and times. While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.

Statsmodels:- Statsmodels is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration.

# Models Used

 Naive Bayes
  Stochastic Gradient Descent (SGD)
  Random Forest
  Support Vector Machine
  Logistic Regression
________________________________________
# Conclusions:

This model focuses on analysing how individuals are responding to the pandemic, taking into account that the COVID-19 disease is a global health issue that has impacted most countries' economies. The model's major objective is to determine, using machine learning algorithms and NLP approaches, if the public's sentiment is favourable or negative. Although the analysis discovered a variety of opinions, it appears that people generally continue to have a positive attitude toward the pandemic. The only month in which negative thoughts predominated was January, and the month in which the COVID-19 disease was declared a pandemic and many countries began to implement care measures and safety protocols is March, which also happens to be the month in which positive thoughts began to increase.

# In conclusion, 38% of users displayed negative emotions, whereas 62% of users displayed happy emotions.
