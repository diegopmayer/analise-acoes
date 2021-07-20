# Analysis system for investments

> For all steps and schedules about the project see the page <a href="https://diegopmayer.notion.site/Sistema-de-an-lise-de-investimento-0a3547a8fe3141e3a33909914a794eeb">clique here</a>

## Objective

Create a solution to deliver a recommendation stock and funds, using descriptive and predictive analysis and answers the questions like when I can buy, sell or keep them?

## What kind of Problem?

Regression - Time Series - Supervised Learning

To better understand what is the time series, see [HERE](https://www.aptech.com/blog/introduction-to-the-fundamentals-of-time-series-data-and-analysis/) an article about the foundations of time series.

## How can you solve it?

First of all, simple features and models, also complex if necessary.

Collecting data from API, libraries, web scraping, social media, newspaper sites, and blogs.

Getting foundations and technical information about the company, and all about the segment, area, business-related, or competitors.

Create predict solution for each stock, and improve each cycle, adding the new features and new sentiment analysis from social media, API, or web scraping.

## MindMap

![Analysis%20system%20for%20investments%20a61c8d7431c84b008a963f48cef3cc68/Untitled.png](Analysis%20system%20for%20investments%20a61c8d7431c84b008a963f48cef3cc68/Untitled.png)

## Features

company_name, symbol, open_price, close_price, sma, lower_band, upper_band, sentiments from (president of the company, communication person, influencers, competitors, etc), growth_tax_price, commodity_price, competitor_price, segment_price, others...

## Models

![Analysis%20system%20for%20investments%20a61c8d7431c84b008a963f48cef3cc68/Untitled%201.png](Analysis%20system%20for%20investments%20a61c8d7431c84b008a963f48cef3cc68/Untitled%201.png)

Deep learning has been showing better valuation performance, but, it's hard to interpret the model, and it's most important to have the highest volume of data "registers".

### Baseline

SMA → Simple Moving Average, it's better, because it's mostly used by investors, then, we most get upper than SMA.

### Model

First of all, we will use the [pmdarima](http://alkaline-ml.com/pmdarima/) from the Python library, also, we will use the [Facebook prophet](https://facebook.github.io/prophet/)

See [PMDArima auto arima](https://www.notion.so/PMDArima-auto-arima-c3efe642d507416195937e0693cab898)  how you can use the pmdarima.
See [Facebook Prophet](https://www.notion.so/Facebook-Prophet-9019725f4cf24ab29af4b42b9ccf3d6d)  how you can use the prophet

## Revenue Stream thought.

1. Monthly payer.
2. Commission percent by profit.
3. ADS.
4. Investors portfolio to earn with partners company.

Explaining videos in "Portuguese"

Vídeo_01
[Análise de Ações](https://www.awesomescreenshot.com/video/4272767?key=e96cd2fb0bdb8979cda97eca7436eb13)

Video_02
[petrobras](https://www.awesomescreenshot.com/video/4272919?key=5469970aa632c84f3aa9331c7f966d67)

Video_03
[petrobras](https://www.awesomescreenshot.com/video/4272955?key=cc3f26fc7ee764c70bd25e42455198a9)

Code repository from GitHub
[diegopmayer/analise-acoes](https://github.com/diegopmayer/analise-acoes)

First Steps:

1. Best ranking by growth tax from the close price.
2. Close price prediction for the next week only two stocks.
3. Collecting more features from the same API and others.
4. Volume prediction to add into close price prediction.
5. Funds prediction.
6. Buy and sell recommendations prediction by Bollinger metrics.

[Tasks](https://www.notion.so/a1f5eb95db934bfd9c261d4f0d6113e7)
