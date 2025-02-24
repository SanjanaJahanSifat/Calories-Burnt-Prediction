# Calories Burnt Predictor

## 🚀 Overview

The **Calories Burnt Predictor** is a machine learning-powered web app built using **Streamlit**. It predicts the number of calories burnt based on various physiological factors and exercise details using an **XGBoost model**.

## ✨ Features

- 🔹 **User-friendly UI** powered by Streamlit.
- 🔹 **Predicts calories burnt** based on age, gender, height, weight, heart rate, body temperature, and exercise duration.
- 🔹 **Machine Learning model** trained using XGBoost for accurate predictions.
- 🔹 **Responsive Design** for smooth user experience.

## 📦 Installation

To set up and run the app locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-repo/calories-burnt-predictor.git
cd calories-burnt-predictor

# Run the Streamlit app
streamlit run app.py
```

## 🛠 Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python, Pandas
- **Machine Learning Model:** XGBoost
- **Deployment:** Localhost / Cloud Services (Optional)

## 🎯 How to Use

1. Select your **gender**.
2. Enter your **height (cm)**, **weight (kg)**, and **age**.
3. Input your **exercise duration (min)**, **heart rate (BPM)**, and **body temperature (°C)**.
4. Click on the **Predict Probability** button to get the estimated calories burnt.

## 📁 Project Structure

```
📂 calories-burnt-predictor
│-- 📄 app.py             # Streamlit App Code
│-- 📄 model.pkl          # Pre-trained Machine Learning Model
│-- 📄 README.md          # Project Documentation
```

## 🤖 Machine Learning Model

The app uses an **XGBoost Regressor** trained on a dataset containing physiological data. Features used:

- Gender (One-Hot Encoded)
- Age
- Height (cm)
- Weight (kg)
- Exercise Duration (min)
- Heart Rate (BPM)
- Body Temperature (°C)





