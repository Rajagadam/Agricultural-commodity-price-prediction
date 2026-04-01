# 🌾 Agricultural Commodity Price Prediction System

## 📌 Overview

This project is a **web-based application** built using **Django** and
**Deep Learning (LSTM / BiLSTM)** to predict agricultural commodity
prices.\
It helps farmers, traders, and stakeholders make informed decisions by
forecasting future market prices based on historical data.

------------------------------------------------------------------------

## 🚀 Features

-   📊 Predict commodity prices using LSTM/BiLSTM model\
-   🌍 Location-based input (State, District, Market)\
-   🧾 User-friendly web interface (Django)\
-   📈 Historical data analysis\
-   🔍 Real-time prediction results\
-   🔐 Authentication system (Login/Register)

------------------------------------------------------------------------

## 🛠️ Tech Stack

### Backend

-   Python\
-   Django\
-   Django REST Framework

### Machine Learning

-   TensorFlow / Keras\
-   LSTM / Bidirectional LSTM

### Frontend

-   HTML, CSS, JavaScript\
-   React (if used)

### Database

-   PostgreSQL / SQLite

------------------------------------------------------------------------

## 📂 Project Structure

    Commodity/
    │── backend/
    │── frontend/
    │── dataset/
    │── model/
    │── README.md

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

``` bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create Virtual Environment

``` bash
python -m venv env
env\Scripts\activate
```

### 3️⃣ Install Dependencies

``` bash
pip install -r requirements.txt
```

### 4️⃣ Setup Database

``` bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run Server

``` bash
python manage.py runserver
```

------------------------------------------------------------------------

## 🧠 Model Details

-   Uses **LSTM / BiLSTM** for time series forecasting\
-   Inputs: Commodity, State, District, Market\
-   Output: Predicted Price

------------------------------------------------------------------------

## 📊 How It Works

1.  User selects commodity and location\
2.  Data is processed\
3.  Model predicts price\
4.  Results shown on UI

------------------------------------------------------------------------

## 🔒 Future Enhancements

-   Real-time API integration\
-   Mobile app\
-   Weather-based prediction

------------------------------------------------------------------------

## 👨‍💻 Author

**Raja Gadam**
