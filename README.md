# 📊 Trader Behavior Insights: Fear & Greed in Crypto Markets

This project explores how Bitcoin market sentiment—specifically Fear and Greed—affects trader performance. By merging historical trading data with sentiment indices, we uncover patterns that can inform smarter trading strategies in volatile crypto environments.

---

## 📚 Table of Contents

- [Project Overview](#-trader-behavior-insights-fear--greed-in-crypto-markets)
- [Datasets Used](#-datasets-used)
- [Objectives](#-objectives)
- [Key Findings](#-key-findings)
- [Tools & Libraries](#-tools--libraries)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Contributing](#-contributing)
- [Contact](#-contact)

---

## 📁 Datasets Used

- **Bitcoin Market Sentiment Dataset**  
  Contains daily sentiment classifications (Fear, Greed, etc.)

- **Hyperliquid Trader Data**  
  Includes trade-level details: execution price, size, side, leverage, closed PnL, and more.

- **Historical Data**  
  [Download Link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

- **Fear & Greed Index**  
  [Download Link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

---

## 🧠 Objectives

- Analyze how trader performance varies across different sentiment phases.
- Test if the difference in PnL between Fear and Greed days is statistically significant.
- Derive actionable insights for sentiment-aware trading strategies.

---

## 🔍 Key Findings

- Traders performed significantly better on **Fear** days (avg. PnL ≈ 128.29) than on **Greed** days (avg. PnL ≈ 53.99).
- **Extreme Greed** days had the highest potential gains but also the highest volatility.
- A t-test confirmed the difference in performance is statistically significant (**p-value < 0.0001**).

---

## 📈 Tools & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (for statistical testing)

---

## 🗂️ Project Structure

```
.
├── Trader-Behavior-Insights-Atharva-Ramgir.ipynb  # Main analysis notebook
├── requirements.txt                               # Python dependencies
├── data/                                          # Place datasets here
└── README.md
```

---

## 📌 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/atharvramgir/Fear-and-Greed---Decoding-Trader-Behavior.git
   cd Fear-and-Greed---Decoding-Trader-Behavior
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the datasets:**
   - [Historical Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)
   - [Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)
   - Place the downloaded files in the `data/` directory.

4. **Open the notebook:**
   ```bash
   jupyter notebook Trader-Behavior-Insights-Atharva-Ramgir.ipynb
   ```

5. **Run the cells and follow the instructions in the notebook.**

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

---

## 📬 Contact

For questions or feedback, reach out to [Your Name](mailto:your.email@example.com).
