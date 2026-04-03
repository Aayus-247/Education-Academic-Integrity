# 🚀 AI vs Human Text Classifier

A Machine Learning project that classifies whether a given text is **AI-generated 🤖 or Human-written 🧑** using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

With the rapid growth of AI-generated content, it has become important to distinguish between human-written and machine-generated text.  

This project builds a **text classification pipeline** using traditional ML algorithms and TF-IDF vectorization to detect AI-generated content with high accuracy.

---

## ⚙️ Features

- 📂 Upload and extract dataset (ZIP support)
- 🧹 Text preprocessing (cleaning, normalization)
- 🔠 TF-IDF vectorization
- 🤖 Multiple ML models:
  - Logistic Regression
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)
- 📊 Model comparison & evaluation
- 📉 Confusion Matrix & ROC Curve visualization
- ☁️ WordCloud visualization
- 💾 Model saving using Joblib
- 🔮 Real-time prediction function

---

## 📁 Project Structure

```
├── dataset/
│   └── your_dataset_5000.csv
├── model/
│   ├── text_classifier_5000.joblib
│   └── vectorizer.joblib
├── main.ipynb
└── README.md
```

---

## 📊 Dataset

- Contains text samples labeled as:
  - `0` → Human-written 🧑  
  - `1` → AI-generated 🤖  
- Sample size: ~5000 entries (sampled to 500 during training)

---

## 🧠 Model Pipeline

1. Data Loading
2. Preprocessing
3. Feature Extraction (TF-IDF)
4. Train-Test Split
5. Model Training
6. Evaluation
7. Model Saving

---

## 📈 Model Performance

- Accuracy achieved: **~80%+**
- Best Model: **Logistic Regression**

---

## 💻 Installation & Setup

### 1️⃣ Clone Repository
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install Dependencies
```
pip install pandas scikit-learn matplotlib wordcloud joblib
```

### 3️⃣ Run Notebook
```
jupyter notebook main.ipynb
```

---

## 👨‍💻 Author

**Aayus (Fear Less Devil)**  
GitHub: https://github.com/Aayus-247  

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
