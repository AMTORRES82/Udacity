# FIRST UDACITY ASSESSMENT: 3 BUSINESS QUESTIONS ON HOUSES DATASET

**1.Libraries used:**

  import numpy as np
  import pandas as pd
  import matplotlib.pyplot as plt
  from sklearn.linear_model import *
  from sklearn.model_selection import train_test_split
  from sklearn.metrics import r2_score, mean_squared_error
  import seaborn as sns
  from scipy import stats
  from scipy.stats import norm, skew
  %matplotlib inline
  
  Numpy, pandas, matplotlib and sklearn for the models
  
 **2.Motivation for the project:**
  
  2.1. Answer 3 questions about the real state market using the dataset:
    2.1.1.Most important features
    2.1.2.Best deals.
    2.1.3. Worst deals.
  2.2 Learn more and practice with linear model regularizators, elastic net, lasso, ridge.
  2.3.Pass this assessment.
  2.4 Apply the new knowledge acquired in Udacity.
  
 **3.Files in the repository:** 
  test.csv: The dataset whith the house prices and the rest of features.
  Houses2.ipynb: The jupyter notebook where we find the code.
  README.md
  
 **4.Blog:**
  4.1 This first post is about the model and most important features: https://medium.com/chicago-house-prices/the-data-37ed20241621
  4.2 This second post is about the three business questions, where I use the models: https://medium.com/chicago-house-prices/business-questions-from-the-houses-dataset-577ce33570ac
   
 **5.Summary of the results of the analysis:**
  - Most related features with the price.
  - Best deals, where the market price is far below our model prediction. Avg profiles within the category.
  - Worst deals, where the market price is far above our model prediction. Avg profiles within the category.
 
 **6.References:**
  - Kaggle
  - Stackoverflow
  - Udacity Course
  
