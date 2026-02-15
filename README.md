Social Listening: Healthcare Access Barriers

Unsupervised social listening study identifying healthcare access barriers (cost, stigma, geography, literacy, bureaucracy) in Reddit discussions using NLP, topic modeling, and time-series analysis.

Project Overview

This project analyzes Reddit discussions across health-related communities to:

Identify common structural and psychological barriers to care

Detect intent and sentiment patterns

Extract latent topics using LDA and BERTopic

Explore temporal relationships using Granger causality tests

Methods

Text preprocessing and cleaning

Barrier and intent tagging

Sentiment analysis (VADER)

Topic modeling (LDA, BERTopic)

Monthly panel construction

Granger causality testing

1. How to :
Clone the repository

2. Install dependencies:
pip install -r requirements.txt


3. If pulling live Reddit data, set Codespaces secrets:
REDDIT_CLIENT_ID
REDDIT_CLIENT_SECRET
REDDIT_USER_AGENT

4. Open:
notebooks/Final_Project.ipynb

Notes:
No raw Reddit credentials are stored in this repository.
API credentials are handled securely using environment variables.
