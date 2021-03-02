# daily-revenue-prediction
Machine Learning Techniques Final Project

# Task Introduction

In this final project, you are going to be part of an exciting machine learning competition. A hotel booking company tries to predict the daily revenue of the company from the data of reservation. In particular, after a room reservation request is fulfilled (i.e. no cancellation), on the arrival date, the revenue of the request is the rate of the room (called ADR) multiplied by the number of days that the customer is going to stay in the room, and the daily revenue is the sum of all those fulfilled requests on the same day. The goal of the prediction is to accurately infer the future daily revenue of the company, where the daily revenue is quantized to 10 scales.

Now, having collected some data from the hotel booking service, the CEO of the company decides to ask you, a rising star in the data science team, to help with the prediction task. You need to fight for the most accurate prediction on the score board. Then, you need to submit a comprehensive report that describes not only the recommended approaches, but also the reasoning behind your recommendations. Well, let’s get started!

data source: [course page](https://www.csie.ntu.edu.tw/~htlin/course/ml20fall/project/)

# Feature

1. The `main.ipynb` file contains the following content:
    - EDA
    - Data Preprocessing
        * Missing Values Handling
        * Outlier and Future Data Removal
        * Unique Value of Categorical Features Reduction
    - Feature Engineering
        * Feature Generation
        * One-Hot Encoding
        * Log Transformation
        * Interaction
        * Standardization
    - Feature Selection (Regression and Classification)
        * (We don't perform dimension reduction here, since we aim to hold the explainability.)
    - Baseline Model Building (Regression and Classification)
        * involving walk-forward cross-validation

2. The `report.pdf` file contains the comprehensive work flow, EDA result, model comparison and our suggestion.
