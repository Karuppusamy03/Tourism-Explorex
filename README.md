
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

## 🧩 Modules Overview

| Module                        | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| **User Management**           | Handles user registration, login, profile management, and user history.     |
| **Recommendation Engine**     | Uses AI and machine learning to suggest personalized locations and experiences based on user preferences and behavior. |
| **Navigation Module**         | Provides real-time location tracking, interactive maps, and route directions. |
| **Expense Predictor**         | Estimates the travel cost dynamically using machine learning models based on destination, distance, and duration. |
| **Chatbot & Voice Assistant** | Offers real-time travel support, app navigation help, and general queries via chat and voice commands. |
| **Weather & Location API Integration** | Fetches real-time weather forecasts and geolocation details using Google Maps and OpenWeatherMap APIs. |
"""

# 🧠 How It Works

Tourism Explorex combines powerful machine learning, real-time APIs, and user-friendly design to provide a seamless and intelligent travel planning experience.

The platform follows a multi-layered approach to serve personalized, efficient, and interactive travel assistance.

---

### 🔍 Step 1: User Interaction

- Users register or log in using email or social media accounts.
- The system collects travel preferences, search history, and bookmarked places.
- Users interact with the system via:
  - Chatbot (text-based assistant)
  - Voice assistant (hands-free commands)
  - Map-based search interface

---

### 📊 Step 2: Data Collection & Preprocessing

- Gathers data from:
  - User inputs and behavior
  - External APIs (Google Maps, OpenWeatherMap)
  - Historical data and travel logs
- Cleans and transforms data for ML models
  - Normalization, encoding, filtering, etc.

---

### 🤖 Step 3: ML Model Predictions

- **Gradient Boosting** and **Random Forest** models predict:
  - Estimated travel expenses based on user profile, location, and date
  - User satisfaction scores and feedback trends
- **Support Vector Machine (SVM)** is used for:
  - Classifying user preferences
  - Refining recommendations

---

### 📍 Step 4: Real-Time Recommendations

- Location engine suggests nearby places like:
  - Hotels
  - Restaurants
  - Tourist attractions
- Recommendations are tailored to user interests using clustering and filtering techniques.

---

### ☁️ Step 5: Context Awareness

- Weather forecast module fetches up-to-date weather details to:
  - Recommend indoor or outdoor plans
  - Adjust travel timelines

- Real-time navigation helps users with:
  - Route planning
  - Live traffic updates
  - Nearby amenities (ATM, food, medical)

---

### 💬 Step 6: Interactive Support

- Chatbot and voice assistant answer queries like:
  - "Show me top-rated places near me"
  - "How much will my trip cost?"
  - "Bookmarked places"
- Multilingual support planned for future versions

---

### ✅ Output

- Personalized dashboard
- Visual travel plans
- Estimated expenses
- Review collection
- Real-time alerts and suggestions

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
