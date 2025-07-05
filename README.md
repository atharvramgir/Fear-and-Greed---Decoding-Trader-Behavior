# 📊 Trader Behavior Insights: Fear & Greed in Crypto Markets

This project explores how Bitcoin market sentiment—specifically Fear and Greed—affects trader performance. By merging historical trading data with sentiment indices, we uncover patterns that can inform smarter trading strategies in volatile crypto environments.

## 📁 Datasets Used

- **Bitcoin Market Sentiment Dataset**  
  Contains daily sentiment classifications (Fear, Greed, etc.)


- **Hyperliquid Trader Data**  
  Includes trade-level details: execution price, size, side, leverage, closed PnL, and more.

- **Historical Data**  
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing 
- **Fear Greed Index link:** 
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
## 🧠 Objectives

- Analyze how trader performance varies across different sentiment phases.
- Test if the difference in PnL between Fear and Greed days is statistically significant.
- Derive actionable insights for sentiment-aware trading strategies.

## 🔍 Key Findings

- Traders performed significantly better on **Fear** days (avg. PnL ≈ 128.29) than on **Greed** days (avg. PnL ≈ 53.99).
- **Extreme Greed** days had the highest potential gains but also the highest volatility.
- A t-test confirmed the difference in performance is statistically significant (**p-value < 0.0001**).

## 📈 Tools & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (for statistical testing)

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/atharvramgir/Fear-and-Greed---Decoding-Trader-Behavior.git

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Open the notebook:
   ```bash
   jupyter notebook Trader-Behavior-Insights-Atharva-Ramgir.ipynb
