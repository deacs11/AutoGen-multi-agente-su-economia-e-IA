# 🤖📊 AutoGen-multi-agente-su-economia-e-IA

Questo progetto Colab utilizza [AutoGen](https://github.com/microsoft/autogen) di Microsoft per orchestrare un **dibattito intelligente multi-agente** su temi economici cruciali, con agenti che rappresentano scuole di pensiero diverse.

## 🎯 Obiettivo

Simulare un confronto tra diversi approcci economici per analizzare:

- L’impatto dell’intelligenza artificiale su **inflazione** e **disoccupazione**
- Le implicazioni dell’**invecchiamento della popolazione** sul **debito pubblico**
- Le possibili strategie politiche e monetarie secondo ogni ideologia

## 👥 Agenti coinvolti

- 🟦 **Keynesiano** – Propone interventi pubblici per stimolare la domanda
- 🟥 **Austriaco** – Promuove il libero mercato e l'auto-regolazione
- 🟨 **Neoclassico** – Pone enfasi sulla produttività, razionalità e ruolo marginale dello Stato
- 🧓 **Demografico** – Analizza l'effetto dell'invecchiamento su economia e welfare

## ⚙️ Tecnologia

- [AutoGen](https://github.com/microsoft/autogen)
- OpenAI GPT-4 (via API Key)
- Python 3 + Google Colab
- `fpdf2` per generazione PDF finale con dialogo + sintesi

## 📄 Output

- 🔁 Dibattito multi-turno tra agenti (fino a 3 round)
- 🧠 Sintesi automatica del confronto generata da un agente "sintetizzatore"
- 📄 File PDF esportato contenente:
  - Intera conversazione
  - Sintesi dettagliata

## 📦 Requisiti

- Python ≥ 3.9
- Pacchetti:
  - `pyautogen`
  - `openai`
  - `fpdf2`

## 🚀 Come usarlo su Colab

1. Apri il notebook `.ipynb` su Google Colab
2. Inserisci la tua chiave OpenAI nei **Segreti Colab** con nome `OPENAI_API_KEY`
3. Esegui le celle sequenzialmente
4. Scarica il PDF finale

## 💡 Espansioni possibili

- Agente “Storico” per comparazioni con eventi passati
- Agente “Analista” per generazione grafici e dati quantitativi
- Interfaccia utente via Streamlit
- Dibattito modulare su altri temi: geopolitica, etica, tecnologia

---


