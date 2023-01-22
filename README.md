# Covid-19 Tweet Analysis


# Problem Statement

The diseases that currently affect the world, especially which are classified as pandemic, cause serious problems to the population at all levels: economic, emotional, status, planning, politics, etc., in addition to the complexity of traditions, ethics, individual psychology and social behaviour of people. Therefore, it is required and necessary a people's attitudes analysis when adverse situations arise Identifying people's reaction to this threat can provide important information on how society behaves and reacts to unwanted and unexpected situations, which can be positive or negative, currently the Internet and social networks have become powerful tools to access people’s opinions and comments on various topics The main objective is to make a predictive model, which could help in predicting the Sentiment of a tweets.

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

Data Cleaning and Null values treatment: Data cleaning is an important step in the data analytics process in which you either remove or update information that is incomplete or improperly formatted. Null values Treatment by different methods. We have our dataset in hand which is raw and unfiltered. This step involves cleaning our data first by eliminating the columns which are not needed for our analysis. We have around 8760 rows × 14 columns in our dataset.Since, there were no null values, we have left it untouched.
Exploratory Data Analysis: Exploratory Data Analysis is the approach of analyzing data, gathering and summarizing the important characteristics of the information, and using simple visualization that makes it easier to understand.
Importing necessary modules and libraries:
We are importing the following libraries for their respective applications:
Pandas:- Pandas is used to analyze data. It has functions for analyzing, cleaning, exploring, and manipulating data.
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

Taking into account that the COVID-19 disease is global health problem and has affected most countries and their economies, this model focuses on analysing people’s reaction to the pandemic. The main goal of the model is to deduce whether the sentiment of the public opinion is positive or negative by applying machine learning algorithms and NLP techniques. Despite the fact that the analysis found variation of opinions, it seems that people mostly remain positive about the pandemic, January is the only month in which negative thoughts predominated, March is the month when the COVID-19disease was declared as a pandemic and many countries started to apply care measures and safety protocols, which coincides with the rise of positive thoughts.

# To summarize, 62% of the users showed positive feelings and 38% of the users showed negative feelings.
