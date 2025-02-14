# Gold Price Prediction

![gold3](https://github.com/user-attachments/assets/7b04589f-db8a-4c28-884e-8c19f961d105)

## Context
Historically, gold had been used as a form of currency in various parts of the world including the USA. In present times, precious metals like gold are held with central banks of all countries to guarantee re-payment of foreign debts, and also to control inflation which results in reflecting the financial strength of the country. Recently, emerging world economies, such as China, Russia, and India have been big buyers of gold, whereas the USA, SoUSA, South Africa, and Australia are among the big seller of gold.

Forecasting rise and fall in the daily gold rates can help investors to decide when to buy (or sell) the commodity. But Gold prices are dependent on many factors such as prices of other precious metals, prices of crude oil, stock exchange performance, Bonds prices, currency exchange rates, etc.

The challenge of this project is to accurately predict the future adjusted closing price of Gold ETF across a given period of time in the future. The problem is a regression problem, because the output value which is the adjusted closing price in this project is continuous value.


## About Dataset 
The historical data of Gold ETF fetched from Yahoo finance has 7 columns, Date, Open, High, Low, Close, Adjusted Close and Volume, the difference between Adjusted Close and Close is that closing price of a stock is the price of that stock at the close of the trading day. Whereas the adjusted closing price takes into account factors such as dividends, stock splits and new stock offerings to determine a value. We would use Adjusted Close as our outcome variables which is the value we want to predict.
#### 1. 'SP_open', 'SP_high', 'SP_low', 'SP_close', 'SP_Ajclose', 'SP_volume' of S&P 500 Index,
#### 2.  'DJ_open','DJ_high', 'DJ_low', 'DJ_close', 'DJ_Ajclose', 'DJ_volume' of Dow Jones Index,
#### 3.  'EG_open', 'EG_high', 'EG_low', 'EG_close', 'EG_Ajclose', 'EG_volume' of Eldorado Gold Corporation (EGO),
4.  'EU_Price','EU_open', 'EU_high', 'EU_low', 'EU_Trend' of EUR USD Exchange rate,
5.  'OF_Price', 'OF_Open', 'OF_High', 'OF_Low', 'OF_Volume', 'OF_Trend' of Brent Crude oil Futures,
6.  'OS_Price', 'OS_Open', 'OS_High', 'OS_Low', 'OS_Trend', of Crude Oil WTI USD,
7.   'SF_Price', 'SF_Open', 'SF_High', 'SF_Low', 'SF_Volume', 'SF_Trend' of Silver Futures,
8.   'USB_Price', 'USB_Open', 'USB_High','USB_Low', 'USB_Trend' of US Bond Rate data,
9.    'PLT_Price', 'PLT_Open', 'PLT_High', 'PLT_Low','PLT_Trend' of Platinum Price,
10.  'PLD_Price', 'PLD_Open', 'PLD_High', 'PLD_Low','PLD_Trend' of Palladium price
11.  'RHO_PRICE' of Rhodium Prices
12. 'USDI_Price', 'USDI_Open', 'USDI_High','USDI_Low', 'USDI_Volume', 'USDI_Trend' of US dollar Index Price,
13.  'GDX_Open', 'GDX_High', 'GDX_Low', 'GDX_Close', 'GDX_Adj Close', 'GDX_Volume' of Gold Miners ETF,
14.   'USO_Open','USO_High', 'USO_Low', 'USO_Close', 'USO_Adj Close', 'USO_Volume' of Oil ETF USO
