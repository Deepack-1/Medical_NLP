
# 🩺 Medical NLP Pipeline

This repository contains a Medical NLP Pipeline built using Streamlit and Google Gemini AI to process physician-patient conversations and extract structured medical information. It performs:

✅ Medical NLP Summarization
✅ Sentiment & Intent Analysis
✅ SOAP Note Generation
✅ JSON Output & Download Feature







## Documentation


🚀 Features

-Upload a .txt file containing a medical conversation.

-Extract structured medical details (Symptoms, Diagnosis, Treatment, etc.).

-Perform sentiment and intent analysis on the conversation.

-Generate SOAP notes for clinical documentation.

-Display extracted data in JSON format.

-Provide download buttons for structured reports.



                                                                                                                                                                                            


## Installation
🛠️ Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/yourusername/medical-nlp-pipeline.git  
cd medical-nlp-pipeline

2️⃣ Install Dependencies

pip install streamlit google-generativeai

3️⃣ Set Up API Key

Create a .env file and add your Google Gemini API Key:

API_KEY=your_google_gemini_api_key

OR manually set it in app.py:

API_KEY = "your_google_gemini_api_key"

4️⃣ Run the Application

streamlit run app.py

## Screenshots

![App Screenshot](https://drive.google.com/uc?export=view&id=1zhD1SFkPxxUTdMudWtL240wpps8zueey)

![App Screenshot](https://drive.google.com/uc?export=view&id=1IlTpgwhKgD8n4oP4GZ_5zFi15-2okt1N)


## 🔬 Methodologies Used
✅ Medical NLP Summarization

Uses Google Gemini AI to extract key medical insights.

JSON structure includes: Symptoms, Diagnosis, Treatment, Current Status, Prognosis.

✅ Sentiment & Intent Analysis

Determines the emotion of the patient.

Detects conversation intent (e.g., medical diagnosis, follow-up inquiry).

✅ SOAP Note Generation

Extracts Subjective, Objective, Assessment, and Plan (SOAP) notes.

Converts unstructured text into structured medical documentation.
## Acknowledgements


Google Gemini AI for NLP processing.

Streamlit for the interactive web interface.

