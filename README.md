# LLM Pages
This repository hosts automatically generated web applications. The codebase is **completely replaced** on each deployment.
## 🚀 Current Deployment
**Task:** StockMarket
**Round:** 1
**Deployed:** 2026-07-16 05:07:32 UTC
### Description
Build a modern, professional Stock Screening web application similar to Finviz or TradingView.

The application must fetch real-time stock market data using a free public stock market API.

Requirements:

• Allow users to search for stocks by company name or ticker symbol.

• Display a responsive table containing:
  - Company Name
  - Stock Symbol
  - Current Price
  - Daily Change (%)
  - Market Cap
  - Volume
  - 52 Week High
  - 52 Week Low

• Allow sorting on every column.

• Allow filtering by:
  - Market Cap
  - Price Range
  - Daily Gain/Loss
  - Volume

• Include a watchlist where users can bookmark stocks.
  Save the watchlist using localStorage.

• Clicking a stock should open a detailed modal containing:
  - Live Price
  - Previous Close
  - Open Price
  - High
  - Low
  - Volume
  - Company Information

• Display an interactive price chart for the selected stock.

• Automatically determine the most appropriate free stock market API.

• If the chosen API requires an API key:
  - Generate a collapsible "API Settings" panel.
  - Allow users to enter their API key.
  - Save the key in localStorage.
  - Automatically restore it on page load.
  - Validate the API key before using it.
  - Display clear error messages if the key is invalid.

• If a free API without authentication is available, prefer that API.

• Implement loading indicators while fetching market data.

• Handle:
  - Invalid stock symbols
  - Network failures
  - API rate limits
  - Empty search results

• Make the UI fully responsive for desktop, tablet, and mobile.

• Use modern cards, smooth animations, hover effects, and a professional dashboard layout.

• Generate everything in a single standalone index.html with inline CSS and JavaScript.

Do not use dummy or static stock data.
Always fetch live market data from the selected API.
## 🌐 Live Application
**[View Current App](https://prathitnarayan.github.io/LLM-Pages/)**
---
## 📝 About This Repository
- **Purpose:** Automated deployment of LLM-generated applications
- **Behavior:** Each deployment completely replaces the previous codebase
- **Updates:** Code is regenerated on demand based on task requirements
- **Technology:** Single-page HTML applications with inline CSS/JS
## 🔄 Deployment History
This README is updated with each deployment. Previous deployments are tracked in commit history.
### Latest Changes
- **Task:** StockMarket
- **Brief:** Build a modern, professional Stock Screening web application similar to Finviz or TradingView.

The application must fetch real-time stock market data using a free public stock market API.

Requiremen...
- **Round:** 1
- **Timestamp:** 2026-07-16 05:07:32 UTC
---
*Powered by AI Project Generator | Last updated: 2026-07-16 05:07:32 UTC*
