# Real Estate Data Agent 🏠🏢

A powerful, automated real estate data collection and analytics system for the Moroccan market.

## 🚀 Features
- **Multi-Source Scraper**: Integrated collectors for **Avito.ma**, **Mubawab.ma**, and **Sarouty.ma**.
- **Data Quality Shield**: 
    - Automatic category cross-checking (Rent vs Sale).
    - Statistical outlier removal (5% trimming).
    - Hard ingestion limits (price/surface) to prevent junk data.
- **Dynamic Dashboard**: Interactive analytics showing price trends, averages per city, and market distribution.
- **CSV Export**: High-reliability export feature for data science and market research.

## 🛠️ Tech Stack
- **Backend**: FastAPI, Python 3.9+, SQLite, BeautifulSoup4.
- **Frontend**: React, Vite, CSS (Glassmorphism design).
- **Communication**: Async HTTP with rate-limit protection.

## 📦 Setup & Installation
1. **Backend**:
   ```bash
   cd backend
   pip install -r requirements.txt
   uvicorn main:app --port 8000
   ```
2. **Frontend**:
   ```bash
   npm install
   npm run dev
   ```

## 📊 Usage
Click "RUN AGENT" on the dashboard to start the 3-phase scraping pipeline. The system will automatically clean and categorize the data before it appears in your charts.
