## Clinical Assistant  
**AI-Driven Personalized Health Assistant with Context-Aware Responses and Multilingual Voice Interaction**

### Overview

This project presents a lightweight, voice-enabled clinical assistant designed to deliver personalized health information using structured patient data. It integrates a compact language model (TinyLLaMA) with voice input/output, multilingual support, and patient-specific context injection. The assistant operates entirely on local machines, eliminating reliance on cloud services or high-end computing infrastructure.

Developed as part of the SAT5144 – Artificial Intelligence in Healthcare course at Michigan Technological University.


### Key Objectives

- Provide a natural, conversational interface for patients to inquire about their health status  
- Leverage structured patient data for generating context-aware, personalized responses  
- Support multilingual voice interaction (English, Hindi, Spanish)  
- Ensure usability in low-resource settings by running on CPU-based systems  
- Demonstrate real-time performance using a lightweight LLM (TinyLLaMA)


### Core Features

- **Voice Recognition:** Accepts natural language questions through microphone input  
- **Data Context Injection:** Retrieves relevant health records based on patient ID  
- **Language Model Response:** Uses TinyLLaMA to generate human-like, personalized replies  
- **Text-to-Speech:** Converts AI-generated responses into audio using gTTS  
- **Multilingual Output:** Adapts responses to the user’s preferred language


### Dataset Description

The assistant interacts with a series of simulated patient datasets, which emulate real-world clinical records:

- **Patient Profiles:** Name, age, gender, date of birth, preferred language, reading level  
- **Lab Results:** Glucose, BNP, hemoglobin, creatinine values and medical interpretations  
- **Vital Signs:** Weight, blood pressure, heart rate, daily steps, sleep quality  
- **Mental Health:** Mood tracking, stress level, depression scores  
- **Diet & Allergies:** Food/drug allergies, intolerances, restricted diet preferences  
- **Clinical Encounters:** Diagnoses, medication lists, care plans, admission/discharge dates

Each dataset is linked via a unique patient ID to support dynamic personalization.


### Model & Technology Stack

- **Language Model:** `TinyLLaMA-1.1B-Chat-v1.0` (from Hugging Face)  
- **Libraries & Frameworks:**  
  - Transformers (Hugging Face)  
  - Pandas, NumPy, Tempfile  
  - `speech_recognition`, `gTTS`, `pygame`  
  - `langdetect`, `googletrans`  
- **Environment:** Python 3.x, Jupyter Notebook  
- **Hardware:** Optimized to run on systems with 8GB RAM


### Getting Started

#### Clone the Repository
```bash
git clone https://github.com/Yaswanth1702/clinical-assistant.git
cd clinical-voice-assistant
```

#### Launch the Assistant
```bash
jupyter notebook Clinical_Assistant.ipynb
```

Ensure your device microphone and speakers are enabled for full interaction.


### Demonstration

A live demonstration of the assistant is available here:  
**[Watch the Demo on YouTube](https://www.youtube.com/watch?v=your-video-link)**

The demo shows real-time voice input, patient-specific response generation, and multilingual spoken output using simulated patient data.


### Contributors

- **Yaswanth Ganapathi**  
- **Ganesh Vannam**  

