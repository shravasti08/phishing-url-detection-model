# 🚨 Phishing URL Detection  
A machine learning project that detects phishing URLs by comparing various classification algorithms.

## 📌 Project Overview  
This project analyzes URLs and classifies them as **phishing or legitimate** using different ML models. Feature extraction, preprocessing, and model comparison are performed to determine the best approach.

## 📊 Algorithms Used  
The following machine learning algorithms were compared:  
- Decision Tree  
- Random Forest  
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

## 📂 Dataset  
- The dataset contains labeled phishing and legitimate URLs.  
- Features include textual, lexical, and host-based characteristics.  
- Source : Kaggle, link to the dataset - https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls

## 📊 Results  
After training and evaluating multiple machine learning models, the following results were observed:

| Model | Accuracy |
|--------|---------|
| Decision Tree | 86.7% |
| Random Forest | 91.9% |
| Logistic Regression | 85.6% |
| Support Vector Machine | 86.3% |
| K-Nearest Neighbours | 88.4% |
| Naive Bayes | 61.0% |


## ⚙️ Dependencies  
Install the required Python libraries using:  
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
