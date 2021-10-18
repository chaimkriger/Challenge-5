# Financial Planner Application

There are two sections to this application. In the first section, i create a personal financial planner for emergencies. To do this, i assume that The average monthly household income for each credit union member is //$12,000, and each credit union member has a savings portfolio that consists of a cryptocurrency wallet, stocks, and bonds.
First, I evaluate the cryptocurrency wallet by using the requests library. I assume that the member holds 1.2 Bitcoins 5.3 Etherium coins. I then evaluate the stock and bond holdings by using the Alpca SDK. 
Next, I use the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan. I also build a pie chart that visualizes the composition of the member’s portfolio.
If the member's total portfolio's value is greater than the amount needed to fund the emrgency fund, my application will print a congradulatory message. If the amount is less than the amount needed to fund the emergency fund, my application will tell the member how much more money he will need to fund it.

In the next section of my application, i create a financial planner for retirement. I use the Alpaca API to get historical closing prices for a retirement portfolio. i use a  60/40 portfolio split: 60% stocks (SPY) and 40% bonds (AGG).

 I then run Monte Carlo simulations to forecast the portfolio performance 30 years from now. I use the simulated data to find the range that the retirement portfolio will be in 30 years with a 95 percent confidence interval.
 30 years is a lenthly period of time to wait until retirement, and so i forecast the cumulative returns for 10 years from now. Because of the shortened investment horizon (30 years to 10 years), the portfolio needs to invest more heavily in the riskier asset—that is, stock—to help accumulate wealth for retirement. Based on the new Monte Carlo simulation, i attempt to discern if this new portfolio distribution can help the member retire after only 10 years.
 
---

## Technologies

This project leverages python 3.7.

---

## Installation Guide

Before running the application, python must be installed.

---

## Usage

To use the Financial Planner Application, simply run the code. You can custom tailer the application for  your own needs, by simply swapping any of the data with your own. For example, you can updaate the monthly income, and the emergency fund threshold as desired. you can also change the amount of years for the Monte Carlo simulation, the tickers in the portfolio, or the weights distribution. 


---

## Contributors

just me, myself, and a little help from Module 5.

---

## License

None, feel free to copy the code and use anytime!