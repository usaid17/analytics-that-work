___
# 🐦 Twitter Sentiment Analysis

Analyze the **emotions behind real-time tweets** using the Twitter API and TextBlob.

This project pulls live tweets using a keyword/topic and classifies their sentiment using simple NLP techniques. It's part of my growing collection of practical data science projects — small, focused, and aimed at solving real-world problems step-by-step.

---

## 🚀 Project Purpose

As a beginner in data science, I'm focused on learning by building. This project helps me understand how to:

- Connect to external APIs (Twitter)
- Clean and analyze real-world unstructured text (tweets)
- Use `TextBlob` for basic Natural Language Processing
- Save and structure results for easy visualization

---

## 📦 What's Inside?

- `twitter_sentiment_analysis.ipynb` → Main notebook with code and explanations
- `tweet_sentiments.csv` → Output file storing each tweet and its sentiment scores
- Live sentiment examples printed in the notebook

---

## 📊 What It Does

- Uses **Tweepy** to access Twitter API (v2)
- Filters for English tweets only, excluding retweets
- Uses **TextBlob** to calculate:
  - `Polarity` → How positive/negative the tweet is (scale: -1 to +1)
  - `Subjectivity` → How opinion-based the tweet is (scale: 0 to 1)
- Saves the analysis into a `.csv` file for further insights

---

## 🛠️ How to Run It

1. **Clone the repo** or download the notebook  
2. Install dependencies:

   ```bash
   pip install tweepy textblob pandas
```

3. **Set your Twitter API bearer token** as an environment variable:
    
    
```bash
    `export TWITTER_BEARER_TOKEN='your-secret-token-here'` 
```

4. **Run the notebook** (`twitter_sentiment_analysis.ipynb`)  
The script will fetch tweets, analyze them, and show + save the results.

## 📁 File Structure

```bash

CopyEdit

`📦 twitter_sentiment_analysis/  
┣ 📄 twitter_sentiment_analysis.ipynb  
┣ 📄 tweet_sentiments.csv  
┣ 📄 README.md  
┗ 📄 .gitignore (.env should be ignored if used)`
```

---

## 📌 Notes

- The query is currently set to `Israel vs Iran`, but you can **change it to any topic** you're interested in!
    
- This project uses basic sentiment analysis. Accuracy may vary on sarcasm or complex phrasing — but it’s a great learning step toward more advanced NLP.
    

---

## 💡 Why This Project?

This is one of my early steps into applied data science. My focus is not just to learn tools, but to build intuition, understand real-world workflows, and grow with **purpose and clarity**.

More projects coming soon! 🚀

---

## 📬 Contact

I'm always open to feedback or collaborations!  
📧 Email: _[hiusaidk@gmail.com]_ 
