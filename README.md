# 🔍 TruthLens – Real-Time News Text Analyzer

TruthLens is a Python-based **News Text Analysis application** developed using **Jupyter Notebook**. It analyzes news content using Natural Language Processing (NLP) techniques and provides insights into text statistics, sentiment, keywords, and attention-grabbing language patterns.

> **Note:** TruthLens does not determine whether news is factually true or false. It analyzes linguistic patterns and provides a suspicion indicator.

---

## 🚀 Features

* 📰 News text input and analysis
* 📝 Word count
* 📄 Sentence count
* 🔤 Character count
* 📏 Average word length
* 😊 Sentiment analysis
* 📊 Polarity and subjectivity scores
* 🔑 Keyword extraction
* ⚠️ Suspicion indicator
* 📈 Keyword frequency charts
* 📊 Sentiment visualization
* 📉 Suspicion indicator visualization
* 📋 Final analysis report

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **NLTK**
* **TextBlob**
* **Pandas**
* **Matplotlib**
* **WordCloud**
* **Regular Expressions (Regex)**

---

## 📂 Project Structure

```text
TruthLens/
│
└── TruthLens.ipynb
```

---

## ⚙️ Installation

Make sure Python and Jupyter Notebook are installed.

Open your Jupyter Notebook and run:

```python
%pip install nltk textblob pandas matplotlib wordcloud
```

Then import the required libraries:

```python
import re
import nltk
import pandas as pd
import matplotlib.pyplot as plt

from collections import Counter
from textblob import TextBlob
from wordcloud import WordCloud
from nltk.corpus import stopwords
```

---

## ▶️ How to Run

### 1. Open Jupyter Notebook

Start Jupyter Notebook and open:

```text
TruthLens.ipynb
```

### 2. Run the cells

Execute the cells in order:

```text
Cell 1 → Install Libraries
Cell 2 → Import Libraries
Cell 3 → Enter News Text
Cell 4 → Text Analysis
Cell 5 → Sentiment Analysis
Cell 6 → Keyword Extraction
Cell 7 → Suspicion Analysis
Cell 8 → Charts
Cell 9 → Final Report
```

### 3. Enter news

Paste or type a news article when requested.

Example:

```text
Researchers announced a new technology that could improve
clean energy production. The technology was tested in several
experiments and showed promising results.
```

### 4. View results

TruthLens generates:

```text
Word Count
Sentence Count
Character Count
Sentiment
Polarity
Subjectivity
Top Keywords
Suspicion Score
Suspicion Level
Charts
Final Report
```

---

## 🧠 How TruthLens Works

```text
                 NEWS TEXT
                     │
                     ▼
              TEXT PROCESSING
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
   Text Analysis  Sentiment   Keywords
        │            │            │
        └────────────┼────────────┘
                     ▼
             Suspicion Analysis
                     │
                     ▼
                  Charts
                     │
                     ▼
              FINAL REPORT
```

---

## ⚠️ Suspicion Analysis

TruthLens checks for linguistic patterns such as:

* Sensational words
* Excessive exclamation marks
* Excessive question marks
* ALL-CAPS words

Example:

```text
BREAKING!!! SHOCKING NEWS!!!
You won't believe this incredible discovery!
```

Such patterns may increase the **suspicion score**.

The score is categorized as:

```text
0–19   → LOW 🟢
20–49  → MEDIUM 🟡
50–100 → HIGH 🔴
```

This is a **language-pattern indicator**, not a fact-checking system.

---

## 📊 Output

TruthLens produces visualizations for:

### Keyword Frequency

Shows the most frequently occurring keywords in the article.

### Sentiment

Displays whether the article has predominantly:

* Positive
* Neutral
* Negative

language.

### Suspicion Indicators

Displays counts for:

* Sensational words
* Exclamation marks
* Question marks
* ALL-CAPS words

---

## 🔮 Future Enhancements

Future versions can include:

* 🌐 News URL analysis
* 🎤 Speech-to-text input
* 🤖 Machine-learning-based classification
* 📰 Fact-checking API integration
* 🔎 Source credibility analysis
* 📱 Web application interface
* ⚡ Interactive real-time dashboard
* 📄 PDF report generation
* ☁️ Cloud deployment

---

## 🎯 Project Objective

The main objective of TruthLens is to demonstrate how **Natural Language Processing can be used to analyze news content and identify linguistic patterns associated with sensational or attention-grabbing writing.**

---

## 👩‍💻 Developer

**Mahalakshmi S**

**BE Computer Science and Engineering**

---

## 📜 Disclaimer

TruthLens is an educational NLP project. The suspicion score should **not** be interpreted as proof that an article is fake, misleading, or true. Actual verification requires reliable sources and fact-checking.

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
