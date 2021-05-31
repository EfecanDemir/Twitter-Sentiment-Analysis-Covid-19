# Twitter-Sentiment-Analysis-Covid-19 (Turkish)
* Sentiment analysis on tweets using Naive Bayes, SVM, Random Forest, LSTM. 
* Twitter Scraper - Scrape tweets for a user or a every word.

## Dataset Information

We use and compare various different methods for sentiment analysis on tweets (a binary classification problem). The training dataset is expected to be a csv file of type `Description,Sentiment_Analysis,Polarity,Topic`.

`Sentiment_Analysis` is either `1` (positive), `-1`(negative) and `0` (neutral). 

`Polarity` is the value between 1 and -1.

`Topic` categorizes it under 7 headings during sentiment analysis.

## Requirements

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.  
* `numpy`
* `sklearn`
* `nltk`
* `nlp`
* `keras` with `TensorFlow` backend for LSTM.
* `matplotlib` 

**Note**: It is recommended to use Anaconda distribution of Python.

## Information about other files

* `dataset/2021_corona.csv`: List of 2021 January tweets. (21.414)
* `dataset/mart_2020.csv`: List of 2020 March tweets. (55.516)
* `dataset/nisan_2020.csv`: List of 2020 April tweets. (25.321)
* `dataset/mayis_2020.csv`: List of 2020 May tweets. (10.347)

* `code/ocak2021.ipynb`: List analysis of 2021 January tweets. 
* `code/mart2020.ipynb`: List analysis of 2020 March tweets. 
* `code/nisan2020.ipynb`: List analysis of 2020 April tweets. 
* `code/mayis2020.ipynb`: List analysis of 2020 May tweets. 

* `code/scraper.ipynb`: Twitter data scraping and editing. 
