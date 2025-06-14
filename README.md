AnnDoot AI: Plant Disease Detection, Crop & Fertilizer Recommendation
Overview
AnnDoot AI is an integrated, AI-powered web application designed to empower farmers with instant, reliable plant disease detection, crop recommendation, and fertilizer guidance. Built with Python, TensorFlow, Streamlit, and Flask, the platform leverages deep learning and machine learning to deliver actionable insights for smarter, more sustainable agriculture.

Features
Plant Disease Detection

Upload or capture a plant leaf image to detect diseases using a trained CNN (MobileNetV2/InceptionV3).

Supports 14+ crops and 38+ disease/health classes.

Provides actionable, multilingual treatment advice (chemical & organic), tailored to detected disease and environmental factors.

Visual explanations of predictions using LIME for transparency.

Crop Recommendation

Input soil nutrients (N, P, K), pH, temperature, humidity, and rainfall.

ML model suggests the most suitable crop for your local conditions.

Recommendations are personalized and available in multiple Indian languages.

Fertilizer Recommendation

Enter soil nutrient levels and select crop.

System recommends the optimal fertilizer type and dosage using a Random Forest classifier.

Output is mapped to local crop names and supports multilingual display.

User-Friendly Interface

Intuitive web app with support for voice commands and real-time translation.

Responsive design, accessible to users with varying technical backgrounds.

Getting Started
Clone the repository

bash
git clone https://github.com/your-username/AnnDoot-AI.git
cd AnnDoot-AI
Install dependencies

bash
pip install -r requirements.txt
Download/Place Model Files

Place trained model files (trained_model.h5, fert_model_simple.pkl, etc.) in the project directory.

Run the Application

bash
streamlit run app2.py
