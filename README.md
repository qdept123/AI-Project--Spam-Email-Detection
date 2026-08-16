# Email Spam Detection Project 📧

**Course:** CSC 266: Artificial Intelligence  
**Institution:** Vedas College / Affiliated University  
**Submission Date:** End of August, 2026  
**Domain:** Machine Learning & Deep Learning (Natural Language Processing / Text Classification)

---

## 📌 Project Overview

This project is a comprehensive Machine Learning and Deep Learning solution designed to classify email and SMS messages into **Spam** or **Ham (Legitimate)**. The goal is to build, evaluate, and compare multiple predictive models using traditional Supervised Machine Learning algorithms alongside Deep Learning architectures (ANN / RNN / LSTM) to determine the most effective approach for automated spam filtering.

The repository includes a fully runnable Jupyter Notebook on Google Colab/Kaggle, detailed presentation slides, and an IEEE-standard written research report.

---

## 👥 Group Members & Division of Work

| Name | Role / Focus Area | Key Responsibilities |
| :--- | :--- | :--- |
| **Rajat Bikram Karki** | **ML Engineer & Data Analyst** | Implementation of Machine Learning models (Random Forest, K-Nearest Neighbors, Decision Tree, Naive Bayes), TF-IDF Feature Extraction, and Data Preprocessing / EDA. |
| **Samip Khadka** | **DL Engineer** | Architecture design and implementation of Deep Learning models (Artificial Neural Networks - ANN, Recurrent Neural Networks - RNN/LSTM) using TensorFlow/Keras, hyperparameter tuning, and DL evaluations. |
| **Mandeep Kumar Chaudhary** | **Presenation Slide Maker & Documentation** |  Comprehensive Written Report (IEEE format), Presentation Slides (10+ slides), README setup, repository structure, and cross-model performance comparison. |

---

## 🚀 Key Features & Pipeline

1. **Exploratory Data Analysis (EDA):** Word count, character length distributions, class balance visualisations, and word clouds for spam vs. ham messages.
2. **Text Preprocessing & Feature Engineering:**
   - Lowercasing, removal of special characters, numbers, and stopwords.
   - Stemming / Lemmatization.
   - Vectorization using **TF-IDF** (Term Frequency-Inverse Document Frequency) for traditional ML models.
   - Tokenization, Padding, and Embedding layers for Deep Learning models.
3. **Machine Learning Models Implemented:**
   - **Random Forest Classifier** (Ensemble Learning)
   - **K-Nearest Neighbors (KNN)** (Instance-based Learning)
   - **Decision Tree Classifier** (Tree-based Learning)
   - **Naive Bayes Classifier** (Probabilistic Learning - Multinomial/Gaussian NB)
4. **Deep Learning Models Implemented:**
   - **Artificial Neural Network (ANN)** (Sequential Dense layers with Dropout)
   - **Recurrent Neural Network (RNN / LSTM)** (Sequential NLP pipeline for contextual word relationship modeling)
5. **Model Evaluation & Comparison:** Metrics include Accuracy, Precision, Recall, and F1-Score to ensure high precision in identifying spam without misclassifying important ham messages.

---

## 📊 Summary of Implemented Algorithms

| Algorithm | Model Type | Framework / Library | Primary Purpose | Lead Developer |
| :--- | :--- | :--- | :--- | :--- |
| **Random Forest** | Machine Learning | `scikit-learn` | Ensemble classification on TF-IDF features | Rajat Bikram Karki |
| **K-Nearest Neighbors**| Machine Learning | `scikit-learn` | Distance-based text classification | Rajat Bikram Karki |
| **Decision Tree** | Machine Learning | `scikit-learn` | Rule-based hierarchical classification | Rajat Bikram Karki |
| **Naive Bayes** | Machine Learning | `scikit-learn` | Probabilistic NLP text classification | Rajat Bikram Karki |
| **ANN** | Deep Learning | `TensorFlow` / `Keras` | Multi-layer perceptron for feature embeddings | Samip Khadka |
| **RNN / LSTM** | Deep Learning | `TensorFlow` / `Keras` | Sequence modeling for text contextual flow | Samip Khadka |

---

## 🛠️ Installation & Setup Guide

### Option 1: Running on Google Colab (Recommended)
1. Open [Kaggle Code](https://www.kaggle.com/code).
2. Click **File** > **Upload Notebook** and select `Email_Spam_Detection.ipynb`.
3. Upload the `spam.csv` dataset into the Colab session files (or run the Kaggle dataset download block within the notebook).
4. Go to **Runtime** > **Run all**.

### Option 2: Links
1. Link for Machine Learning Algorithms: 
> Google Collab: https://colab.research.google.com/drive/1Nbv2NjDSYvdXLCMGQUycg0z_rOH5ey4V?usp=sharing
> Kaggle: https://www.kaggle.com/code/rajatbikramkarki/email-spam-detection-machine-learning-algorithms

## 📋 Required Python Libraries

- `numpy` & `pandas` — Data manipulation and preprocessing
- `matplotlib` & `seaborn` — Visualization and confusion matrices
- `scikit-learn` — ML algorithm implementation, TF-IDF vectorization, and evaluation metrics
- `nltk` — Text preprocessing (stopwords, tokenization, stemming)
- `tensorflow` / `keras` — DL neural network architectures (ANN, Sequential, Dense, LSTM, Dropout)

---

##  Deliverables Checklist

- [x] **Jupyter Notebook (`.ipynb`)**: Executable on Google Colab / Kaggle with full outputs and markdown documentation.
- [x] **Machine Learning Models**: Random Forest, KNN, Decision Tree, Naive Bayes.
- [x] **Deep Learning Models**: ANN and RNN/LSTM architecture using TensorFlow/Keras.
- [x] **Accuracy Comparison**: Comprehensive comparative table and discussion of metrics.
- [x] **Presentation Slides**: Complete 10+ slide presentation covering problem, methodology, results, and learnings.
- [x] **Written Report**: Formatted according to IEEE referencing standards and required chapter specifications (A4, 1.5 line spacing, Times New Roman 12pt).

---

## 📖 Citation & References

1. UCI Machine Learning Repository / Kaggle: *Email Spam Collection Dataset*: (https://www.kaggle.com/datasets/venky73/spam-mails-dataset)
2. Scikit-Learn Documentation: https://scikit-learn.org/
3. TensorFlow & Keras Guide: https://www.tensorflow.org/ & https://keras.io/
4. IEEE Guidelines for Conference and Academic Papers.
# AI-Project--Spam-Email-Detection
