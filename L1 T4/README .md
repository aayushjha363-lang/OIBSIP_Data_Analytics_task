
---

# Twitter Sentiment Analysis Project

### Project Summary

This project focuses on **exploratory data analysis (EDA)** and **sentiment classification** of tweets. The analysis is conducted entirely in the browser using **Jupyter Lite** with Pyodide, requiring no local installation.

---

### Dataset Information

The dataset `Twitter_Data.csv` includes the following columns:

* **clean_text** – Tweets that have been pre-processed and cleaned for analysis.
* **category** – Sentiment label of each tweet:

  * `1` → Positive sentiment
  * `0` → Neutral sentiment
  * `-1` → Negative sentiment

---

### Environment Setup

To execute the analysis in **Jupyter Lite**, install the required Python packages in the first notebook cell:

```python
%pip install pandas matplotlib seaborn wordcloud
```

---

### Key Features

* Perform exploratory analysis to understand tweet patterns and distributions
* Visualize word frequencies using word clouds
* Classify tweets based on sentiment categories
* Generate actionable insights from the sentiment trends

---



