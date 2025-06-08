# 💸 Fintech App Analysis – Multi-Stage Pipeline for App Insights

This repository contains a multi-step data pipeline to **scrape**, **clean**, **analyze**, and **visualize** fintech apps on the Play Store. It’s designed to uncover trends and generate insights for app developers, analysts, and investors in the fintech space.

---

## 🧭 Project Structure

```
fintech-app-analysis/
├── task-1/                     # Data Collection
│   ├── scraper.py             # Play Store scraper
│   └── cleaner.py             # Data preprocessing
│
├── task-2/                     # Analysis
│   ├── analysis.py            # Main analysis script
│   ├── outputs/               # Results (CSV/plots)
│   └── README.md              # Task-specific docs
│
├── task-3/                     # Database
│   ├── db_schema.sql          # Oracle table definitions
│   └── loader.py              # Data import script
│
├── requirements.txt            # Python dependencies
└── README.md                   # You're here
```

---

## 📌 Project Objectives

### ✅ Goal: Collect, process, and analyze fintech apps data from the Play Store

- **Stage 1 – Data Collection**
  - Crawl fintech app metadata from Google Play Store
  - Clean and normalize fields like ratings, installs, etc.
  - Store raw and processed data

- **Stage 2 – Exploratory Data Analysis (EDA)**
  - Profile app data by category, developer, and region
  - Visualize trends in installs, ratings, updates, and monetization
  - Generate insights for strategic decision-making

- **Stage 3 – Database Setup**
  - Define schema to store cleaned app data
  - Use SQL script to set up and load data into Oracle-compatible DB
  - Enable queries and analytics over structured app metadata

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fintech-app-analysis.git
cd fintech-app-analysis
```

### 2. Set up a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate         # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

---

## 📊 How to Run

### Run Scraper
```bash
cd task-1
python scraper.py
```

### Clean and Process Data
```bash
python cleaner.py
```

### Run Analysis
```bash
cd ../task-2
python analysis.py
```

---

## 🗃️ Database (Optional)

To set up the database:
```sql
-- Inside task-3/db_schema.sql
-- Use Oracle or compatible system
```

To load cleaned data:
```bash
python loader.py
```

---

## 📈 Output

Analysis results and plots are saved in:

```
task-2/outputs/
```

---

## 🧪 Key Features

| Feature                | Implemented |
|------------------------|-------------|
| Play Store Scraper     | ✅ `scraper.py` |
| Data Cleaner           | ✅ `cleaner.py` |
| EDA Charts & Stats     | ✅ `analysis.py` |
| SQL Schema Definition  | ✅ `db_schema.sql` |
| Database Loader Script | ✅ `loader.py` |
| Modular Folder Layout  | ✅ task-wise separation |
| Plot Output Directory  | ✅ `outputs/` |
| Requirements Tracking  | ✅ `requirements.txt` |

---

## 🙌 Acknowledgments

Developed as part of a hands-on data project for fintech trend analysis and app intelligence. Thanks to contributors and open-source tools that made this possible.
