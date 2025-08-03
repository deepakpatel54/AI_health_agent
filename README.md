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
