# bitcoin-price-analysis
analyzing the price of bitcoin vs market sentiment
# 🧠 Bitcoin Sentiment & Price Analysis

This project explores the relationship between public sentiment on Twitter and the price of Bitcoin. Using real tweet data and historical Bitcoin price data, we aim to understand if there's any correlation between how people feel and how the market moves.

## 📂 Project Structure

bitcoin-analysis/
├── data/ # Contains CSVs with price and tweet sentiment data
│ ├── bitcoin_price.csv
│ └── bitcoin_tweet_sentiments.csv
├── notebooks/ # Jupyter notebooks for data analysis and visualization
│ └── sentiment_price_analysis.ipynb
├── scripts/ # Python scripts (e.g., sentiment scoring pipeline)
│ └── sentiment_model.py
├── README.md # This file
├── requirements.txt # List of dependencies
└── .gitignore # Ignore virtualenvs, CSVs, etc.

markdown
Copy
Edit

## 📊 Data Sources

- **Bitcoin Price Data**: Historical BTC prices collected via [source or mention manually gathered].
- **Twitter Sentiment Data**: Tweets analyzed using the `cardiffnlp/twitter-roberta-base-sentiment-latest` model from HuggingFace Transformers.

## 🛠️ Tech Stack

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebooks
- HuggingFace Transformers (`roberta-base`)
- PyTorch / Scipy
- Git + GitHub

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/your-username/bitcoin-analysis.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Open the Jupyter notebook  
   `jupyter notebook notebooks/sentiment_price_analysis.ipynb`

## 📈 Key Features

- Apply pretrained transformer model to classify tweet sentiment.
- Clean and align BTC price data with sentiment scores.
- Analyze and visualize potential correlations between sentiment and price movement.

## 🤝 Contributing

Pull requests welcome. For major changes, open an issue first to discuss what you’d like to change.

## 📜 License

[MIT](LICENSE)
