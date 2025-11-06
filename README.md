# 🚨 PumpDetectorBot

**PumpDetectorBot** is a Telegram-integrated Python bot that scans the **Top 500 tokens on CoinMarketCap** every 30 minutes and detects early-stage pump signals based on:

- 📊 **Volume/MarketCap ratio**
- ⚡ **Short-term momentum (1h/24h %)**
- 📈 **Custom volatility and phase filters (Early / Mid / Late)**

The bot identifies tokens with strong breakout potential and sends alerts directly to Telegram with detailed pump phase classification, metrics, and confidence scores.

---

## ✅ Features

- Automated scanning of Top-500 CMC tokens
- Early signal classification (80%+ probability)
- Noise filtering to reduce false positives
- Real-time Telegram alerts
- CSV logging of history and predictions
- Simple + cumulative signal logic
- Phase tagging:
  - 🟢 Early Pump Phase
  - 🟡 Mid Pump Phase
  - 🔴 Late Pump Phase
  - ⚪ Unclear Phase

---

## 💡 Use Cases

- Front-run tokens with early pump behavior
- Detect breakout candidates using volume/momentum
- Integrate into trading dashboards or bots
- Monitor market anomalies in real time

---

## ⚙️ Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PumpDetectorBot.git
   cd PumpDetectorBot
2.	Install requirements:
   pip install -r requirements.txt
3.	Add your API keys:
   	Replace API_KEY with your CoinMarketCap API key
   Replace BOT_TOKEN and CHAT_ID with your Telegram bot credentials
4. Run the bot:
   python pump_detector.py
   
## 📄 License
MIT License 
