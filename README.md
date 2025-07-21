# Portfolio-Tracker1.0
Portfolio Tracker that keeps track of stocks, shares, cash, and total portfolio value with daily reports through email.


## Features - 
- Track as many stocks as you like through ticker symbols & shares owned
- input available cash and optionally put in an interest rate (rate does nothing currently but will be useful in future versions)
- Daily email reports consisting of current prices and portfolio value
- Scheduled daily updates at market close

## How to Use - 
When running, input ticker symbols separated by a single space (no commas)
input number of shares owned for each stock in accordance with the order you entered the ticker symbols
input cash amount
choose either Y or N for interest rate
enter email address of your choice to recieve reports

## Important Notes - 
Users must create their own .env file with bot email credentials to recieve email reports
the script uses yfinance, schedule, etc so users must install the libraries 

## Future Improvements - 
Storage of past prices to show profits/loss
weekly reports
graph of portfolio over time
graph of invidivual stocks over time
