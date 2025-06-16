# 📰 Financial News Sentiment Analysis & Stock Correlation

A financial analytics project that explores the relationship between news sentiment and stock price movements using Natural Language Processing (NLP), quantitative indicators, and correlation analysis.

---

## 📋 Table of Contents

1. [Project Overview](#project-overview)  
2. [Business Objective](#business-objective)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Project Structure](#project-structure)  
6. [Features](#features)  
7. [Tasks and Deliverables](#tasks-and-deliverables)  
---

## 🔍 Project Overview

This project analyzes a large corpus of financial news headlines and correlates them with stock market movements. It includes sentiment analysis using NLP tools, technical indicator computation using TA-Lib and PyNance, and visual/quantitative analysis of time-series stock data.

---

## 🎯 Business Objective

Nova Financial Solutions aims to improve its forecasting accuracy using news sentiment as a predictive tool. This project helps discover correlations between public sentiment (extracted from headlines) and stock performance, supporting smarter investment strategies.

---

## ⚙️ Installation

Clone the repo and install required packages:

```bash
git clone https://github.com/Yeabfikre/Financial-news-sentiment-stock-analysis.git
cd Financial-news-sentiment-stock-analysis
pip install -r requirements.txt
```

## ▶️ Usage
Run notebooks step-by-step or use the pipeline.

### 📘 Notebooks
```
jupyter notebook notebooks/task1_exploratory-data-analysis.ipynb
jupyter notebook notebooks/task2.ipynb
jupyter notebook notebooks/task-3.ipynb
```
---
## 📁 Project Structure
```text
├── .github/workflows/
│   └── unittests.yml
├── .vscode/
│   └── settings.json
├── notebooks/
│   ├── task1_exploratory-data-analysis.ipynb
│   ├── task2.ipynb
│   └── task-3.ipynb
├── scripts/
│   └── README.md
├── src/
│   └── __init__.py
├── tests/
│   └── __init__.py
├── .gitignore                        
├── requirements.txt
├── LICENSE
└── README.md
```
---
## 🌟 Features
- 🧠 NLP-based Sentiment Analysis using NLTK, TextBlob
- 📈 Technical Analysis with TA-Lib (RSI, MA, MACD)
- 📊 Correlation Analysis of sentiment vs. stock returns
- 🧪 Git-based CI/CD with unit test automation
- 📅 Time series and publishing trend analysis
- 🌐 Clean GitHub workflow and environment setup

## ✅ Tasks and Deliverables
### 🔧 Task 1: Git + EDA + Setup
- GitHub repo setup, branch naming, CI integration
- Basic headline stats, publisher trends, publishing frequency
- Topic modeling and time-series EDA

### 📊 Task 2: Technical Indicator Analysis
- Compute MA, RSI, MACD with TA-Lib
- Integrate PyNance for additional metrics
- Visualize technical indicators

### 📉 Task 3: Sentiment-Stock Correlation
- Sentiment scoring of headlines
- Align stock and news dates
- Correlate average daily sentiment with daily returns
- Pearson coefficient + visual insight
