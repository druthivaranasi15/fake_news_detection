# Fake News Detection

This project detects fake news articles using Natural Language Processing (NLP) and Machine Learning techniques.

##  Features
- Text preprocessing (tokenization, stopword removal, stemming)
- TF-IDF vectorization
- Machine learning classifiers (Logistic Regression, Random Forest, etc.)
- Model evaluation using accuracy, precision, recall, and F1-score

##  Files
- `Fake news Detection.ipynb` → Main notebook with full code
- `README.md` → Project documentation

##  Requirements
Install dependencies:
```bash```
pip install numpy pandas scikit-learn nltk

#  Dataset
You can use the [Fake News Dataset from Kaggle](https://www.kaggle.com/c/fake-news/data).

It includes:
- **title** — headline of the article  
- **text** — full content of the article  
- **label** — 0 for real news, 1 for fake news  

Make sure to download and place the dataset in your project directory before running the notebook.

---

#  Model Summary
The model processes and analyzes text data to classify news articles as **Real** or **Fake**.  
Different ML algorithms were trained and compared based on performance metrics such as:
- Accuracy  
- Precision  
- Recall  
- F1-score  

The goal is to identify which model performs best for fake news detection.

---

# Results
The best-performing model achieved high accuracy in distinguishing fake and real news.  
You can visualize results through confusion matrices and performance graphs within the notebook.

---

# How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Fake news Detection.ipynb"
