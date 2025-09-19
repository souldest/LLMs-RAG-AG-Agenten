# 📘 Einführung in LLMs, RAG und AI-Agenten

Willkommen zu diesem Projekt!  
Dieses Repository enthält ein interaktives **Jupyter Notebook**, das die Grundlagen von **Large Language Models (LLMs)**, **Retrieval-Augmented Generation (RAG)** und **AI-Agenten** demonstriert.  

Das Projekt richtet sich an Studierende, Entwickler:innen und Interessierte, die einen praxisnahen Einstieg in moderne KI-Technologien suchen.

---

## 🚀 Inhalte

- **LLM-Demonstration**: Grundlagen und Abfragen (OpenAI oder Dummy-Modus).  
- **RAG (Retrieval-Augmented Generation)**: Dokumentensuche und Textgenerierung.  
- **AI-Agenten**: Einfache Entscheidungslogik zwischen LLM und RAG.  
- **Interaktive Widgets**: Eingabefeld, Slider für Temperature & Max Tokens, Dokumentenübersicht.  

---

## 📂 Dateien

- `notebooks/notebook.ipynb` → interaktives Notebook (ausführbar in Jupyter).  
- `notebooks/notebook.html` → statische Version des Notebooks zum Ansehen.  
- `requirements.txt` → benötigte Python-Pakete.  
- `README.de.md` → diese Dokumentation.  

---

## ⚙️ Installation & Setup

1. Repository klonen oder herunterladen:
   ```bash
   git clone https://github.com/DEIN_USERNAME/LLM-RAG-Agenten-Kurs.git
   cd LLM-RAG-Agenten-Kurs
Virtuelle Umgebung erstellen (optional, empfohlen):

bash
Code kopieren
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Abhängigkeiten installieren:

bash
Code kopieren
pip install -r requirements.txt
Jupyter starten:

bash
Code kopieren
jupyter notebook
🔑 OpenAI API-Key (optional)
Für echte LLM-Abfragen wird ein OpenAI API-Key benötigt:

API-Key hier erstellen

Im Notebook setzen:

python
Code kopieren
import os
os.environ["OPENAI_API_KEY"] = "DEIN_API_KEY"
Ohne API-Key läuft das Notebook im Dummy-Modus mit Beispielantworten.

📚 Voraussetzungen
Python 3.9 oder neuer

Jupyter Notebook / JupyterLab

Basiskenntnisse in Python

👨‍🏫 Autor
Dr. Sidi Ould-Weiss
📧 estaghvirou.b@gmail.com
📞 0176/31591931

📜 Lizenz
Dieses Lernmaterial darf nur mit ausdrücklicher Genehmigung des Autors genutzt werden.
