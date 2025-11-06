#  Reddit Finance Trends Data Scraper

### Overview
The **Reddit Finance Trends Data Scraper** is a Python-based project designed to collect and organize discussions from Reddit’s **r/wallstreetbets** community.  
It allows researchers, analysts, and developers to explore real-time trends, analyze public sentiment, and identify popular financial topics discussed among retail investors.

This project uses Reddit’s official API through the **PRAW** (Python Reddit API Wrapper) library to gather high-quality and structured data such as post titles, scores, timestamps, and engagement metrics.

---

### Objectives
- Collect top or trending posts from **r/wallstreetbets** in a structured format  
- Facilitate further analysis such as:
  - Sentiment evaluation  
  - Stock ticker trend detection  
  - Market movement correlation  
- Provide a modular and reusable data pipeline for Reddit scraping  

---

### Key Features
- Secure Reddit API authentication via environment variables  
- Configurable subreddit, post limits, and time filters  
- Automatic timestamp conversion to readable date formats  
- Exports cleaned data to CSV for seamless analysis  
- Modular design for integration with analytics or visualization tools  

---

### Output
The scraper produces a **CSV dataset** containing structured Reddit post data.  
Each row typically includes attributes such as:
- Post title  
- Upvote score  
- Comment count  
- Date of creation  
- Reddit post URL  
- Body text (if available)

This dataset can then be used for natural language processing, trend mapping, or visualization tasks.

---

### Future Scope
- Integration of **comment scraping** and **keyword filtering**  
- Incorporation of **sentiment analysis** modules  
- Real-time Reddit monitoring for financial trend prediction  
- Dashboard visualization support using Streamlit or Plotly  


