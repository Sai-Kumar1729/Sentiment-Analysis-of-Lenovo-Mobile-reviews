# 📱 Lenovo Phone Review Sentiment Analysis  
This project analyzes **Lenovo phone reviews** using **Logistic Regression** and **TF-IDF Vectorization**.  
The model predicts whether a review is **positive** or **negative**, helping in product sentiment analysis.  

## 📌 Features  
✅ **Text Preprocessing**: Stopword removal, tokenization, lemmatization  
✅ **Feature Extraction**: TF-IDF vectorizer  
✅ **Model Training**: Logistic Regression  
✅ **Performance Metrics**: Accuracy, Confusion Matrix, F1-score  
✅ **Prediction Script**: Classify new reviews  

---

## 📂 Dataset  
- The dataset consists of **Lenovo phone reviews** (scraped from online sources).  
- The **target variable**: `1 (Positive)` or `0 (Negative)`.  
- The dataset is preprocessed before training the model.


## 🛠 Project Structure
📂 Sentiment-Analysis-of-Lenovo-Mobile-reviews
├── 📜 Text_Processing.py         # Script to train the Logistic Regression model
├── 📜 Model_Building.py             # Script to predict sentiment for new reviews
├── 📜 Model_prediction.py       # Text preprocessing functions
├── 📜 Classifier.pkl  # Saved trained model
├── 📜 tfidfModel.pkl   # TF-IDF vectorizer
├── 📜 K8reviews.csv            # Raw dataset
├── 📜 Cleaned_data.csv            # Cleaned reviews dataset
└── 📜 README.md              # Project documentation (You are here!)

---


### **🔹 1️⃣ Clone the Repository**  
```sh
[git clone https://github.com/Sai-Kumar1729/Sentiment-Analysis-of-Lenovo-Mobile-reviews.git]
cd lenovo-review-analysis
