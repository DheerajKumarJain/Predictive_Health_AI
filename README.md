# 🧠 PredictiveHealthAI – AI-Powered Disease Prediction & Symptom Chatbot

**PredictiveHealthAI** is a comprehensive AI-driven healthcare assistant that combines machine learning with an interactive HealthBot to help users predict diseases, understand symptoms, and receive health advice. Designed with accessibility and user experience in mind, it empowers users to make informed health decisions in real-time.

## 🔍 Key Features

- **🩺 Disease Prediction**
  - Predicts the likelihood of **diabetes** and **heart disease** using machine learning models trained on real medical datasets.
  - Simple and intuitive input forms with clear output and explanations.

- **🤖 HealthBot – AI Chat Assistant**
  - A custom-built AI chatbot that understands symptoms provided in natural language.
  - Responds with possible diagnoses, health tips, and follow-up suggestions.
  - Trained using a symptom-disease mapping dataset and enhanced with structured logic for accurate responses.

- **📄 Auto-Generated Health Reports**
  - Automatically creates downloadable PDF summaries for each diagnosis or chatbot interaction.
  - Provides a convenient way to store or share results with healthcare providers.

- **📂 Modular & Interactive Interface**
  - Built using **Streamlit**, featuring individual pages:
    - `Diabetes Predictor`
    - `Heart Predictor`
    - `HealthBot` (chat-based assistant)
    - `Appointment` (UI prototype for scheduling)

## ⚙️ Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **ML Models**: scikit-learn, pandas, joblib  
- **Chatbot Logic**: Rule-based NLP with symptom-condition matching  
- **PDF Generation**: ReportLab / FPDF  
- **Data Visualization**: Matplotlib / Streamlit built-in charts

## 🗂️ Project Structure

PredictiveHealthAI/
├── app.py # Main launcher
├── chatbot/ # Chatbot logic & symptom-response mapping
├── data/ # Medical datasets
├── model/ # Trained ML models (.pkl)
├── pages/ # Streamlit pages
├── report/ # PDF outputs
├── utils/ # Explanation helper scripts
├── requirements.txt # Python dependencies


## 🚀 Getting Started

1. Install dependencies:
   pip install -r requirements.txt
   
2. Launch the app:
   streamlit run app.py
