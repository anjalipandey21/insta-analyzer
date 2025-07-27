# 📸 Predicting Instagram Engagement Using Images and Captions

## 📘 Project Overview
This project explores what drives engagement on Instagram by analyzing a brand’s posts using both image content and captions. Using data scraped from Instagram and labeled via a computer vision API, the project predicts engagement levels and extracts meaningful content themes using NLP and logistic regression.

---

## 🧠 What This Project Does
- Scrapes Instagram post data: captions, image URLs, and like counts.
- Uses image recognition (Google Vision / Azure) to extract labels from each image.
- Classifies posts as **high or low engagement** based on median likes.
- Builds logistic regression models to predict engagement using:
  - Image content (labels)
  - Post captions
  - A combination of both
- Performs **topic modeling** (LDA) on image content to uncover recurring themes.
- Compares top-performing vs. low-performing content based on topics and suggests engagement strategies.

---

## 📊 Key Features & Insights
- **Multimodal Analysis**: Combines vision + text to understand content impact.
- **Engagement Prediction**: Logistic regression identifies content patterns linked to higher engagement.
- **Topic Modeling**: LDA reveals visual themes associated with likes.
- **Strategic Recommendations**: Offers data-backed content strategies for improving Instagram performance.

---

## ⚙️ Technologies Used
- `Python 3.x`
- `Instaloader` (or custom scraper)
- `Google Cloud Vision API` or `Azure Vision`
- `scikit-learn` (logistic regression, evaluation)
- `Gensim` (topic modeling - LDA)
- `Pandas`, `NumPy` (data handling)
- `Matplotlib`, `Seaborn` (visualizations)

---

## 📂 Project Structure
- Main notebook containing data scraping, labeling, analysis, modeling, and results.
- This documentation file.

---

## 🚀 How to Run
1. Ensure all required packages are installed:
   ```bash
   pip install pandas numpy gensim scikit-learn matplotlib seaborn
