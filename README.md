# Fake News Detection with NLP and Deep Learning

This project builds and compares traditional and deep learning models to detect **fake political news** using short-form statements from the **LIAR dataset**. It evaluates classical ML, BiLSTM, Capsule Networks, and BERT, reframing a 6-class problem into binary classification for higher performance and interpretability.

---

## 📌 Objectives
- Detect whether a political statement is **real or fake**
- Compare traditional ML vs deep learning (BiLSTM, CapsuleNet, BERT)
- Explore the impact of binary vs multiclass classification
- Apply tokenisation, lemmatisation, TF-IDF, GloVe, and Transformers

---

## Models Tested

| Model                | F1 Score (Binary) |
|---------------------|------------------|
| Logistic Regression | 0.63             |
| SVM                 | 0.62             |
| Random Forest       | 0.63             |
| Hybrid RF+SVM       | 0.63             |
| BiLSTM              | 0.62             |
| Capsule Network     | 0.59             |
| **BERT (tuned)**    | **0.62**, recall for fake = **0.76**

---

## 📁 Folder Structure
- `notebooks/`: Final model training notebook
- `reports/`: Full write-up with data analysis, model evaluation, and discussion

---

## 🛠️ Tools Used
Python, Scikit-learn, TensorFlow, Keras, HuggingFace Transformers, NLTK, Matplotlib, Pandas

---

## 📂 Dataset
[LIAR dataset by Wang (2017)](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip) – 12,836 manually fact-checked political statements.

---

## 👤 Author
**Pascal Ugonna Akano**  
MSc AI & Data Science  
University of Hull

