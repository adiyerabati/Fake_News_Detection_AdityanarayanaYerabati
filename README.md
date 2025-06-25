
# Semantic Classification of News Articles using Word2Vec

## 📌 Objective

The objective of this assignment is to develop a **Semantic Classification** model. You will use the **Word2Vec** method to extract semantic relationships from news articles and train supervised learning models that classify text based on meaning rather than just syntax.

This project aims to provide a foundational understanding of how semantic embedding techniques, when combined with machine learning, can significantly enhance the accuracy and reliability of text classification tasks.

---

## 🧠 Business Objective

The spread of **fake news** has become a major challenge in the digital age. With thousands of news articles published daily, distinguishing credible news from misinformation is increasingly difficult. This poses a threat to public trust and informed decision-making.

The goal of this assignment is to:

- Build a **semantic classifier** that can automatically detect fake news.
- Use **Word2Vec** to identify meaningful patterns in the text.
- Apply **supervised learning models** to classify news articles as **true** or **fake**.
- Support efforts to reduce the spread of misinformation and maintain public trust in media.

---

## 🔄 Pipelines to be Performed

1. **Data Preparation**
2. **Text Preprocessing**
3. **Train-Validation Split**
4. **Exploratory Data Analysis (EDA) on Training Data**
5. **EDA on Validation Data** *(Optional)*
6. **Feature Extraction using Word2Vec**
7. **Model Training and Evaluation**

---

## 📊 Data Dictionary

You will work with two datasets: `True.csv` and `Fake.csv`.

Each dataset contains the following columns:

| Column Name | Description                        |
|-------------|------------------------------------|
| `title`     | Title of the news article          |
| `text`      | Full text of the news article      |
| `date`      | Date of publication of the article |

- `True.csv`: Contains **21,417** true news articles
- `Fake.csv`: Contains **23,502** fake news articles

---

## 📁 Project Structure (Recommended)

