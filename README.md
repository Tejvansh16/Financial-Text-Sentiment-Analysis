# 💹 Financial Text Sentiment Analysis  

A Natural Language Processing (NLP) project to perform sentiment analysis on financial news articles using **FinBERT**, a domain-specific version of BERT.  

---

## 📌 Project Overview  
This project uses **FinBERT** to classify financial news articles as **Positive**, **Negative**, or **Neutral**. By analyzing sentiment from financial news, the system provides insights to assist in investment decisions.  

### ✅ **Key Objectives:**  
- Extract financial news using **Yahoo Finance RSS Feeds**.  
- Perform sentiment analysis using **FinBERT** via Hugging Face Transformers.  
- Calculate an **Overall Sentiment Score** to evaluate the market sentiment.  
- Provide actionable insights for financial decision-making.  

---

## 🗂 Dataset and Tools  
- **Data Source:** Financial news articles from Yahoo Finance RSS Feeds.  
- **Model:** **FinBERT** (Fine-tuned BERT for financial sentiment analysis).  
- **Libraries:**  
  - Transformers  
  - Feedparser  
  - Requests  
  - Pandas  

---

## 🚀 Approach  

1. **Data Extraction:**  
    - Extracted financial news articles using **Yahoo Finance RSS Feeds**.  
    - Filtered relevant articles based on keywords like company names or stock tickers.  

2. **Sentiment Analysis:**  
    - Applied **FinBERT** using Hugging Face’s pipeline for classification.  
    - Classified articles into **Positive**, **Negative**, or **Neutral** categories.  

3. **Score Calculation:**  
    - Calculated an **Overall Sentiment Score** based on classified article sentiments.  
    - Defined score thresholds for sentiment determination:  
      - **Score ≥ 0.15:** Positive  
      - **Score ≤ -0.15:** Negative  
      - Otherwise: Neutral  

---

## 📊 Results and Insights  

- **Example Sentiments:**  
  - `"Stocks rallied and the British pound gained."` → **Positive** (Score: 0.89)  
  - `"Stocks are down."` → **Negative** (Score: 0.92)  
  - `"Tesla to build new megafactory in Texas."` → **Neutral** (Score: 0.82)  

- The model effectively classified financial articles with confidence scores using FinBERT.  
- The system provides actionable insights for investors by analyzing real-time market sentiment.  

---
