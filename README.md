This is a Streamlit web application that functions as a stock search engine with forecasting capabilities. Here's a short overview of its key features:
Search Functionality: Users can search for stock information by entering ticker symbols (e.g., AAPL, MSFT).
Real-Time Data: The app attempts to fetch real-time stock quotes from multiple APIs (Finnhub, Yahoo Finance, Alpha Vantage) with fallback options if any fail.
Data Visualization: Displays interactive charts using Plotly for stock price history.
Price Forecasting: Offers both short-term (7-day) and long-term (6-month) price predictions based on historical data analysis.
Prediction Reasoning: Provides explanations for the predictions based on metrics like price trends, trading volume, volatility, technical indicators, and sector conditions.
Mock Data Generation: Falls back to algorithmically generated mock data if API calls fail, ensuring the app always displays something useful.
User Interface: Features a dark-themed UI with responsive stock cards and forecasting panels.
