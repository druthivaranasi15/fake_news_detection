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
Logistic Regression model accuracy: 0.9868596881959911
naive bayes model accuracy: 0.9398663697104677
Random Forest Model accuracy: 0.9898663697104677

---

# How to Run
1. Open the Jupyter Notebook:
   ```bash```
   jupyter notebook "Fake news Detection.ipynb"

## Author
**Varanasi Druthi**  
3rd Year CSE (Data Science), IIIT Nagpur  

---

## License
This project is open-source and available for educational and research purposes.

---

## 🧾 Acknowledgements
- Inspired by open-source Human Action Recognition datasets and research papers.  
- Built using Python’s machine learning ecosystem — Scikit-learn, NumPy, Pandas, and Matplotlib.  
- Special thanks to academic mentors and dataset providers for guidance and support.
