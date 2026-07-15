# Ai_Diseases_Prediction
AI-Powered Medical Chatbot for Symptom Analysis and Disease Prediction using Machine Learning and NLP. The system analyzes user symptoms, predicts possible diseases, provides medical recommendations, suggests nearby hospitals and doctors, and supports appointment booking through an intelligent healthcare assistant.

🏥 AI-Powered Medical Chatbot for Symptom Analysis and Disease Prediction

An AI-powered Medical Chatbot that leverages Machine Learning (ML) and Natural Language Processing (NLP) to analyze user symptoms and predict possible diseases. The system provides preliminary healthcare guidance, recommends medicines, suggests nearby hospitals and doctors, and supports appointment booking. It is designed to improve healthcare accessibility by offering intelligent, fast, and user-friendly medical assistance before consulting a healthcare professional.

📌 Table of Contents
Overview
Features
System Architecture
Technologies Used
Machine Learning Algorithms
Project Modules
Installation
Usage
Project Structure
Future Enhancements
License
Author
📖 Overview

Healthcare services are often limited by long waiting times, high consultation costs, and lack of immediate medical guidance. This project addresses these challenges by developing an intelligent chatbot capable of understanding user symptoms, predicting possible diseases, and providing basic healthcare recommendations using Machine Learning and NLP techniques.

The chatbot serves as a preliminary healthcare assistant and is not intended to replace professional medical diagnosis.

✨ Features
🤖 AI-powered medical chatbot
🩺 Symptom-based disease prediction
🧠 Natural Language Processing (NLP)
💊 Drug recommendation
📝 Medical precautions and health advice
🏥 Hospital recommendation
👨‍⚕️ Doctor recommendation
📅 Doctor appointment booking
🌍 Multi-language support
📍 Google Maps integration
📊 Machine Learning-based disease classification
🏗️ System Architecture

The system consists of the following layers:

User Interface Layer
Symptom Input
Chatbot Interaction
Disease Prediction
Drug Recommendation
Hospital Recommendation
Doctor Recommendation
Appointment Booking
Application Logic Layer
Input Validation
Feature Processing
Recommendation Engine
Translation Handler
Machine Learning Layer
Disease Prediction Model
NLP Model
Drug Recommendation Model
Data Layer
Symptom Dataset
Medicine Dataset
Disease-Cure Dataset
External Services
Google Maps API
Google Translate API
🛠️ Technologies Used
Programming Languages
Python
HTML5
CSS3
JavaScript
Frameworks
Flask
Machine Learning
Scikit-learn
XGBoost
Pandas
NumPy
Frontend
Bootstrap
HTML
CSS
JavaScript
APIs
Google Maps API
Google Translate API
🤖 Machine Learning Algorithms
Logistic Regression
Random Forest Classifier
XGBoost
Natural Language Processing (NLP)
📂 Project Modules
1. User Interface Module
Interactive chatbot
Symptom input
Disease prediction
2. Symptom Processing Module
Input cleaning
Feature extraction
Symptom validation
3. Disease Prediction Module
ML model prediction
Confidence score generation
4. Medical Recommendation Module
Medicine suggestions
Precautions
Lifestyle advice
5. Chatbot Module
Interactive conversation
NLP processing
6. Hospital Recommendation Module
Nearby hospitals
Google Maps integration
7. Doctor Recommendation Module
Specialist recommendation
Doctor details
8. Appointment Module
Doctor appointment booking
Slot scheduling
9. Data Management Module
Medical datasets
Symptom database
Medicine database
📊 Workflow
User
   │
   ▼
Enter Symptoms
   │
   ▼
NLP Processing
   │
   ▼
Feature Extraction
   │
   ▼
Machine Learning Model
(Logistic Regression / Random Forest / XGBoost)
   │
   ▼
Disease Prediction
   │
   ├────────► Drug Recommendation
   │
   ├────────► Medical Advice
   │
   ├────────► Hospital Recommendation
   │
   ├────────► Doctor Recommendation
   │
   ▼
Appointment Booking
🚀 Installation
Clone Repository
git clone https://github.com/yourusername/AI-Powered-Medical-Chatbot.git
Move into Project
cd AI-Powered-Medical-Chatbot
Install Dependencies
pip install -r requirements.txt
Run the Application
python app.py

Open your browser:

http://127.0.0.1:5000
💻 Usage
Launch the application.
Enter symptoms in the chatbot.
The chatbot analyzes the symptoms using NLP.
ML models predict the most probable disease.
The chatbot displays:
Disease prediction
Confidence score
Medical precautions
Medicine recommendation
Doctor recommendation
Nearby hospitals
Book an appointment if required.
📁 Project Structure
AI-Powered-Medical-Chatbot/
│
├── dataset/
├── models/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│
├── app.py
├── train_model.py
├── prediction.py
├── chatbot.py
├── requirements.txt
├── README.md
└── LICENSE
