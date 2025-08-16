# ⚡ Data Analyst Agent
> **Smarter, faster, and more intuitive data analysis** powered by **Generative AI + Python magic** ✨  

📂 Repository: *[[Insert your GitHub link here]](https://github.com/DevyanshJain/TDS-Data-Analyst-Agent)*  
🌐 **Live Demo:** [tds-data-analyst-agent-kr6j.onrender.com](https://tds-data-analyst-agent-kr6j.onrender.com/)  

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
![Python](https://img.shields.io/badge/python-3.9%2B-brightgreen)  
![FastAPI](https://img.shields.io/badge/FastAPI-🚀-teal)  
![Status](https://img.shields.io/badge/deployed-Live-green)  

---

## 📌 Overview  

Meet **Data Analyst Agent 2.0** — your **AI-powered data companion** that transforms raw datasets into **visual insights, reports, and summaries** within seconds.  

✅ AI-powered insights  
✅ Automated EDA & reports  
✅ Rich visualizations  
✅ Batch query support  

---

## ✨ Features  

| Feature 🚀 | Why It’s Awesome 😎 |
|------------|----------------------|
| 🤖 **AI-Powered Insights** | Google’s Generative AI interprets queries like a human |
| 📊 **Visual Reports** | Generate plots with *Seaborn & Matplotlib* |
| 🌍 **Web Scraper Mode** | Import live data from URLs |
| 📂 **Multi-Format Input** | Works with CSV, Excel, JSON, Parquet, TXT |
| 🔄 **Batch Q&A** | Ask multiple questions at once |
| 🖥️ **Beginner Friendly** | Minimal setup, clean UI |
| ⚡ **Blazing Fast** | Real-time processing with FastAPI |

---

## 🚀 Getting Started  

### 🔹 Option 1: Try Live Demo  
👉 [Click Here to Use Now](https://tds-data-analyst-agent-kr6j.onrender.com/)  

### 🔹 Option 2: Run Locally  

1️⃣ Clone the repo  
```bash
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent
```

2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

3️⃣ Configure API keys (.env)
```ini
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240
```

4️⃣ Run the app
```bash
python -m uvicorn app:app --reload
```

Now open [**http://localhost:8000/**](http://localhost:8000/) in your browser

## 🧑‍💻 Usage
1. Prepare Queries (questions.txt)
```text
What’s the revenue growth month-over-month?
Find correlation between Age and Income.
Show top 5 most profitable products.

```
2. Upload Dataset + Questions
- **Dataset (optional):** CSV, Excel, JSON, Parquet, TXT  
- **Queries (required):** Plain text file  
3. Results
- 📊 **AI-generated visualizations**  
- 📑 **Summaries & correlations**  
- 📈 **Insights in seconds**

## 🛠 Tech Stack
**Backend:** FastAPI, LangChain, Google Generative AI, Pandas, NumPy  
**Frontend:** HTML5, CSS, JavaScript (Bootstrap-inspired)  
**Visualization:** Seaborn, Matplotlib  

---

## 🔧 API Endpoints  

| Method | Endpoint   | Purpose                  |
|--------|------------|--------------------------|
| `GET`  | `/`        | Web app interface        |
| `POST` | `/api`     | Submit dataset + queries |
| `GET`  | `/summary` | Diagnostics & summaries  |

---

## 📂 Supported Formats  

| Format | Extensions        |
|--------|------------------|
| CSV    | `.csv`           |
| Excel  | `.xlsx`, `.xls`  |
| JSON   | `.json`          |
| Parquet| `.parquet`       |
| Text   | `.txt`           |

---

## 🎯 Use Cases  

- 📈 **Business Analytics** – KPIs, forecasts, growth reports  
- 🔬 **Research** – Data exploration, validation  
- 🤖 **Data Science** – EDA, anomaly detection  
- 📊 **Reporting** – Automated dashboards  

---

## 🔒 Security  

- ✅ Runs locally → no third-party storage  
- ✅ API keys via `.env`  
- ✅ Configurable CORS policy  

---

## 📜 License  

Licensed under **MIT** – free for personal & commercial use.  
