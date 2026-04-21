# spam-email-classifier
ML model to detect spam emails using Naive Bayes and TF-IDF | Python, scikit-learn.
# 📧 Spam Email Classifier

A machine learning project that automatically detects whether an email/SMS is **spam or legitimate (ham)** using Natural Language Processing and Naive Bayes algorithm.

---

## 🎯 Objective

To build a classification model that can accurately identify spam messages, helping users filter unwanted and potentially harmful emails.

---

## 🛠️ Tools & Technologies

| Category | Tools Used |
|----------|-----------|
| Language | Python 3 |
| ML Library | scikit-learn |
| Data Handling | Pandas |
| Visualization | Matplotlib |
| Algorithm | Multinomial Naive Bayes |
| Feature Extraction | TF-IDF Vectorizer |

---

## 📊 Dataset

- **Name:** SMS Spam Collection Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Size:** 5,572 messages (4,825 ham + 747 spam)

---

## ⚙️ How It Works

1. Load and clean the dataset
2. Convert text to numbers using **TF-IDF** (Term Frequency - Inverse Document Frequency)
3. Split data into 80% training and 20% testing
4. Train a **Naive Bayes** classifier
5. Evaluate using accuracy, precision, recall
6. Predict on new custom messages

---

## 📈 Results

- **Accuracy:** 95%+
- **Algorithm:** Multinomial Naive Bayes
- Confusion matrix and prediction charts generated automatically

---

## 🚀 How to Run

**Step 1: Install dependencies**
```bash
pip install pandas scikit-learn matplotlib
```

**Step 2: Download the dataset**
- Go to [Kaggle SMS Spam Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Download `spam.csv` and place it in the same folder as the script

**Step 3: Run the project**
```bash
python project1_spam_classifier.py
```

---

## 📁 Project Structure
