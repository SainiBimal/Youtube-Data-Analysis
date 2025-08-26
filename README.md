# 🎥 YOUTUBE DATA ANALYSIS

This repository provides an **end-to-end analysis of YouTube channel performance metrics** using **Python, Pandas, Matplotlib, and Seaborn**.  
It explores **revenue sources, engagement, subscriber trends, and watch-time performance** to uncover actionable insights for content growth.  

🔗 [Project Repository](https://github.com/SainiBimal/Youtube-Data-Analysis)


---

## 📌 Project Overview

- Dataset: **364 video records** with **70+ performance metrics**  
- Features include:  
  - Video duration, publish time, watch time, CTR, engagement metrics  
  - Revenue sources (AdSense, Premium, Transactions)  
  - Subscriber activity (new subs, unsubscribes, churn rate)  
- Goal: Identify **factors driving views, engagement, and revenue** for a YouTube channel.  

---

## 🔍 Key Analyses & Insights

### 📈 Univariate Analysis
- **Revenue per 1000 Views (RPM)** distribution – Most videos earn under $0.20 per 1k views.  
- **Video Duration** – Majority are medium-length (5–15 minutes).  
- **Thumbnail CTR** – Most videos average 2–8%, skewed distribution.  

### 📊 Bivariate & Multivariate Analysis
- **Revenue Breakdown**:
  - YouTube Ads ~ largest share.  
  - Premium & Transactions ~ smaller contributions.  
- **Subscribers**:
  - Gained vs Lost → Visualized monthly subscriber churn.  
- **Engagement Mix**:
  - Likes dominate (~75%), Comments & Shares add ~20%.  

### 📅 Time-Series Trends
- **Monthly Subscriber Activity**: Clear spikes during viral video launches.  
- **Like/Dislike Ratio**: Improved consistently post-2020.  
- **Churn Rate**: Averaged 2–4%, with peaks after low-engagement uploads.  

### 👁️ Watch-Time Analysis
- **Top 20 videos by watch hours** drive ~60% of channel’s total watch time.  
- Longer videos (>10 mins) tend to yield higher watch hours.  
- **View Duration vs View %**:
  - Videos with **CTR > 8%** show **higher average view duration**.  

### 📊 Correlation Insights
- **Engagement Rate vs Revenue per View** → Positive relationship, high-engagement videos bring better ad revenue.  
- **Views vs Subscribers** → Strong link: Top viewed videos correlate with max subscriber growth.  

---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `ytb.ipynb` | Main Jupyter Notebook with analysis |
| `Youtube Data Analysis.pdf` |Final Presentation |
| `youtube_channel_real_performance_analytics.csv` | Dataset |
| `README.md` | Project documentation (this file) |

---

## 🚀 Tools & Technologies

- **Python (Pandas, NumPy)** – Data wrangling & feature engineering  
- **Matplotlib / Seaborn** – Visualization  
- **Google Colab / Jupyter** – Development environment  

---

## 📌 Business Insights

- Videos with **higher thumbnail CTR & longer duration** drive more subscribers.  
- Engagement (likes, shares, comments) strongly impacts **revenue per view**.  
- Ad revenue remains dominant, but **YouTube Premium share is growing** steadily.  
- Churn analysis highlights the importance of consistent, high-engagement uploads.  

---

## 🔮 Future Scope

- Build **predictive ML models** for revenue & subscriber growth.  
- Create a **Power BI dashboard** for channel performance.  
- Apply **clustering** to segment videos by performance types (viral, evergreen, low-performing).  
- Experiment with **NLP sentiment analysis** on comments for deeper audience insights.  

---

![Visitor Count](https://komarev.com/ghpvc/?username=SainiBimal&style=flat-square)

---

## 🙌 Author

**BIMAL KUMAR SAINI**  
Data Analyst Intern  
📧 bimalsaini333@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bimalsaini333/) | [GitHub](https://github.com/SainiBimal)
