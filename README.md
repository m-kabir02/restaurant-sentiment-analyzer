# 🍽️ Restaurant Review Sentiment Analyzer

A web app that analyzes restaurant reviews using **Hugging Face Transformers** (RoBERTa) and the **Yelp Fusion API**.  
Users can search for a restaurant, fetch live Yelp reviews, and see sentiment insights (positive, neutral, negative).

## 🚀 Features
- Search for restaurants by name + location.
- Fetch latest Yelp reviews via API.
- Analyze sentiment with **RoBERTa (cardiffnlp/twitter-roberta-base-sentiment)**.
- Interactive dashboard:
  - Sentiment distribution chart
  - Confidence scores
  - Reviews tagged with sentiment

## 🛠️ Tech Stack
- **Python 3.9+**
- **Streamlit** (UI + dashboard)
- **Transformers (Hugging Face)**
- **Plotly** (visualizations)
- **Yelp Fusion API** (review data)

## ⚡ Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/restaurant-sentiment-analyzer.git
   cd restaurant-sentiment-analyzer
