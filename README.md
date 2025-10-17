# 🧠 Zero-Shot Text Classification App

Eine interaktive **Streamlit-Webanwendung**, die mithilfe eines **Zero-Shot-Classifiers** von **Hugging Face Transformers** beliebige Texte automatisch in frei definierte Kategorien einordnet.  
Zusätzlich können aktuelle **Google News RSS-Schlagzeilen** abgerufen und direkt klassifiziert werden.

---

## 🚀 Funktionen

- 📰 **Google News Integration:** Aktuelle Schlagzeilen automatisch abrufen  
- 🤖 **Zero-Shot-Klassifikation:** Texte ohne Training in eigene Kategorien einordnen  
- 🏷️ **Freie Kategorieeingabe:** Beliebige Themenbereiche (z. B. *economy, politics, sport, health, finance*)  
- 🔁 **Mehrlabel-Unterstützung:** Texte können mehreren Kategorien gleichzeitig zugeordnet werden  
- 📊 **Visualisierung:** Balkendiagramm mit Wahrscheinlichkeiten  
- 💾 **CSV-Export:** Ergebnisse herunterladen  

---

## 🧩 Technologien

| Komponente | Beschreibung |
|-------------|--------------|
| **Python** | Hauptsprache |
| **Streamlit** | UI-Framework für die Web-App |
| **Transformers (Hugging Face)** | Zero-Shot-Textklassifikation |
| **Pandas** | Datenanalyse & CSV-Export |
| **Requests + XML** | RSS-Daten von Google News abrufen und verarbeiten |

---

## ⚙️ Installation

## 1️⃣ Repository klonen

git clone https://github.com/<dein-benutzername>/zero-shot-classifier-app.git
cd zero-shot-classifier-app


### Virtuelle Umgebung erstellen
python -m venv venv

### Aktivieren unter Windows
venv\Scripts\activate

### Aktivieren unter macOS/Linux
source venv/bin/activate

## Abhängigkeiten instalieren
pip install -r requirements.txt

## App starten
streamlit run app.py

