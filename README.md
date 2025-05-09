# 🧠 Analysing Vaccine Perception of Twitter Users

This project investigates public perception of COVID-19 vaccines on Twitter by analyzing tweets posted between January 2021 and March 2023. Our objective is to uncover key factors that shape vaccine attitudes and extract insights that can help public health officials create more effective vaccination campaigns.

## 📂 Dataset

Tweets were collected via Twitter scraping between Jan 2021 – Mar 2023. The dataset includes fields like tweet text, likes, retweets, datetime, etc. You can find the processed dataset in the data/ folder.

## 📊 Tools & Libraries

- Python, Pandas, NumPy
- NLTK, spaCy, Gensim
- Matplotlib, Seaborn, WordCloud
- NetworkX, pyLDAvis
- Jupyter Notebook

## 🛠️ Methods & Analysis Performed

- Exploratory Data Analysis
- Sentiment Analysis using VADER
- Time Series Analysis to visualize sentiment trends over time
- Word Cloud Visualization to identify frequently used terms
- Topic Modelling with LDA to surface underlying themes
- Semantic Network Analysis to uncover relationships between concepts

## 📈 Key Insights

- Sentiment Distribution:
  - 43% of tweets were positive with the mean compound sentiment score of all tweets being 0.07.
  - We can infer that the perceptions of vaccines are generally more positive among Twitter users.

- Time Series Analysis:
  - Positive sentiment peaked in May 2021 following CDC announcements.
  - Sharp drop in Feb 2023 due to misinformation campaigns (e.g., Project Veritas tweet).
  - Illustrated how easy it is to sway public opinion on vaccines using fake news.

- Topic Modelling (using Latent Dirichlet Allocation):
  - Positive Tweets were centered around trust in effectiveness, safety, and scientific innovation.
  - Negative Tweets were based on fear of side effects, misinformation, and political distrust.

- Semantic Network Analysis:
  - Highlighted latent associations between key terms (e.g., "poison" & "stick", "condo" & "covid").
  - Revealed hidden discourse structures, suggesting that external societal issues were entangled with vaccine sentiment.

For detailed information, please refer to `analysis_three.ipynb`.

## 🎯 Conclusion

Despite overall positive sentiment toward COVID-19 vaccines, the analysis highlights how easily public opinion can shift due to fake news and online misinformation. A key takeaway is the importance of transparent communication from public health agencies and the need to proactively address fear and distrust through accessible, accurate information to improve vaccine adoption rates.