# 🏠 Bangalore Home Price Predictor

A machine learning web application that predicts home prices in Bangalore based on user inputs like location, square footage, number of bedrooms (BHK), and bathrooms.

![App Screenshot](https://images.unsplash.com/photo-1564013799919-ab600027ffc6?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80)

---

## 🚀 Features

- Interactive UI using **HTML**, **Bootstrap**, and **JavaScript**
- **Flask API** backend connected to a **Machine Learning model**
- Real-time prediction of property prices
- Location dropdown loaded dynamically from the backend

---

## 📁 Project Structure

bangalore-home-price-predictor/
│
├── artifacts/ # Pickled model and column files
├── app.py # Flask backend app
├── util.py # Utility: model loading & prediction
├── index.html # Frontend HTML + JS
├── requirements.txt # Python dependencies
└── README.md # This file

## 🔧 Setup Instructions

### 1. Clone this repo

```bash
git clone https://github.com/Gokulrajm2654/bangalore-home-price-predictor.git
cd bangalore-home-price-predictor

### 2. Install Python dependencies
pip install -r requirements.txt

### 3. Run the backend server
python server.py

### 4. Open the UI
Just open index.html in your browser, or serve it via Flask templates.

