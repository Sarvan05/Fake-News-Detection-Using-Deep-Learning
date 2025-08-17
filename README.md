# Fake News Detection Using Deep Learning

This project implements a **Fake News Detection system** using Deep Learning (BiLSTM + GloVe embeddings). The model classifies news articles as **FAKE** or **REAL** based on their textual content. It uses the Fake and Real News Dataset and applies text preprocessing, word embeddings, and LSTM-based neural networks to achieve high accuracy.

---

## 🚀 Features
- Preprocessing of text data (cleaning, tokenization, padding)  
- Word embeddings using **GloVe** (Global Vectors for Word Representation)  
- **Bidirectional LSTM** model for sequence learning  
- Achieves ~87% accuracy on test data  
- Can predict labels for new/unseen news articles  

---

## 🛠️ Tech Stack
- **Python**  
- **TensorFlow / Keras**  
- **NumPy**, **Pandas**  
- **Matplotlib**, **Seaborn** (for visualization)  
- **Scikit-learn**  

---

## 📊 Model Performance
- **Test Accuracy:** ~86.6%  
- **Precision, Recall, F1-score:** ~0.87 (balanced for both FAKE & REAL classes)  

---

## ▶️ How to Use

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/Fake-News-Detection-Using-Deep-Learning.git
cd Fake-News-Detection-Using-Deep-Learning

```
Step 2: 

Open the notebook (FakeNewsDetection.ipynb) in Jupyter/Colab.

Run the cells to preprocess, train, and test the model.

Step 3:
```
from tensorflow.keras.models import load_model
model = load_model("fake_news_model.h5")
```
