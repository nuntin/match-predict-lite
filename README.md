# match-predict-lite

> ⚽ Lightweight ML-powered football match analyzer built with Streamlit.  
> Predict match advantage between two teams using historical stats — no betting involved.

---

## 🧠 Overview
`match-predict-lite` is a lightweight, ready-to-use web app for analyzing the statistical advantage between two football teams.
Built with **Streamlit** and trained on historical match data using **scikit-learn**, this tool is designed for:

- Football enthusiasts curious about match outcomes
- Data science learners building ML intuition
- Developers seeking deployable ML + Web examples

**No betting features. No odds. Just pure prediction.**

---

## 🔍 Features

- 🧮 Predicts win/draw/loss likelihood from historical match stats
- 📊 Simple logistic regression model — easily extendable
- 🌐 Clean Streamlit UI — enter 2 team names and get insights
- 📁 Exportable predictions as CSV

---

## 📦 Folder Structure

```
match-predict-lite/
├── dataset/               # Sample match data (CSV)
├── model/
│   └── train_model.ipynb  # Jupyter Notebook for training
├── app/
│   └── streamlit_app.py   # Web UI using Streamlit
├── output/                # Predictions CSV output
└── README.md
```

---

## 🚀 Getting Started

### 🔧 1. Clone the repo
```bash
git clone https://github.com/Nuntin/match-predict-lite.git
cd match-predict-lite
```

### 📦 2. Install dependencies
```bash
pip install -r requirements.txt
```

### ▶️ 3. Run the app
```bash
streamlit run app/streamlit_app.py
```

---

## 📚 Tech Stack
- Python 3.8+
- scikit-learn
- pandas
- Streamlit

---

## 🔐 Legal & Ethical Use
This project is for **educational and analytical** use only.  
It **does not promote or support gambling** in any form.

You are free to clone, modify, and deploy for non-betting purposes under MIT License.

---

## 📩 Contact
Made by Nuntin Padmadin
GitHub: https://github.com/Nuntin  
Email: nuntin.p@gmail.com  
Open to feedback, contributions, or integration ideas — pull requests welcome!
