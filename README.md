# 📚 Amazon vs Flipkart Book Price Intelligence System

## 🔍 Overview
This project is an **end-to-end Machine Learning application** that predicts the **optimal market price of books** and identifies the **cheaper platform (Amazon or Flipkart)**.  

It also provides **pricing analytics, competitor comparison, and historical price simulation** through an interactive **Streamlit web application**.

The system is **containerized using Docker** and is ready for **cloud deployment**.

---

## 🚀 Key Features
- 💰 **Price Prediction (Regression)** – Predicts optimal market price  
- 🏪 **Cheaper Platform Prediction (Classification)** – Amazon vs Flipkart  
- 📊 **Price Comparison Analytics**  
- 📈 **Trust Score Analysis (Ratings × Reviews)**  
- 📉 **Price Gap Analysis**  
- 📈 **Historical Price Simulation**  
- 🌐 **Interactive Streamlit Dashboard**  
- 🐳 **Dockerized for Deployment**

---

## 🧠 Machine Learning Pipeline

### 1️⃣ Data Collection
- Amazon book dataset  
- Flipkart book dataset  

### 2️⃣ Data Cleaning & Preprocessing

### 3️⃣ Exploratory Data Analysis (EDA)

### 4️⃣ Feature Engineering
- Price difference  
- Trust score  
- Review impact  
- Price ratios  

### 5️⃣ Model Training
- **Regression:** Random Forest Regressor  
- **Classification:** Random Forest Classifier  

### 6️⃣ Hyperparameter Tuning
- GridSearchCV  

### 7️⃣ Model Evaluation

### 8️⃣ Deployment
- Streamlit  
- Docker  

---

## 🗂️ Project Structure

ecommerce-price-predictor/
│
├── app.py
├── Dockerfile
├── .dockerignore
├── requirements.txt
│
├── data/
│ └── merged_cleaned_books.csv
│
├── model/
│ ├── best_price_prediction_model.pkl
│ ├── best_platform_classifier.pkl
│ └── label_encoder.pkl
│
├── notebooks/
│ ├── 01_eda.ipynb
│ └── 02_model_training.ipynb
│
└── README.md

---

## 📊 Feature Engineering Highlights
- **Price Difference:** Amazon price − Flipkart price  
- **Absolute Price Gap**  
- **Price Ratio**  
- **Trust Score:** Rating × Reviews  
- **Title Length (Text Feature)**  

These features help capture **competitive pricing behavior**.

---

## 🤖 Models Used

### 🔹 Regression (Price Prediction)
- Linear Regression (baseline)  
- **Random Forest Regressor (best)**  

### 🔹 Classification (Cheaper Platform)
- Logistic Regression  
- **Random Forest Classifier (best)**  

---

## 📈 Streamlit Web App
The Streamlit app provides:
- Real-time price prediction  
- Platform recommendation  
- Visual analytics  
- Historical price trend simulation  
- Business-friendly insights  

---

## ▶️ Run Locally

```bash
streamlit run app.py
