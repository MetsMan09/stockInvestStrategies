# Stock Market Fantasy League

Welcome to the **Stock Market Fantasy League**! 🚀📈 This web app allows users to create and manage their own stock portfolios, competing with others on a leaderboard. It's an exciting way to learn about the stock market while having fun in a fantasy league-style competition.

## Features 🌟

- **Create and Manage Portfolios**: Build your own stock portfolio and track your investments over time.
- **Fantasy League**: Compete with others to see who can create the most successful portfolio.
- **Leaderboard**: View rankings of the top-performing portfolios.
- **Real-Time Stock Data**: Fetch real-time stock prices and market trends.
- **User-friendly Interface**: Built with Streamlit for an interactive and easy-to-use interface.

## How It Works 🏦

1. **Create an Account**: Sign up to start building your stock portfolio. (Future multi-account support is planned.)
2. **Add Stocks**: Choose your favorite stocks to add to your portfolio.
3. **Track Performance**: Monitor your portfolio’s performance in real-time based on the latest market data.
4. **Compete for the Top Spot**: See how your portfolio stacks up against others on the leaderboard. The portfolio with the highest value wins!

## Tech Stack 💻

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**: Stock data via free API services (e.g., Alpha Vantage, Yahoo Finance)
- **Database**: (Optional for user accounts, not yet implemented)
- **Deployment**: Local for now, future deployment planned to a cloud platform (like Heroku or AWS)

## Getting Started 🛠️

### Prerequisites

Before running the app, make sure you have the following installed:

- Python 3.x
- Streamlit

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/stock-market-fantasy-league.git
   cd stock-market-fantasy-league


 # Stock Fantasy League - Risky Investment Strategies

This project is a gamified approach to financial literacy. Users can create portfolios and compete based on stock performance over time. In this game, **risky investment strategies** are penalized to promote smarter financial decisions. Below is a list of these strategies and how they are penalized.

## Risky Investment Strategies

### 1. **All-In on One Stock ("YOLO Investing")**
- **Description**: Investing everything in a single stock rather than diversifying.
- **Example**: Betting 100% of funds on Tesla instead of spreading investments across industries.
- **Penalty**: Lower multiplier on the final score for lack of diversification.

### 2. **Chasing Hype Stocks & Meme Stocks**
- **Description**: Picking stocks that have extreme short-term momentum (e.g., GameStop, AMC) but lack solid fundamentals.
- **Penalty**: Reduced score multiplier and a **warning** about volatility due to market trends like social media hype.

### 3. **Investing in Penny Stocks**
- **Description**: Stocks with a low market cap (<$1 billion) and prices below $5 per share. These are highly volatile and often subject to pump-and-dump schemes.
- **Penalty**: Multiplier reduced significantly for high-risk volatility.

### 4. **Not Diversifying (Sector Concentration Risk)**
- **Description**: Investing everything in a single industry (e.g., all tech stocks) instead of spreading investments across multiple sectors.
- **Penalty**: Score reduction for lack of diversification, and rewards for portfolios with multiple sectors.

### 5. **Frequent Trading & Overtrading**
- **Description**: Constantly buying and selling stocks instead of holding them for longer periods.
- **Penalty**: Transaction cost penalty and score reduced for **excessive trades** in a short period.

### 6. **Buying Stocks with High Beta Values**
- **Description**: Stocks with beta > 1.5 (meaning they fluctuate more than the market).
- **Example**: Growth stocks that swing wildly based on market sentiment.
- **Penalty**: Reduce multiplier for portfolios with high-beta stocks.

### 7. **Ignoring Earnings & Financials (Fundamental Risk)**
- **Description**: Investing in stocks with negative earnings (EPS < 0) or heavy debt.
- **Penalty**: Penalize stocks with negative earnings or poor financials.

### 8. **High Debt-to-Equity Ratio Stocks**
- **Description**: Companies with an extremely high debt load relative to their equity are financially unstable.
- **Example**: Airlines, companies that borrow heavily to stay afloat.
- **Penalty**: Reduced score for portfolios with high-leverage stocks.

### 9. **Buying on Margin (Leverage)**
- **Description**: Borrowing money to invest in stocks, which increases financial risk.
- **Penalty**: Major penalty, as margin trading amplifies risks.

### 10. **Trying to "Catch a Falling Knife" (Buying Dying Stocks)**
- **Description**: Investing in stocks that have been consistently declining in price over time.
- **Example**: A stock down 40%+ in the last year might indicate deeper problems.
- **Penalty**: Penalize portfolios that include stocks with significant declines.

## Implementation Ideas

### Risk Score System
- Create a **risk score** for portfolios based on the number of risky behaviors in the portfolio.
- A portfolio with **3+ risky behaviors** will get a **0.7x – 0.9x penalty** on their final score.

### Dynamic Risk Assessment
- Use APIs to gather financial data (e.g., stock price, beta, debt ratios) and assess risk in real-time.

### Warnings & Educational Feedback
- **Pop-Up Alerts**: Show a warning if a user is making risky choices and provide educational tips explaining why the strategy is risky.

### Diversification Bonus
- Reward users who maintain a **well-diversified portfolio** by adding a small bonus multiplier (e.g., 1.1x).

### Frequent Trading Penalty
- Track the number of trades per day and penalize users who exceed a set limit (e.g., 5 trades per day).

## Example Scoring System

- **Balanced Strategy**: 1.0x (Normal score)
- **Risky Portfolio**: 0.7x – 0.9x
- **Highly Diversified Portfolio**: 1.1x – 1.2x
