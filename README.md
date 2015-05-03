# Stocks
Lets use the README as a To-DO list.

Obviously we are going to need a stock table that holds the daily history.

Stock
======
Symbol | Date | Open | High | Low | Adj Close | Volume
======================================================
FB | 1-3-2016 | 100 | 105.0| 99.99 | 104.89 | 1000000
AAPL | 1-3-2016 | 1000 | 1005.0| 999.99 | 1004.89 | 100000
...

Maybe we should have a "Watch List" kind of table where we can add symbols and whether we are looking that them for long or short? Just throwing this idea out here. 

Watch List
==========
Symbol | Reason
===============
CAT | Bearish
URI | Bullish

I will spend some time thinking what we we want and what we are going to need. The point of the program is to back test and for some strange reason I think we may only need 2 Tables. One that holds the stock history and another that holds the methods that perform a specfic back test idea (ie 10 SDMA crossses above 20 SDMA).


Need to create a method that will print out query results in a readable format ie (see below)

query = Select * from stock where date == '1-3-2016'

Symbol | Date | Open | High | Low | Adj Close | Volume
======================================================
FB | 1-3-2016 | 100 | 105.0| 99.99 | 104.89 | 1000000
AAPL | 1-3-2016 | 1000 | 1005.0| 999.99 | 1004.89 | 100000


