
# 🌍 Tourism Explorex: ML-Powered Travel Companion

**Smart Travel: ML-Powered Predictive Travel Expense with Real-Time Assistance and Data Processing**

Tourism Explorex is an intelligent travel companion web application that enhances user travel experiences by offering personalized location recommendations, real-time navigation, voice and chatbot assistance, weather updates, and predictive travel expense estimation using Machine Learning.

---

## 📌 Features

- 🔐 Secure user authentication (Email & Social login)
- 🗺️ Interactive map for nearby places
- 💬 Real-time chatbot assistant
- 🧭 Voice assistant for hands-free navigation
- ☁️ Weather forecasts for travel planning
- 💸 ML-based travel expense prediction
- ⭐ Personalized recommendations (AI-driven)
- 📍 Bookmark favorite locations
- 📊 Feedback and ratings system
- 📤 Social media sharing
- 🔍 Filter and sorting by price, rating, distance

---

## 🚀 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**: Scikit-learn (Gradient Boosting, SVM, Random Forest)
- **Database**: SQLite / Firebase
- **APIs Used**:
  - Google Maps API
  - OpenWeatherMap API
- **Hosting/Deployment**: [Include your platform if hosted]

---

## 📷 Screenshots

| Feature              | Screenshot Preview |
|----------------------|--------------------|
| Home Page            | `assets/screenshots/homepage.png` |
| Login / Register     | `assets/screenshots/login.png` |
| Map Navigation       | `assets/screenshots/maps.png` |
| Expense Prediction   | `assets/screenshots/predict.png` |
| Chatbot Assistant    | `assets/screenshots/chatbot.png` |

---

## 📁 Installation Guide

1. Clone the repository:
   ```bash
   git clone https://github.com/Karuppusamy03/Tourism-Explorex.git
   cd Tourism-Explorex

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
3. set up API keys:
   - Google Maps API
   - OpenWeatherMap API
  Store them in a .env file or config file:
   ```bash
   GOOGLE_API_KEY=your_key_here
    WEATHER_API_KEY=your_key_here
4. Run the application:
   ```bash
   python app.py


## 📊 Machine Learning Models

- **Gradient Boosting**: For high-accuracy cost prediction.
- **Random Forest**:  Robust to overfitting, handles classification.
- **Support Vector Machine (SVM)**: Optimal classification boundaries.

## 🧪 Testing

- Unit testing with pytest
- Integration tests for APIs and model interaction
- Real-time test reports available in /tests/reports/

## 🔮 Future Enhancements

- Local language and voice recognition
- Smart itinerary planning
- Enhanced sentiment analysis for reviews
