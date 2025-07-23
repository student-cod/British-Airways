# British Airways Customer Sentiment Analysis

## Project Overview

This project analyzes customer reviews of British Airways to derive actionable business insights. It uses **web scraping, NLP sentiment analysis (TextBlob & Vader), and data visualization** to understand passenger perceptions and identify key areas for service improvement.

---

## Objective

To analyze customer reviews using sentiment analysis techniques to:

- Understand overall passenger perception
- Identify pain points
- Derive insights for enhancing customer experience

---

## Tools & Libraries Used

- **Languages & IDE:** Python (Jupyter Notebook)
- **Web Scraping:** requests, BeautifulSoup
- **Data Processing:** pandas, re, nltk
- **Sentiment Analysis:** TextBlob, vaderSentiment
- **Visualisation:** matplotlib, WordCloud

---

## Workflow Summary

1. **Data Acquisition:** Scraped 1000+ reviews from Skytrax using BeautifulSoup.
2. **Data Cleaning & Preprocessing:** Lowercased text, removed numbers/punctuation, filtered stopwords.
3. **Sentiment Analysis:**
   - **TextBlob:** Polarity scoring for Positive, Neutral, Negative classification.
   - **Vader:** Compound scoring for fine-tuned sentiment classification.
4. **Visualisation:** Generated pie charts, bar graphs, and word clouds to summarise insights.

---

## Key Findings

- **TextBlob Sentiment Distribution:** ~40% Positive, ~42% Neutral, ~18% Negative
- **Vader Sentiment Analysis:** Similar distribution with slightly varied thresholds.
- Majority of reviews are neutral or positive, indicating satisfaction but with areas to improve (~18% negative).

---

## Data

- **Dataset:** `data/british_airways_reviews.csv` contains scraped review data used for analysis.

---

## How to Run

```python
# Clone the repository and open the notebook in Jupyter
# Ensure all required libraries are installed before running
