# 🚀 CryptoCurrency

A React application for tracking real-time cryptocurrency prices and market data using the CoinGecko API.

## Features

- Real-time price updates every 3 seconds
- Search cryptocurrencies by name or symbol
- Detailed coin page with 7-day price chart
- Market stats: market cap, volume, circulating supply

## Tech Stack

- **React** — UI
- **React Router** — navigation
- **Recharts** — price chart
- **CoinGecko API** — cryptocurrency data

## Getting Started

### Prerequisites

- Node.js v18+
- npm

### Installation

```bash
git clone 
cd crypto-tracker
npm install
npm run dev
```

App will be running at `http://localhost:5173`

## Project Structure

```
src/
├── api/
│   └── coinGecko.js       # API calls
├── components/
│   └── CryptoCard.jsx     # Coin card component
├── pages/
│   ├── Home.jsx           # Main page with coin list
│   └── CoinDetail.jsx     # Individual coin page
├── utils/
│   └── formatter.js       # Price/marketcap formatting
├── App.jsx
├── main.jsx
└── index.css
```

## API

Data is fetched from [CoinGecko](https://www.coingecko.com/en/api) — free tier, no API key required.


## BYE
