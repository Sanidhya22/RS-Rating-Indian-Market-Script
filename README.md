# RS Rating for Trading View

First what to give credit to [Fred6725](https://github.com/Fred6725) for creating the below RS Rating Script .I have done some modification and modified it for indian market.

This Trading View script calculates the Relative Price Strength (RS) Rating for a given stock. It's a measure of a stock's price performance over the last twelve months, compared to all stocks in a selected Index. The rating scale ranges from 1 (lowest) to 99 (highest).

## Features

- Adaptation for Indian Market
- Option to choose the index to compare to (NSE:NIFTY, NSE:CNX500, NSE:NIFTYSMLCAP250, NSE:CNXSMALLCAP)
- Option to compare to a different index
- Option to hide the RS rating
- Option to plot RS new highs
- Option to adjust the offset of the line for display purposes
- Option to change the color of the RS Line & Rating
- Option to change the color of the dots for RS new highs
- Option to choose which new high to plot (RS New Highs, RS New Highs Before Price, Historical RS New Highs, Historical RS New Highs Before Price)
- Option to adjust the recent high look-back count

## How to Use

1. Open Trading View.
2. Open the script editor.
3. Copy and paste the provided script into the editor.
4. Save the script.
5. Apply the script to your chart.

Please note that the script is designed to work best in the daily timeframe. Results may not be accurate in other timeframes.

This script uses three methods to calculate the RS Rating:

1. A method that calculates how the stock behaves vs SMA.
2. A classic performance method that calculates the performance of the stock's closing price vs the closing price 3 months back.
3. A method that measures how the stock performs against the comparative Symbol.

The final RS Rating is a combination of the results from these three methods. The script also includes some adjustments based on observations to improve the accuracy of the rating.
