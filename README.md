
# 📊 Sentiment Analysis & User Profiling in Reviews

This repository contains code for performing **sentiment analysis** and **user profiling** on a dataset of user reviews. The project focuses on **text preprocessing, sentiment classification, topic modeling, and user segmentation** based on review characteristics.

## 🚀 Project Overview
This project was a **group effort**, and the dataset was originally obtained through web scraping. However, **this repository contains only the parts I contributed to**, including **data preprocessing, sentiment analysis, user profiling, and topic modeling**.

The goal of the project was to:
- **Clean and preprocess** user reviews for further analysis.
- **Perform sentiment classification** using **RoBERTa**.
- **Extract topics** from reviews using **LDA topic modeling**.
- **Profile users** based on their review behavior and sentiment.

## 🔧 Methodology
1. **Data Preprocessing**
   - Removal of punctuation, special characters, and stopwords.
   - Tokenization & Lemmatization.
   - Encoding categorical features and standardizing numerical data.

2. **Sentiment Analysis**
   - Classification of user reviews as **positive, negative, or neutral** using **Sentiment RoBERTa**.
   - Generation of **WordClouds** to visualize sentiment-based keywords.

3. **User Profiling**
   - Extracting **review-based behavioral features** (e.g., text length, punctuation use).
   - Training a **Random Forest Classifier** to predict user attributes.
   - Analyzing sentiment distribution across different user groups.

4. **Topic Modeling**
   - Using **LDA (Latent Dirichlet Allocation)** to extract main themes from reviews.
   - Visualizing key topics using **pyLDAvis**.

## 📊 Results & Findings
- Sentiment analysis achieved **high accuracy** in classifying review sentiment.
- Certain topics (e.g., **customer service**, **product quality**) appeared frequently across reviews.
- Male and female users showed **different sentiment trends** in their reviews.
- Behavioral patterns in review writing helped distinguish **user groups**.

## 📜 Acknowledgment
This project was a **group effort**. **The uploaded files correspond to the parts I actively contributed to**, but credit is shared with my teammates.

## 📌 References
- [Hugging Face Sentiment RoBERTa](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)
- [Scikit-learn](https://scikit-learn.org/)
- [NLTK for text preprocessing](https://www.nltk.org/)
- [PyLDAvis for topic modeling visualization](https://pyldavis.readthedocs.io/)

---
