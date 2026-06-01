# 🎬 NLP Text Processing – IMDB Sentiment Analysis  

## 📌 Executive Summary  
- This project focuses on building a sentiment analysis model using the IMDB dataset. 
- It applies **NLP preprocessing, TF-IDF vectorization, and machine learning algorithms** to classify movie reviews as positive or negative, achieving **85% accuracy**.  

---

## 💼 Business Problem  
Businesses and streaming platforms rely heavily on customer feedback. However, manually analyzing thousands of reviews is time-consuming and inefficient.  

---

## 💡 Solution  
- We developed an **automated sentiment analysis pipeline** that processes raw IMDB reviews, extracts meaningful features, and classifies them into sentiments. 
- This helps organizations **quickly track audience sentiment and improve decision-making**.  

---

## 📊 Number Impact  
- **85% accuracy** on test data  
- **10% improvement** in classification performance through feature selection and hyperparameter tuning  

---

## ⚙️ Methodology  
1. **Data Preprocessing** – Cleaning, tokenization, stopword removal, lemmatization  
2. **Feature Engineering** – TF-IDF vectorization, feature selection  
3. **Model Training** – Logistic Regression, SVM, Naive Bayes  
4. **Evaluation** – Accuracy, Precision, Recall, F1-score  

---

## 🛠️ Skills Used  
- **Python**  
- **NLTK** (tokenization, stopwords, lemmatization)  
- **Scikit-learn** (TF-IDF, ML models, evaluation)  
- **Feature selection & hyperparameter optimization**  

---

## 📈 Results & Recommendations  
- ✅ Achieved **85% accuracy** with TF-IDF + Logistic Regression  
- ✅ Recommended for **review monitoring, customer satisfaction tracking, and content insights**  
- ✅ Can be extended to **multilingual reviews** or integrated into a **real-time feedback dashboard**  

---

## 🚀 Next Steps & Limitations  
🔹 Extend to **deep learning models (LSTM, BERT)** for higher accuracy  
🔹 Build a **Streamlit dashboard** for interactive review analysis  
🔹 Handle **sarcasm and context** (current limitation of TF-IDF + ML)  
🔹 Expand dataset to include **product reviews, tweets, and global sentiment data**  

---

## 🏗️ Project Architecture  

```
├──                                      Raw IMDB Reviews/
│                                                ⬇️
├──           Text Preprocessing (Cleaning, Tokenization, Stopword Removal, Lemmatization)
│                                                ⬇️
├──                  Feature Engineering (TF-IDF Vectorization, Feature Selection)
│                                                ⬇️
├──                         Model Training (LogReg, SVM, Naive Bayes)
├──                                              ⬇️
├──                        Evaluation\n(Accuracy, Precision, Recall, F1)
├──                                              ⬇️
└──                           Final Sentiment Classifier\n(85% Accuracy)
```

---

## ⚡ How to Run  

### 1. Clone the Repository  
```bash
git clone https://github.com/Kirtikesh157/NLP-Text-Processing-IMDB-Dataset-.git
````

### 2. Install Dependencies

All required packages are listed in **requirements.txt**

```bash
pip install -r requirements.txt
```

### 3. Run the Script

```bash
python sentiment_analysis.py
```

### 4. Expected Output

* Preprocessing pipeline execution logs
* Model training and evaluation
* Final accuracy score (\~85%) printed in the console

---

## 📦 Requirements

```txt
pandas
numpy
nltk
scikit-learn
tqdm
# Optional (if using visualizations)
matplotlib
seaborn
```

---


---

## 📌 Project Objectives

- Clean and preprocess raw IMDB review text.
- Convert text to numerical representations (TF-IDF, Count Vectorizer).
- Train sentiment classification models using scikit-learn.
- Evaluate model performance with accuracy, confusion matrix, and other metrics.
- Explore the use of pipelines and parameter tuning.

---

## 🛠️ Tech Stack

| Task              | Tools & Libraries                     |
|-------------------|----------------------------------------|
| Text Processing   | `nltk`, `re`, `string`, `sklearn`     |
| Vectorization     | `CountVectorizer`, `TfidfVectorizer`  |
| Modeling          | `LogisticRegression`, `NaiveBayes`    |
| Evaluation        | `classification_report`, `confusion_matrix` |
| Data Handling     | `pandas`, `numpy`                     |
| Visualization     | `matplotlib`, `seaborn`               |
| Notebook          | `Jupyter Notebook`                    |

---

## 📂 Project Structure
```
├── data/
│ └── imdb.csv
├── notebooks/
│ └── NLP_IMDB_Processing.ipynb
├── models/
│ └── saved_models.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🧪 Features Implemented

- Text preprocessing (lowercasing, stopword removal, stemming)
- Vectorization: Bag of Words and TF-IDF
- Model training: Naive Bayes, Logistic Regression
- Evaluation: Accuracy, precision, recall, F1-score
- ML Pipeline integration using `Pipeline()` from scikit-learn

---


## 📌 Future Enhancements

- Apply deep learning models (e.g., **LSTM**, **BERT**).
- Build a web-based text sentiment classifier using **Streamlit** or **Flask**.
- Include hyperparameter tuning using **GridSearchCV**.

---

## 📬 Connect With Me

Like the project? Let’s connect\!

  * 🔗 [GitHub](https://github.com/Kirtikesh157) 
  * 💼 [LinkedIn](https://www.linkedin.com/in/kirtikesh-bhoyar-a5331a284/)


