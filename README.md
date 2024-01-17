# tradingBotBasics  
User place order- Limit order/ Market order  
How is the price of a stock determined- Supply/Demand  
Highest bid, lowest ask- when the lowest ask becomes lesser than highest bid the exchange happens.  
Finance Jargons- Orderbook, limit/market order, Market depth, Liquidity, Maker and taker  
Orderbook- When the lowest ask and highest bid comes closer and closer the spread closes. When the match happens they move out of the orderbook. The price of the stock is the last price when the exchange happens. If the spread is very small, it is a liquid stock. Spread = highest bid-lowest ask.  
The price of the stock is literally the last price of it when the exchange happened. Different exchange platforms hence have different prices of the same stock, depending on the last price at which the exchange happened, on that platform.  
How is the orderbook filled. Limit order- Some traders place very specific price target, the say like I am willing to pay this much price for this much quantity. If there is a match at the current orderbook, the exchange happens otherwise the order sits in the orderbook. Market order- You only give the quantity, and the price is taken as the best price in the current orderbook. This exchange have more trading fee. Limit orders have lesser trading fee.  
Liquidity/ market depth- how many orders does the book have. How tight the spread is? Can it handle big orders without crashing the price. Market makers provide liquidity. The market makers are incentivised, companies like citadel do some math and place orders in the orderbook. The less the spread the more the people will want to trade.  
Maker vs Taker- Maker is the person who commit to a price, and waits for the order providing liquidity and person who takes the order and hence the liquidity from the orderbook is called the taker. Maker is charged less trading fee than the Taker.  
Where does latency matter- The trader have to quickly place, cancel and prioritize their orderbook. Order ack time should be very small, and cancel time should be also very small otherwise under some circumstance they will get a big loss.  
How is latency made better for the exchange- using faster programming languages. Faster serialization and deserialization of data. In memory orderbooks, the orderbooks we get from trading platforms are stored in a variable in the program as we cannot afford the time to get the data back from the database. These are the ways to make latency better for exchange.
How is latency made better for a Trader/ Market maker- being closer to the trading server, having multiple connections open, faster serialization/deserialization, faster prediction models.  
+++***
