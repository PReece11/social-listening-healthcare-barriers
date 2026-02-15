# 🩺 Social Listening: Healthcare Access Barriers

Unsupervised NLP study identifying structural and psychological barriers to healthcare access in Reddit discussions.

This project analyzes large-scale Reddit conversations to detect cost, stigma, geography, literacy, and bureaucratic barriers to care using topic modeling, sentiment analysis, and time-series modeling.

---

## 🎯 Project Goal

**Research Question**

Do online discussions about cost and stigma predict increases in care avoidance behavior?

Using NLP and temporal modeling, this study evaluates whether barrier-related discourse precedes measurable increases in avoidance intent.

---

## 🧠 What This Project Does

- Identifies healthcare barriers in Reddit posts  
- Detects intent to delay or avoid care  
- Measures emotional tone using sentiment analysis  
- Extracts latent themes via topic modeling  
- Constructs monthly time-series panels  
- Tests predictive relationships using Granger causality  

---

## 🔬 Methods

### NLP Pipeline
- Text preprocessing & cleaning  
- Barrier tagging (cost, stigma, bureaucracy, etc.)  
- Intent detection (avoid vs neutral)  
- Sentiment analysis (VADER)

### Topic Modeling
- LDA  
- BERTopic (sentence-transformers)

### Time-Series Modeling
- Monthly aggregation  
- Interpolation of sparse months  
- Granger causality testin
