Web Introduction to tick data gathering/processing/execution


On this script we will be able to retreive data from the exchange, process it, and determine 
technical signals according to our trading strategy. 

For the example, we will use technical indicators (MACD & RSI) and cryptocurrency assets due example is done 
on weekend for training purposes and the market is open :)

To do so, we will use:

1º- ccxt library -> which allows to easily connect the most common cryptocurrency exchanges
in order to retreive the raw data, and execute the orders (buy/sell).
https://ccxt.readthedocs.io/en/latest/manual.html


2º- pandas -> The common library to process the raw data reception and work with it.
https://pandas.pydata.org/docs/

3º- ta library -> To implement technical indicators (we will see the option to calculate them manually or use a library)
https://technical-analysis-library-in-python.readthedocs.io/en/latest/index.html

4º- schedule function -> to run the script every (x) seconds/minutes/hours... for data retreival and process
https://schedule.readthedocs.io/en/stable/