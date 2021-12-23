# Arbitrage opportunities for bitcoin 

This is a Jupyter notebook that contains the code for data collection, preparation, and analysis including visualizations. By sorting through historical data generagted from two exchanges, This will generate a report to deturmine whether there are any arbitrage opportunities for Bitcoin. 

---

## Technologies 

This project leverages python 3.7 with the following packages:
```
Jupyter Notebook 
Pandas 
```
---

## Installation Guide 

Before running the application first install the following dependencies.
```
Install Anaconda Package
Pip intall Jupyter 
```
---

## Usage 

To deturmine the arbitrage opportunities for bitcoin, clone the repository and run **Jupyter lab** in python:

```python
Jupyter Lab
```
Jupyter lab should launch in a web browser, if it doesnt select one one of the hyperlinks it provides copy it and paste it into a web browser page.  

Download the resources folder into your desktop

---

## Analysis 

After performing the analysis which considered arbitrage opportunities in Bitcoin and other cryptocurrencies these are the discoveries I have found.

The analysis was focused on the Bitcoin and other cryptocurrencies Timestamp and close, I was able to generate summary statistics for an early time period and later time period (see graphs below). 

![]('earlier.png')
![]('later.png')

Based on the visualizations of the different time periods, the degree of spread has decreased as time progressed. The visualizations show that over time their exchange comparison has become extremely similar and within the same range, looking closely at the data for earlier time periods the graph clearly displays the arbitrage between bitstamp and coinbase. When analyzing the arbitrage for later time periods the graph displays very little arbitrage, infact bitstamp and coinbase are very similar. 

Looking more closely into the data these are the graphs of the data from an early (January 16, 2018) middle (February 24, 2018), and late analysis (March 26, 2018). 

![]('Early_date.png')
![]('Middle_date.png')
![]('Late_date.png')

After reviewing the profit information across each date from different time periods it shows that we were making a profit from the spread on January 16, 2018, the function profit_per_trade_early.sum() indicates that the cumulative profit was 14147.999999. The spread on February 24, 2018 shows that the profit_per_trade_early.sum() or cumulative profit was 330.0699999999997. Lastly, the spread on March 26, 2018 shows that there has been a regime change which shows that bitstamp is now higher than coinbase. 

---
## Contributors 

Brought to you by Olena Shemedyuk.

email: Olenashemedyuk@gmail.com

---

## Licence 

MIT

