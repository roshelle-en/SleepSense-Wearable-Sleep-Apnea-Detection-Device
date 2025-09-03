# SleepSense-Wearable-Sleep-Apnea-Detection-Device
📌 Overview

SleepSense is an affordable, compact, and easy-to-use wearable device designed to detect sleep apnea in real time. Unlike expensive commercial wearables such as FitBit or Apple Watch, SleepSense provides smart classification, early detection, and instant feedback at a fraction of the cost. With seamless mobile app integration, it empowers users to monitor their sleep health and take preventive action.

⚙️ Functionality

SpO₂ Monitoring: PPG sensor continuously tracks blood oxygen levels.

Motion Detection: IMU identifies unusual sleep positions and apnea-related movements.

Instant Feedback: Vibration motor gently alerts the user to change sleeping posture when apnea is detected.

Data Processing: ESP32 microcontroller transmits data wirelessly to the mobile app.

Mobile App: Displays real-time SpO₂ levels, apnea events, and generates personalized sleep scores (0–100).

🧠 Machine Learning Model

Developed using the MESA Sleep Dataset (NIH, USA).

Dataset: 2,000+ patient records with 500+ features.

Trained model achieves:

F1 Score: 0.9125

AUC-ROC Score: 0.9622

Classifies sleep apnea risk based on oxygen levels, BMI, and sleep efficiency.

🚀 Why SleepSense Stands Out

Affordable: Target cost of LKR 5,000 (much cheaper than premium wearables).

Compact Design: Simple clip-on form factor for comfort.

Ease of Use: Automatic logging with mobile app alerts.

Early Detection: Flags apnea at an early stage using combined SpO₂ + motion analysis.

App Integration: Tracks trends, offers insights, and provides lifestyle tips for better sleep.

🌍 Market Relevance

The global sleep apnea devices market is projected to grow from $7.94B (2024) to $11.72B (2029) at a CAGR of 8.6%. SleepSense addresses this rising global concern with an affordable and accessible solution, especially suitable for developing countries.

📱 Mobile App Features

User Login & Profile Management

Real-time SpO₂ and Sleep Graphs

Daily/Weekly Sleep Reports

Sleep Score (0–100) for quick health overview

Alerts & Recommendations

🔧 Tech Stack

Hardware: ESP32, PPG Sensor, IMU, Vibration Motor

Software: Arduino Framework, Python (ML), Flutter/React Native (App)

Machine Learning: Sleep Apnea Classification Model (Python, Scikit-learn)

Dataset: MESA Sleep Dataset (NIH)

📊 Prototype Results

Achieved high accuracy in detecting sleep apnea events.

Demonstrated reliable real-time feedback through vibrations.

Mobile app successfully provides visualized trends and sleep scoring.
