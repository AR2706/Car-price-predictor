# 🚗 Car Price Prediction System

An end-to-end Machine Learning web application that predicts the resale price of a car based on its specifications, features, and history. The system trains a Random Forest Regressor model on historical automotive data and serves real-time predictions via a production-ready Flask interface deployed in the cloud.

---

## 👤 Developer Profile
* **Name:** Aritra Pradhan
* **Registration Number:** 23BCE11127
* **Course:** B.Tech Computer Science and Engineering

---

## 🔗 Project Links
* **Live Web Application:** [https://car-price-prediction-app-00au.onrender.com](https://car-price-prediction-app-00au.onrender.com)
* **GitHub Repository:** [https://github.com/AkshatGarg2005/car-price-prediction-app](https://github.com/AkshatGarg2005/car-price-prediction-app)

---

## 🛠️ Tech Stack & Ecosystem
* **Core Language:** Python 3.10
* **Machine Learning & Data Processing:** Scikit-learn, Pandas, NumPy
* **Backend Web Framework:** Flask
* **Production Web Server:** Gunicorn (WSGI)
* **Model Serialization:** Pickle
* **Cloud Platform:** Render (Virginia Region Gateway)

---

## 📂 Production Directory Architecture
The repository is engineered according to institutional production guidelines, strictly separating static client UI assets from data matrix operations:

```text
📁 car-price-prediction-app/
│
├── 📁 static/
│   └── 📄 style.css            # Custom forest green user interface theme
│
├── 📁 templates/
│   └── 📄 index.html           # Core frontend interactive web form
│
├── 📄 app.py                   # Production Flask application engine
├── 📄 train.py                 # Automated pipeline download & ML model trainer
├── 📄 car_price_model.pkl      # Serialized Random Forest Regressor binary
├── 📄 requirements.txt         # Plaintext manifest mapping core dependencies
├── 📄 Procfile                 # Production WSGI process container config
└── 📄 .gitignore               # Excludes runtime caches and heavy dataset packages
