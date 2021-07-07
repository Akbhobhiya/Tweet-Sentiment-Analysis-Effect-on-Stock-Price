![Python](http://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=ffffff)
![Linux](http://img.shields.io/badge/-Linux-0078D6?style=for-the-badge&logo=linux&logoColor=ffffff)
# Soft Computing Project
# Tweet Sentiment Analysis Effect on Stock Price
This is a mini project at NITK Surathkal.
## Dataset-
Datasets are included in the repo. For the reference part- 
1.
  Stock price Dataset (RAW)
  Dataset is collected for apple company
  Source-https://finance.yahoo.com/quote/AAPL/history/
  Instances-565 and No of features is-6
2.
  Twitter Dataset for AAPL(RAW)
  Source-https://archive.org/search.php?query=collection%3Atwitterstream&sort=-publicdate
  Instances-20668 and No of features is 2
3.
  After Preprocessing total no of instances is 17650 and no of features is 7


## Idea-
In this project, we have shown that a strong correlation exists between rise/fall in stock prices of a company to the public opinions or emotions about that company expressed on twitter through tweets. The main contribution of our work is the development of a sentiment analyzer that can judge the type of sentiment present in the tweet. The tweets are classified into three categories: positive, negative and neutral. At the beginning, we claimed that positive emotions or sentiment of the public on twitter about a company would reflect in its stock price. Prediction using just only sentiments will help in predicting whether the stock price will fall or rise but predicting fixed value is not predicted accurately using just sentiments. So past data time stock is also required for predicting the stock price. The model is trained using LSTM, random forest regressor, SVM regressor, KNN, XG boost, MLP and MSE is compared among them. LSTM performs best in all the models as it has a tendency of remembering the past data. We will try to predict the same using news analysis and considering twitter data in other languages too in the future.

## How to setup the project
This project is built using Python3+ on jupyter-notebook. All the required libraries are listed in the first part of every code file.
Make sure to install all of them to run the project smoothly.

##### Clone the project
```sh
$ git clone https://github.com/Akbhobhiya/Tweet-Sentiment-Analysis-Effect-on-Stock-Price.git
$ cd Tweet-Sentiment-Analysis-Effect-on-Stock-Price
```
