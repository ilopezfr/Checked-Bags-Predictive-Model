# Checked Bags Predictive Model
Developed a model to predict the average number of bags per passenger (ABPR) for a specific flight.  

Used two years of every single flight data for the airline. 
Steps followed:
1. Data Modeling: 
  -Variable Generation
  -Exploratory Data Analysis
      -Descriptive
      -Distribution
      -Univariate Analysis (correlations)
      -Removed Outliers
      -Variable Transformation

2. Prediction:
    -split using stratified function
  A. Method 1:
    -PCA
    -K-Means # Not implemented
    -GBM # via h2o
  B. Method 2:
    -GLRM (Generalized Low Rank Models) # via h2o
    -GBM # via h2o

