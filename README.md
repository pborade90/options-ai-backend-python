# 📈 Options-AI Backend (FastAPI)

This is the backend API service for the **Options-AI** stock prediction platform. It uses FastAPI to serve LSTM-based machine learning predictions for stock data, along with historical trends and yearly analysis.

---

## 🚀 Features

- ✅ Fetch 20 years of historical stock data using `yfinance`
- ✅ Train and serve an LSTM model for future stock price prediction
- ✅ Yearly analysis for line graph plotting
- ✅ Automatically caches trained models
- ✅ CORS-enabled for frontend access
- ✅ RESTful API with Swagger documentation

---

## 🛠️ Tech Stack

- **FastAPI** for building the API
- **TensorFlow / Keras** for LSTM-based ML
- **yfinance** for stock data
- **Pandas / NumPy** for data processing
- **Uvicorn** as ASGI server

---

## 📦 Installation

```bash
git clone https://github.com/your-username/options-ai-backend.git
cd options-ai-backend
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
