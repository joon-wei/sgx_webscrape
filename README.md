## SGX data downloader
Download historical price data for SGX listed equity.

May need to update the User Agent to what works on your machine.

A webscraper for sg.finance.yahoo which aims to replicate the functionality of yfinance.download(), returning a dataframe of open and close prices and volume for the stock, with date as the index column. May need to update the User Agent to what works on your machine. Of course this depends on the yahoo page working, for some reason the table containing data of the stocks (like C38U) vanish occasionally. Be sure to check the url generated by the script is working well.

Example use:
```
stock = download(ticker,start_date,end_date)
```
