# Anomaly Detection, 3 day course

Welcome to the course material and home of Acumed Training's Anomaly Detection course: 
- **Day 1**: What is an anomaly and the basics of Python Pandas
- **Day 2**: Finding anomalies with machine learning
- **Day 3**: Building better historic profiles 

## Course prerequisites
|    | Requirement |
|---:|--- |
| Must | Some experience developing or at least scripting in Python |
| Must | A numerate background, ideally some basic statistics | 
| Optional | Experience using Python Pandas |
| Optional | A background in machine learning | 

**Note this course outline may change slightly**

## **Day 1**: What is an anomaly and the basics of Python Pandas
Course outline:
 - What are anomallies? and some ways of finding them
  - Regression / curve fitting 
  - Clustering 
  - Classification
 - Quick review of some important concepts 
  - Mean and variance
  - Normal distributions 
  - Single tail / two tail tests
  - How much data is enough?
 - Python Pandas
  - Data structures ( Series, DataFrames )
  - Selecting data
  - Calculating statistics 
  - Plotting
 - **Excercise 1**: Manipulating data with DataFrames

## **Day 2**: Finding anomalies with machine learning
 - Regression
  - The theory
   - Fitting straight lines
   - Fitting curves to data
  - Using Pandas / Scikit is easy
  - **Excercise 2**: Simple linear regression with Pandas
 - Classification ( categories known, supervised machine learning ) 
  - Decision trees
  - **Excercise 3**: Build an Decision Tree anomaly detector 
  - Bayesian classifiers
  - **Excercise 4**: Build Bayesian anomaly detector
 - Clustering ( categories not known, unsupervised machine learning ) 
  - K nearest neigbour
  - **Excercise 5**: Build a K-Nearest Neigbour anomaly detector

## **Day 3**: Building better historic profiles
 - What is profiling?
  - Understand seasonal / daily variations
  - Needs more data
 - **Excercise 6**: Build hourly user profiles
 - Twitter's anomaly detection algorithm
  - Temporal decomposision
  - Variation Student t-test
 - **Excercise 7**: Build anomaly detector that:
  - does user profiling
  - splits the signal into three composite signal (trend, periodic, random)
  - finds outliers 

