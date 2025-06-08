# Fintech App Review Analysis Challenge 🏦📊
**10Academy Artificial Intelligence Mastery**  
*Week 2: Customer Experience Analytics for Banking Apps*

---

## Overview
This repository contains the complete solution for analyzing customer reviews of Ethiopian banking apps (CBE, BOA, Dashen) from the Google Play Store. The project includes:

- **Web scraping** of 1200+ reviews
- **Sentiment analysis** (Positive/Negative/Neutral)
- **Thematic analysis** of key complaint categories
- **Oracle database integration**



---

## Key Features
- **Data Pipeline**: Scraping → Cleaning → Analysis → Visualization → Database
- **Multi-Method Analysis**: TextBlob + spaCy for comprehensive insights
- **Actionable Visualizations**: 
  - Sentiment distribution by bank
  - Common complaint themes
  - Rating vs. sentiment trends
- **Enterprise Integration**: Oracle database schema for bank data

---

## Project Structure
```
fintech-app-analysis/
├── task-1/                  # Data Collection
│   ├── scraper.py          # Play Store scraper
│   └── cleaner.py          # Data preprocessing
│
├── task-2/                  # Analysis
│   ├── analysis.py         # Main analysis script
│   ├── outputs/            # Results (CSV/plots)
│   └── README.md           # Task-specific docs
│
├── task-3/                  # Database
│   ├── db_schema.sql       # Oracle table definitions
│   └── loader.py           # Data import script
│
├── requirements.txt         # Python dependencies
└── README.md                # This file
```
