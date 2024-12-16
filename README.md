# Strategic-Stock-Trading-with-Deep-Reinforcement-Learning-Models

## Team Members
- 1905095 : Md Raihan Sobhan
- 1905115 : Tahsin Wahid

## Problem Definition

Traditional trading models rely heavily on historical data, making them rigid and slow to respond to real-time market fluctuations. This gap often leads to missed opportunities and increased risk for traders.

## Literature Review Highlights:
- Deep Reinforcement Learning (DRL) has shown potential in enabling real-time adaptability and improving decision-making in volatile
environments.
- Studies suggest DRL can integrate real-time data and sentiment analysis, providing more robust, dynamic trading strategies.

## Datasets for Model Training

### Primary Dataset:

[Dhaka Stock Exchange Dataset (DSEBD)](https://www.kaggle.com/datasets/mahmudulhaque/dsebd): Daily stock price data from the
Dhaka Stock Exchange, providing insights into a growing emerging market.
### Additional International Datasets:
- [SP 500 Stock Data](https://www.kaggle.com/datasets/paultimothymooney/stock-market-data): Covers daily prices for SP 500 stocks, offering a view
into a mature market.
- [US Stocks and ETFs Price and Volume Data](https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs): Includes comprehensive price and volume data across all US stocks and ETFs.
- [Brazilian Stock Market](https://www.kaggle.com/datasets/andrewmvd/brazilian-stock-market) - Daily Updated
Indian Stock Market Index Intraday Data(2008-2020)


## Reference Papers :
- [FinRL](https://arxiv.org/pdf/2011.09607): A Deep Reinforcement Learning Library for Automated Stock
Trading in Quantitative Finance
- [Practical Deep Reinforcement Learning Approach for Stock Trading](https://arxiv.org/pdf/1811.07522v3)

## Proposed Solution :
### Solution Approach: 
- Develop a DRL-based trading model that dynamically adapts to real-time market conditions by employing an optimal reward function.
- This function not only maximizes profits but also carefully considers the level of risk taken, ensuring a balanced strategy that prioritizes sustainable growth while minimizing potential losses.

## Key Techniques:
- Proximal Policy Optimization (PPO) for stability in
decision-making.
- Twin Delayed DDPG (TD3) to manage volatility and improve
accuracy.
- Trust Region Policy Optimization (TRPO) for stable and
conservative policy updates.
- Ensemble of DRL models for robust adaptability across market
conditions.

## Performance Metrics

- Initial and Final Portfolio Value
- Annualized Return
- Annualized Standard Deviation
- Sharpe Ratio
- Max Drawdown
- Sortino Ratio


## How to Run This Code
- Run the jupyter notebooks , install required libraries. 
- Update dataset paths, with your local path <br> 
` dir = r"/Users/md.raihansobhan/Desktop/BUET/4-2 Sessionals/CSE 472 | ML/online_class/Strategic-Stock-Trading-with-Deep-Reinforcement-Learning-Models/datasets/kaggle-dse" `


## Tasks to be done
- New Algorithm (DRL)
- Graph analysis
- New Reward Functions 
- 
- Write Ups
- Cleandata bug 
- kwargs - 2 parameters sort out

