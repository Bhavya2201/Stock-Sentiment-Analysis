# Stock-Sentiment-Analysis
This is a simple python projects which makes use of articles about stocks from [Finviz](https://www.finviz.com)

## About
The first step of the project is to get the articles from [Finviz](https://www.finviz.com), which are obtained by selecting the companies whose stock sentiments we wanted to analyse and getting the URL. The next step is web scraping and the data obtained from [Finviz](https://www.finviz.com) is cleaned hence features like title, date and time of publication are obtained. The data then is converted into a dataframe and fed to sentiment analyser. The results obtained after sentiment analysis are plotted using a bar chart.

## Libraries used
* pandas
* matplotlib
* BeautifulSoup
* nltk
* urllib3

 
