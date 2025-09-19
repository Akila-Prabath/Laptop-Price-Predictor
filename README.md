# 💻 Laptop Price Predictor  

A machine learning web app that predicts the price of a laptop based on its specifications.
Built with Flask, trained with scikit-learn, and deployed on Heroku.
- 🌐 **Live App**: [Laptop Price Predictor on Heroku](https://laptoppricepredictor-5075a8b5b0b6.herokuapp.com/) 

---

## 🚀 Features  
- ✅ Cleaned & preprocessed dataset  
- 📊 Trained ML model with scikit-learn  
- 💻 Flask web app with user inputs  
- 🚀 Deployed on Heroku with Gunicorn  

---

## 🛠️ Tech Stack  
- 📦 Python (Flask, scikit-learn, pandas, numpy)  
- 🎨 HTML, CSS (frontend templates)  
- ☁️ Heroku (deployment)  
- 📊 Jupyter Notebook (experiments & training)  

---

## 📂 Project Structure  

```bash
LAPTOP-PRICE-PREDICTOR/
│── app/                    # 💻 Flask web application
│   ├── model/              # 🔧 (optional: custom Python model logic)
│   ├── static/             # 🎨 CSS, JS, images
│   ├── templates/          # 🖼️ HTML templates (Jinja2)
│   ├── .python-version     # ⚙️ Python version for Heroku
│   ├── app.py              # 🚀 Flask app entry point
│   ├── Procfile            # 📜 Heroku process definition
│   └── requirements.txt    # 📦 Production dependencies
│
│── data/                   # 📊 Dataset storage
│   ├── raw/                # 📂 Raw datasets
│   └── processed/          # ✅ Preprocessed datasets
│
│── models/                 # 🤖 Stored ML models
│   └── laptop_model_v1.pkl # 💾 Pre-trained model
│
│── notebooks/              # 📒 Jupyter notebooks
│   ├── data_preprocess.ipynb # 🔧 Data preprocessing
│   └── model_train.ipynb     # 🤖 Model training
│
│── env/                    # ⚙️ Virtual environment (ignored in Git)
│
│── .gitignore              # 🙈 Ignore unnecessary files
│── pyproject.toml          # 📜 Python project metadata
│── README.md               # 📘 Project documentation
│── requirements.txt        # 📦 Dependencies
```

---

## ⚙️ Setup & Installation

1️⃣ Clone the repo
```bash
git clone https://github.com/Akila-Prabath/Laptop-Price-Predictor.git
cd Laptop-Price-Predictor
```
2️⃣ Create a virtual environment
```bash
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
```
3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
4️⃣ Run locally
```bash
cd app
python app.py
```
- App will be available at: http://127.0.0.1:5000/
  
---

## 🚀 Deployment on Heroku

1️⃣ Login
```bash
heroku login
```
2️⃣ Create Heroku app
```bash
heroku create laptop-price-predictor
```
3️⃣ Push to Heroku
```bash
git push heroku master
```
4️⃣ Open the app
```bash
heroku open
```

---

## 📸 Screenshots

<img width="1920" height="886" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/64d8d764-17d4-4028-a955-7bc6b2938ebb" />

---

## 👨‍💻 Author
Akila Prabath
- 🎓 Software Engineering Student
- 🌱 Exploring Machine Learning & Web Development

---
