# Get_OHLC_Data

For Get_OHLC_from_Binance_API/get_data.py, you can use the following parameters with the corresponding formats:
- start_date: '9 Feb 2021'      It is the date from how far back you want to go to fetch the historical data. It is set outside the functions otherwise it would run into an unidentified error. Let me know if you can fix this
- symbol = 'BTCUSDT'         It is the trading pair for which you want to fetch the historical data.
- kline_size = "1m" OR "5m" OR "1h" OR "1d"         It is the time period you wish for the historical data you are fetching   
