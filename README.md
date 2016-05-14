# Anomaly Detection, 3 day course

Welcome to the course material and home of Acumed Training's anomaly detection course: 
- **Day 1**: What is an anomaly and the basics of Python Pandas
- **Day 2**: Finding anomalies with machine learning
- **Day 3**: Building better historic profiles 

## Course prerequisites
|    | Requirement |
|---:|--- |
| Must | Some experience developing or at least scripting in Python |
| Must | A numerate backgrownd, ideally some basic statistics | 
| Optional | Experience using Python Pandas |
| Optional | A background of machine learning | 

**Note this course outline is liable to change**

## **Day 1**: What is an anomaly and the basics of Python Pandas
Course outline:
 - What is an anomally? and some ways of finding them
  - Regression / Curve fitting 
  - Clustering 
  - Classification
 - Quick review of some important concepts 
  - Mean and varience
  - Normal distributions 
  - Single tail / two tail tests
  - How much data is enough?
 - Python pandas
  - Data structures ( Series, DataFrames )
  - Selecting data
  - Calculating statistics 
  - Plotting
 - **Excercise 1**: Manipulating data with dataframes

## **Day 2**: Finding anomalies with machine learning
 - Regression
  - The theory
   - Fitting straight lines
   - Fitting curves to data
  - Using Pandas / scikit it is easy
  - **Excercise 2**: Simple linear regression with Pandas
 - Classification ( categories known, supervised machine learning ) 
  - Decision trees
  - **Excercise 3**: Build decision tree anomaly detector 
  - Bayesian classifiers
  - **Excercise 4**: Build baysian anomaly detector
 - Clustering ( categories not known, unsupervised machine learning ) 
  - K nearest neigbour
  - **Excercise 5**: Build K nearest neigbour anomally detector

## **Day 3**: Building better historic profiles
 - What is profiling?
  - Understand seasonal / daily variations
  - Needs more data
 - **Excercise 6**: Build hourly user profiles
 - Twitters anomally detection algorithm
  - Temporal decomposision
  - Variation Student t-test
 - **Excercise 7**: Build anomally detector that:
  - does user profiling
  - splits the signal into three composit signall (trend, periodic, random)
  - finds outliars 

