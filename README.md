# 📰 Fake News Generator and Detector using Generative AI

This project combines Natural Language Processing (NLP) and Generative AI to **detect** whether a given news article is fake or real and also to **generate fake news** samples using a language model. It helps highlight the dangers of AI-generated misinformation and equips systems to detect it more effectively.

---

## 🔍 Features

- **Fake News Detection**:
  - Classifies input news text as either **"Fake News"** or **"Not A Fake News"**.
  - Uses NLP preprocessing (tokenization, stopword removal, etc.)
  - Trained on a labeled dataset of true and fake news.

- **Fake News Generation**:
  - Uses Generative AI (e.g., GPT-based models) to create realistic but fake news for research and training purposes.
  - Can simulate misinformation scenarios.

---

## 📁 Dataset

### ✅ True News Dataset:
- Contains verified and fact-checked news articles from reliable sources.
- Collected from sources like **Kaggle, news APIs, or scraping authenticated news**.

### ❌ Fake News Dataset:
- Contains misinformation, hoaxes, or fabricated articles.
- Includes data from known fake news websites and synthetic examples for training.

> 📌 Both datasets are typically combined into a single DataFrame with labels:
```python
Label: 0 -> Fake News  
Label: 1 -> Real News
