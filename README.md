# 🩺 HealthGuardian AI
An intelligent health assistant that helps users understand their symptoms using natural language input, verified medical data, and AI-powered analysis. The system provides possible causes, urgency levels, home remedies, and medical advice referral—while supporting multiple languages and ensuring safe, educational guidance.

---

## 🚀 Features

- 🧠 Natural Language Symptom Input  
- 🩹 Condition Suggestions & Urgency Levels  
- 🌐 Multilingual Support  
- 🏠 Home Remedy Recommendations  
- 👨‍⚕️ Referral Guidance to Health Professionals  
- 🔍 Powered by Language Models and Medical Knowledge Bases  
- 📚 Uses Verified Medical Data (WHO, CDC, Journals)  

---

## 🧱 System Architecture

```mermaid
graph TD;
    UI[User Interface] --> SYM[User Symptoms];
    SYM --> LM[Language Model];
    LM --> KB[Medical Knowledge Base];
    KB --> IDX[Index Medical Data];
    LM --> OUT[Generated Output];
    SYM --> OUT;


✅ Prerequisites
 1. IBM Cloud Account – Sign up
 2. Access to Watsonx.ai (Language Model APIs)
 3. Watson Discovery instance



🔐 Data Sources & Safety
This project retrieves health information from trusted sources (e.g., WHO, CDC). It does not diagnose, treat, or replace professional medical advice. All outputs are educational and informational.

📈 Future Scope
Wearable device integration

Mental health and chronic illness modules

Personalized Health Profiles: Build user-specific health timelines and offer more accurate suggestions based on medical history, lifestyle, and genetic factors.Real-Time Collaboration Features

Telemedicine Integration: Directly connect users with certified doctors or clinics for virtual consultations when medical attention is needed. Integration with Publishing Platforms


🚀 How It Works
 1.User inputs a query (e.g., “I have a sore throat and fever”)
 2.IBM Granite LLM processes the language
 3.Vector Index retrieves trusted content from uploaded PDFs
 5.Agent responds with a grounded, natural-language answer
<img width="351" height="717" alt="image" src="https://github.com/user-attachments/assets/5de85dd8-a552-4d0d-99c5-37f74378d670" />


📐 SETUP & TESTING
<img src="[images/screenshot.png](https://github.com/deepakpatel54/AI_health_agent/blob/main/setup.png)" width="600"/>

🪲 DEPLOYED
<img src="[images/screenshot.png](https://github.com/deepakpatel54/AI_health_agent/blob/main/deployed.png)" width="600"/>



🤝 Contributors
Deepak Patel
