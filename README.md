# SMS/Email Spam Classifier

A machine learning project to classify SMS or email messages as **Spam** or **Not Spam**.  
Built using **Python**, **Scikit-learn**, and **Streamlit** for real-time web app deployment.

---

## 📂 Project Structure

```
SMS-Spam-Detection/
│
├── app.py                  # Streamlit application
├── models/
│   ├── model.pkl           # Trained ML model
│   └── vectorizer.pkl      # TF-IDF vectorizer
├── notebooks/
│   └── SMS_Spam_Detection_Workflow.ipynb
├── data/
│   └── spam.csv            # Original dataset
├── requirements.txt        # Python dependencies
└── README.md
```



---

## 🛠 Technologies & Libraries

- Python 3.14.3
- Pandas, Numpy  
- Scikit-learn (TF-IDF + Naive Bayes)  
- NLTK (for text preprocessing)  
- Streamlit (web app deployment)

---

## ⚙️ Features

- Text preprocessing: tokenization, stopword removal, stemming  
- Vectorization using **TF-IDF**  
- Machine learning classification using **Multinomial Naive Bayes**  
- Interactive Streamlit web app for real-time prediction  
- Shows **Spam / Not Spam** result with optional probability display

---

## 🚀 How to Run Locally

1. Clone the repo:

```bash
git clone https://github.com/rishavkumarseth2507/SMS-Spam-Detection.git
cd SMS-Spam-Detection


Install dependencies:
pip install -r requirements.txt


Run Streamlit app:
python -m streamlit run app.py


📝 Author
Rishav Kumar – Python & ML Enthusiast
