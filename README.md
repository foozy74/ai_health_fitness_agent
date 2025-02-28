# **KI Gesundheits- & Fitnessplaner Agent 🏍b️**

Der **KI Gesundheits- & Fitnessplaner** ist ein personalisierter Gesundheits- und Fitness-Agent, der auf dem **Agno AI Agent Framework** basiert. Diese Anwendung erstellt maßgeschneiderte **Ernährungs- und Fitnesspläne** auf Basis von Benutzereingaben wie **Alter, Gewicht, Größe, Aktivitätslevel, Ernährungspräferenzen und Fitnessziele**.  

## **Funktionen**  

- **Gesundheits- und Fitness-Agenten**  
  - Die App verwendet zwei spezialisierte KI-Agenten für **Ernährungsberatung** und **Fitness-/Trainingsberatung**.  

- **Personalisierte Ernährungspläne**  
  - Erstellt detaillierte Mahlzeitenpläne (Frühstück, Mittagessen, Abendessen und Snacks).  
  - Berücksichtigt wichtige Aspekte wie **Flüssigkeitszufuhr, Elektrolyte und Ballaststoffe**.  
  - Unterstützt verschiedene **Diät-Präferenzen** wie **Keto, Vegetarisch, Low-Carb** usw.  

- **Personalisierte Fitnesspläne**  
  - Erstellt individuelle **Trainingsroutinen** basierend auf den Fitnesszielen.  
  - Beinhaltet **Aufwärmübungen, Haupttraining und Cool-down-Phasen**.  
  - Gibt umsetzbare **Fitness-Tipps** und Ratschläge zur **Fortschrittsverfolgung**.  

- **Interaktives Q&A-System**  
  - Benutzer können **Fragen zu ihren Plänen stellen**, die von der KI beantwortet werden.  

---

## **Voraussetzungen**  

Die Anwendung benötigt folgende Python-Bibliotheken:  

- `agno`  
- `google-generativeai`  
- `streamlit`  

Diese Abhängigkeiten sollten über die Datei `requirements.txt` installiert werden.  

---

## **Anwendung starten**  

### **Schritt 1: API-Schlüssel besorgen**  
Bevor du beginnst, benötigst du einen **kostenlosen Gemini API Key**, den du hier erhältst:  
🔗 **[Google AI Gemini API Key](https://aistudio.google.com/apikey)**  

### **Schritt 2: Repository klonen**  
Öffne ein Terminal oder eine Eingabeaufforderung und gib folgendes ein:  
```bash
git clone git@github.com:foozy74/ai_health_fitness_agent.git
cd /ai_health_fitness_agent
```

### **Schritt 3: Abhängigkeiten installieren**  
```bash
pip install -r requirements.txt
```

### **Schritt 4: Streamlit-App starten**  
```bash
streamlit run health_agent.py
```

Die Anwendung wird nun gestartet und kann über den Browser aufgerufen werden. 🚀  

---
