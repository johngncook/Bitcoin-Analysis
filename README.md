# Bitcoin-Analysis
In this analysis we look at the relationship of bitcoin prices with tweets and see if we can use bitcoin tweets as a predictor for the price of the cryptocurrency. We try to see if there is a connection of bitcoin prices by the number of times bitcoin is tweeted about and if the number of tweets can be a good predictor for bitcoin prices. We peform an EDA and attempt to model a relationship with a Simple Linear Regression.

The analysis is contained in the Bitcoin_Analysis.ipynb file.


### Prerequisites

In order to do this analysis the following libraries were used:

* numpy
* pandas
* seaborn 
* matplotlib
* quandl
* statsmodels.api
* scipy.stats
* sklearn.preprocessing

Enter the following into the terminal:
```
pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
pip install quandl
pip install statsmodels
pip install scipy
pip install sklearn

```

### The Data
* Bitcoin prices were accessed from Nasdaq's Quandl, a platform that provides stock data to analysts. Was accessed by using its free API.
Here is a link to their website: https://www.quandl.com/

* Tweets with #Bitcoin were webscraped from bitinfochart's bitcoin tweets historical chart here: https://bitinfocharts.com/comparison/bitcoin-tweets.html
Script providing code for webscraping the page is contained in Bitcoin_Tweet_Scraper.ipynb.

## Author

* **John Cook** - *Initial work* - [johngncook](https://github.com/johngncook)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

