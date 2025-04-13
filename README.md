# 💳 Credit Card Recommender System

This project is a machine learning-based recommendation system for credit cards, built from web-scraped data and designed to help users discover cards based on their preferences, financial profile, and credit score tier.

## 🔍 Overview
Using Python and scikit-learn, this project scrapes credit card data from Credit Karma and classifies them by:

- Credit score eligibility (Excellent, Good, Fair, Bad)
- APR ranges
- Annual fees
- Cashback and reward rates
- Welcome bonuses

It then uses a K-Nearest Neighbors (KNN) model to recommend cards based on content similarity.

## 📦 Features
- ✅ Web scraping with BeautifulSoup
- ✅ Feature engineering of real-world credit card attributes
- ✅ One-hot encoding of credit tiers
- ✅ Scaled numerical inputs for ML modeling
- ✅ KNN-based recommender system to suggest similar cards
- ✅ Clean, exportable dataset (labeled_credit_cards.csv)

## 🧠 Tech Stack
- Python 3
- pandas, NumPy
- BeautifulSoup for web scraping
- scikit-learn for ML
- VS Code (development + testing)
- (Soon) Streamlit for web app deployment

## 🙌 Acknowledgments
Credit card data scraped from public listings on Credit Karma.
