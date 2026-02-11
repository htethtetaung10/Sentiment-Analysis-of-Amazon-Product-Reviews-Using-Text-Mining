# Sentiment-Analysis-of-Amazon-Product-Reviews-Using-Text-Mining
This repository contains the implementation and experiments for my **Master’s Thesis** on sentiment analysis using text mining techniques.

## 📌 Project Overview
This study has applied five different machine learning algorithms of Bernoulli Naive Bayes, Complement Naive Bayes, Logistic Regression, Linear Support Vector Machine and Random Forest on the Amazon fine food products reviews to predict sentiment (positive or negative). The dataset is imbalanced. Therefore, the data has been prepared to be balanced and qualified using random resampling and random undersampling. After balancing the data, the size of data has been decreased due to undersampling. This study has conducted three experiments using unigrams, bigrams, and trigrams in TF-IDF. The results from the study showed that in terms of accuracy, the Linear Support Vector Classifier model got the highest accuracy (91.21) and outperformed among the proposed models while the Naive Bayes models had the lowest accuracies. In terms of running time, Naive Bayes models were the fastest ones than the other models while the Random Forest Classifier consumed the longest time among other models.

**Keywords: Natural Language Processing (NLP), Sentiment Analysis, Text Mining, Tokenization, Machine Learning, Word2vec, N-gram, Product Reviews.**

## 🔧 Techniques Used
- Text preprocessing & cleaning
- Feature engineering
- TF-IDF feature extraction
- Sampling techniques
- Machine learning models (Bernoulli Naive Bayes, Complement Naive Bayes, Logistic Regression, Linear Support Vector Machine and Random Forest)

## 📊 Dataset
Amazon fine food product review dataset (text-based) from Kaggle

## 📁 Repository Structure
- `data/` – Raw and processed datasets (https://drive.google.com/drive/folders/1cWT15d4MXJAboiR_JkcC_ZPYO2np0O3x?usp=drive_lin)
- `final_model/` – Trained models (https://drive.google.com/drive/folders/1DN6GpoAyvy5s8KyGC-b51HBiLy0Bnr-C?usp=drive_link)
- `tfidf_models/` – TF-IDF experiments (https://drive.google.com/drive/folders/15NTZzEPDrS64TXGuoOnNNtjaDoq8W_4q?usp=drive_link)
- `*.ipynb` – Experiment notebooks
- `cloud_shape.png` – Word cloud representing sentiment distribution in the dataset

## 🎓 Academic Context
This work was developed as part of my Master’s thesis in Computer Science.

## 🔗 Relevant Links
- **University repository**: https://dea.lib.unideb.hu/browse/subject?scope=a250708c-1ca3-4ef3-960d-18065f388c22&value=Text%20Mining&bbm.return=1
- 📂 **GitHub Repository**: https://github.com/htethtetaung10/Sentiment-Analysis-of-Amazon-Product-Reviews-Using-Text-Mining
- 📊 **Dataset (Amazon Food Product Reviews)**: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
- 📓 **Notebook (Sentiment Analysis Pipeline)**: sentiment-analysis-final-model.ipynb
- 📘 **Thesis Document (PDF)**: https://drive.google.com/file/d/1lYq3Ke_xH5EJ-nEPRI3AfrVy4Hi9ha50/view?usp=drive_link
- 🧠 **TF-IDF Reference**: https://scikit-learn.org/stable/modules/feature_extraction.html


