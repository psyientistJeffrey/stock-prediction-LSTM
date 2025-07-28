## stock-prediction-LSTM

We Used LSTM to forecast shorterm trend of  *Yuanta/P-shares Taiwan Top 50 ETF*  stock price. Our model was trained on **historical stock data** + **online public sentiment**.


#### 📁 Project Structure

```
short-term-stock-prediction/
├── crawler/                          
│   ├── yfinance_crawler.py        # Scrapes historical stock price data using yfinance
│   └── cmoney_crawler.py          # CMoney sentiment/news crawler (may trigger image pop-ups)
│
├── data_preprocessing/
│   ├── sentiment_data_preprocess.py      # Preprocessing pipeline for sentiment/news data
│   └── stock_data_preprocess.py          # Stock price preprocessing + LSTM training on price data
│
├── Model/
│   └── LSTM_2_0.py                # Combines sentiment and price data, applies LSTM + tuning
│
└── README.md                      # Project overview and usage instructions
```
