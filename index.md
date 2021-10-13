# Portfolio
---
### Cardano Twitter Sentiment Analysis: Using Scrapped Tweets concerning Cardano to analyse sentiment

[![Open Notebook](https://img.shields.io/badge/jupyter-open%20notebook-blue)](Exploration.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/AvinaashP/CardanoTwitterSentiment)

<div style="text-align: justify">I scrapped 200,000 tweets that contained the word Cardano to be able to analyze the sentiment surrounding the cryptocurrency during a time of rapid price increase to see if there was any interesting patterns that I could find. This project allowed me to make use of NLP techniques like regex functions to clean up the tweets and data visualization and manipulation to create graph that could show the value of sentiment surrounding Cardano from August 08 2021 to August 31 2021. </div>

---
### Customer Churn Analysis: Analyzing through Telco data to predict future customer churn

[![Open Notebook](https://img.shields.io/badge/jupyter-open%20notebook-blue)](CustomerChurn.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/AvinaashP/CustomerChurn)
<div style="text-align: justify"> Using data sourced from IBM sample datasets, the Telco dataset includes customer information from a telcommunications company that provides internet and phones services. The aim of the dataset is to create a model that can predict whether a customer is likely to churn. I thought the dataset would be a good opportunity to practice applying problem solving solutions to real world business problems and allow me to apply data visualization and statistical testing techniques that would shine more light on to the dataset. I applied two different gradient boosting model in XGBoost and Catboost and while the performances were close, Catboost edged on XGBoost on recall metrics  </div>

### Kaggle Competition: Grocery Sales Forecasting (Time-Series)
[![Open Notebook](https://img.shields.io/badge/jupyter-open%20notebook-blue)](time-series-grocery-sales.html)

<div style="text-align: justify"> Participating in a Kaggle competition (https://www.kaggle.com/c/store-sales-time-series-forecasting/overview), the aim of the competiton was to forecast the sales from a Ecuadorean Grocery Chain. The competition allows me to practing analyzing time series decompositon and trying out various models like Facebook Prophet and XGBoost regressor to forecast future sales. An obstacle I had to overcome was dealing with the multiple categories of individual stores and product familes which each had their own time-series. I settled on using a nested for loop to iterate over each combination of store and product family and then fit that data subset into a XGboost regressor to predict future sales. While the method was not as efficient as I would have liked, the results were very good and I managed to place 10th in the leaderboard. </div>

<center><img src="images/kaggleCompResults.png"/></center>
