# Popularity and Profits

This is a minor research project focusing mainly on the relationship between transient popularity of a product (achieved in any form like social media views, advertising, etc.) and the stock performance of the parent company owning that product.

## Netflix and Stranger Things ([Notebook](https://github.com/anshulrao/popularity-and-profits/blob/master/code/Netflix%20and%20Stranger%20Things.ipynb))

*Are Netflix stock prices impacted around the release date of this popular original show of theirs?*

#### Stranger Things (PRODUCT)

`Stranger Things` is a popular and successful Netflix series.

#### Netflix (COMPANY)

`Netflix` offers online streaming of a library of films and television series, including those produced in-house. (`Stranger Things` is one their originals).
    
 ##### Summary
 - I analyzed the stock performance (basically the close price variations) of Netflix to pick out any glaring price fluctuations that happened.
 - I then looked at the Google trends data for Stranger Things to locate the time periods when search interest was high.
 - I then compared both of the above to see if the time period of extreme price fluctuations collided with time period of high search interest.


## BTS and Nongshim ([Notebook](https://github.com/anshulrao/popularity-and-profits/blob/master/code/BTS%20and%20Nongshim.ipynb))

*BTS is a very popular boy band and because of their massive following they have have been spreading Korean culture globally. For example, Nongshim's Shin Ramyun noodles (the most popular instant noodles in South Korea) can now be seen in Indian supermarkets too, thanks to the Hallyu wave.
Could it be that BTS's search interest on Google somehow correlates to Nongshim's stock market performance?*

*NOTE: Nongshim is not the parent company of the band. The relationship is being evaluated here based on the fact that the popularity of the S. Korean band has led to a rise of many S. Korean brands.*

#### BTS (PRODUCT)

`BTS` is a "product" from S. Korea that in turn has voluntarily/involuntarily promoted a range of Korean items, one of them being instant ramen noodles.

#### Nongshim (COMPANY)

`Nongshim` is a S. Korean food and beverage company headquartered in Seoul, South Korea. Apart from other things, it produces Shin Ramyun, S. Korea's most popular ramyun brand. 

##### Summary
- I downloaded both the stock data for Nongshim and search interest data for BTS.
- I then built a Linear Regression model. I used half the data to train the model and then predicted the remaining half using the model.

### Data Sources

Link | Description
---- | -----------
[www.nasdaq.com](https://www.nasdaq.com/market-activity/stocks/nflx/historical) | Historical data for Netflix stocks
[trends.google.com](https://trends.google.com/trends/explore?date=2019-01-01%202019-12-31&geo=US&q=%2Fm%2F0131ln7y) | Google Trends data for Stranger Things
[finance.yahoo.com](https://finance.yahoo.com/quote/004370.KS/history?period1=1543622400&period2=1601424000&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true) | Historical data for Nongshim stocks
[trends.google.com](https://trends.google.com/trends/explore?date=2018-12-01%202020-09-30&q=%2Fm%2F0w68qx3) | Google Trends data for BTS
