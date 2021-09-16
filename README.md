# [EN] Introduction to Market Algorithmic Execution Lesson

With this script we will be able to retreive data from the exchange, process it, and determine 
technical signals according to our trading strategy. 

For the example, we will use technical indicators (MACD & RSI) and cryptocurrency assets due lesson example is done 
on weekend for training purposes and the market is open :)

What will we learn?

1. Connect to an exchange RealTime (Data - Orders).
2. Data: Gathering, cleasing (Using pandas) and analysis. 
3. Functions to determine technical indicators, market reading and signals
4. Execute orders when our conditions appears.

What we WON'T cover on this video?

1. Overall market analysis (to activate-deactivate algorithm)
2. Risk Metrics Monitoring (to activate-deactivate algorithm)
3. Deployment on servers or local machine (Linode - Digital Ocean, etc)

To do so, we will use:

1º- ccxt library -> Which allows to easily connect the most common cryptocurrency exchanges
in order to retreive the raw data, and execute the orders (buy/sell).

https://ccxt.readthedocs.io/en/latest/manual.html


2º- pandas -> The common library to process the raw data reception and work with it.

https://pandas.pydata.org/docs/

3º- ta library -> To implement technical indicators (we will see the option to calculate them manually or use a library)

https://technical-analysis-library-in-python.readthedocs.io/en/latest/index.html

4º- schedule function -> to run the script every (x) seconds/minutes/hours... for data retreival and processç

https://schedule.readthedocs.io/en/stable/


# DISCLAIMER

Don't use the conditions on the video to execute real orders. IS FOR EDUCATIONAL PURPOSE. 

The general information contained in this repository/video can't be considered as financial advice or recommendation. In addition, the information published should not be considered as a decision element to buy or sell any type of asset. Investing in financial markets such as CFDs, forex, stocks, derivatives, etc., is an activity that carries risk of losing your money. Do not invest in financial markets if you do not understand the management and consequences of this activity. Finally, remember that results based on the past are not indicative of future results.
