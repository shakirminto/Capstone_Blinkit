# Capstone_Blinkit

# Blinkit Quick-Commerce Python Analytics

## Overview

This repository provides Python code and Jupyter Notebooks for data analysis and predictive modeling of Blinkit's business operations. The focus is on sentiment analysis of customer feedback, and delivery time prediction.

## Key Features

- **Sentiment Analysis & Text Processing:**  
  Clean and analyze customer feedback using NLTK and TextBlob.  
  Extract frequent words, perform sentiment scoring, and correlate feedback sentiment with order values and delivery times.

- **Delivery Time Prediction Model:**  
  Use regression (Scikit-learn) to predict delivery time in minutes, based on features like distance, promised time, and delivery partner.  
  Evaluate model accuracy (MAE, RMSE, R²) and interpret feature importance.



**Clone this repository and add your data files** (`customers.csv`, `orders.csv`, etc.) to the `data/` directory.
 **Open the Jupyter Notebooks** and run the steps in order:
    - `EDA_and_Cleaning.ipynb`
    - `Sentiment_Analysis_and_Feedback.ipynb`
    - `Delivery_Time_Prediction.ipynb`
   
 
