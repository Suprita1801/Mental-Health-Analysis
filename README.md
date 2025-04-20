# 🧠 Detecting Mental Health Trends from Social Media Using NLP and Sentiment Analysis

## 📌 Objective

Analyze Twitter posts to detect emotional and mental health trends using NLP, sentiment analysis, and visualization.

---

## 📂 Dataset Overview

- **Source**: Twitter mental health dataset  
- **Size**: 7,983 tweets  
- **Columns Used**: `post_created`, `post_text`, `followers`, `friends`, `favourites`, `statuses`, `retweets`, `label`

---

## 🔍 Operations Performed

### ✅ Operation 1: Data Loading  
Loaded the CSV file and previewed the structure.

### ✅ Operation 2: Initial Preprocessing  
Dropped unnecessary columns, converted timestamps, and checked nulls.

### ✅ Operation 3: Text Cleaning  
- Lowercased text  
- Removed punctuation, emojis, and stopwords

### ✅ Operation 4: Sentiment Analysis (VADER)  
Classified tweets as Positive, Neutral, or Negative.

### ✅ Operation 5: Sentiment Distribution Pie Chart  
Visualized sentiment percentages.

### ✅ Operation 6: General WordCloud  
Common words in all tweets.

### ✅ Operation 7: Sentiment-Specific WordClouds  
Separate clouds for each sentiment.

### ✅ Operation 8: Top Words by Sentiment  
Bar charts of frequent words per sentiment.

### ✅ Operation 9: Most Retweeted Posts  
Top 10 tweets by engagement.

### ✅ Operation 10: Tweet Volume Per Day  
Visualized tweet activity over time.

### ✅ Operation 11: Sentiment Trends Over Time  
Line chart showing changing moods.

### ✅ Operation 12: Day & Hour Analysis  
Most active days and times.

### ✅ Operation 13: Common Hashtags  
Extracted and plotted top hashtags.

### ✅ Operation 14: Sentiment Heatmap  
Mapped sentiment by day and hour.

### ✅ Operation 15: User Metrics Correlation  
Explored relationships between followers, statuses, etc.

---

## 📈 Insights

- Most tweets are **neutral**, followed by **negative**.
- **Weekends & evenings** have more emotional expression.
- **Retweets** highlight which mental health posts resonated.

---

## 🛠️ Tools Used

- `pandas`, `matplotlib`, `seaborn`
- `NLTK`, `VADER`
- `wordcloud`, `re`

---

## ✅ Future Enhancements

- Live Twitter scraping with Tweepy  
- ML classification of disorders  
- Deploy as a Streamlit or Flask web app

---

