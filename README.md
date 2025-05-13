# 🔍 LLM-Based Query Answering System with Web Scraping

This project is a complete pipeline for answering user queries by retrieving and scraping relevant webpages, processing the extracted data, and (optionally) generating responses using OpenAI's language model. It comes with two interfaces:
- ✅ Flask-based backend
- ✅ Streamlit front-end for user interaction

---

## 💡 Features

- 🌐 Google Search Integration to fetch relevant articles
- 🧠 Web Scraper to extract content from the top results
- 📝 Text Processing to clean and format context
- 🤖 OpenAI GPT Model Support (fallback to scraped content if not working)
- 🖥️ Streamlit Interface for real-time user queries
- 🛠️ Flask Backend for modular integration

---

## ⚙️ Tech Stack

- **Python 3.8+**
- **Flask**
- **Streamlit**
- **BeautifulSoup4** (`bs4`)
- **Google Search API** (`googlesearch-python`)
- **OpenAI GPT (optional)**

---

## ⚠️ Important Note

> 🔐 The OpenAI integration is included, but GPT-based response generation is not functional due to the absence of a **paid API key**. However, the system **fully works** by scraping relevant content from the web and displaying it in a clean format.

---

## 🧪 How It Works

1. **User enters a query**
2. **Google Search** finds top N results
3. **Scraper** fetches and cleans article content
4. **OpenAI (optional)** attempts to summarize or answer using scraped data
5. **Streamlit or Flask** frontend shows the result (scraped content is shown if OpenAI is not configured)

---

## 🧰 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/BharatDhande/LLM.git
cd LLM
"# LLM-Assignment" 
