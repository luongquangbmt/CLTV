# Customer's LTV

I use the LTV model developed by Google engineers [this paper](https://arxiv.org/pdf/1912.07753.pdf) 
and fork from [this repo](https://github.com/google/lifetime_value). 
The model uses customers' attributes and past purchase behaviour data as input. 
b  

## Step 1: Download data
### [Kaggle Acquire Valued Shoppers Challenge Dataset](https://www.kaggle.com/c/acquire-valued-shoppers-challenge/data)

This Kaggle challenge provides almost 350 million rows of completely anonymised transactional data from over 300,000 shoppers. We use the transactional data to demonstrate LTV modeling.

We download the transaction.csv (21GB) file from Kaggle server and prepare csv files for each of top 20 most common companies. Then we train a Keras model to predict customer's lifetime value and returning probability.   

## Step 2: Pre-process data

