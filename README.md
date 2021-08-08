# Credit Card Fraud Detection - Mini Project #3 

The codes done by Jeya and myself over the span of 2 weeks. 
\
**Objective #1:** to determine which model can help to detect fraud with higher accuracy 
\
**Objective #2:** how much it costs the company if it is false positive or false negative

## Codes and Resources Used 
**Python Version:** 3.8 \
**Packages:** numpy, pandas, matplotlib, seaborn, sklearn, imblearn, xgboost, catboost, lightgbm, keras, tensorflow \
**Dataset:** provided by the school (Institute of Data)

## Data Overview 
Dataset contains transactions made by credit cards in September 2013 by European cardholders. There are a total of 31 variables including time, amount and class (fraudulent transaction or non-fraudulent). 
\
<img width="400" alt="No of Fraudulent Transactions" src="https://user-images.githubusercontent.com/77626155/128606514-abfbd6d5-ec85-44e4-81d2-91b711e749ff.PNG">

## Model Building
With the assumption that: 
* 1 fraudulent transaction costs = EUR 162 (including an average of EUR 33k p.a. of a Fraud Analyst salary; & 
* 1 incorrect labelled transaction costs = EUR 40 

Below is a summary of the models of the Precision, Recall, F1 scores and the costs it the company has to bear if the company implements the respective approach(es). Kindly note that the results in the below table are rounded up to the nearest 1%. For a detailed score, please refer to the jupyter notebooks in this repository. 
\
<img width="450" alt="costs" src="https://user-images.githubusercontent.com/77626155/128606631-2626eeec-92dc-44eb-8381-bd204e2c6276.PNG">

## Takeaways 
From our findings, it shows that: 
* higher score  ≠  lesser costs 
* retrieve relevant data to minimise time spent in detecting fraudulent transactions real-time 
* keeping updated with technology advancements (in terms of devices used, firewalls, to individual's knowledge)
