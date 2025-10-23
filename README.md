# Backtesting System  
Teh Chern  


This is a personal project of running a backtesting system using the multiple technical indicators to evaluate the Tech Giants in the U.S. stock market. 

### **Assumptions:**   
• Initial capital: USD 100,000         
• Backtesting date range: 2000-01-01 to 2024-12-31   
• Indicators: RSI 14 30 70, MA 50 200  
• Stocks to compare with NASDAQ: AAPL, MSFT, NVDA, META, GOOG, AVGO, TSM, AMD  
### **Trading Strategies:** 
1. **'RSI'** : Buy when RSI < 30, Sell when RSI > 70  
2. **'MA'** : Buy when Golden Cross, Sell when Death Cross  
3. **'RSI, MA'** : Buy when RSI < 30 and 50MA > 200MA, Sell when RSI > 70 and 50MA < 200MA
