# 💬 Sentiment Analysis of Software Requirements in Social Media Platform (FYP)

## 🧭 Project Overview
An automated user-feedback analysis pipeline that collects app reviews, performs sentiment analysis, categorises feedback into software quality attributes, and produces improvement suggestions (optionally using Phi‑3 via Ollama), presented through a Streamlit dashboard.

## ✨ Features
- Review collection from Google Play Store (scraping scripts included)
- Sentiment analysis (positive / neutral / negative)
- Quality-attribute categorisation (e.g., performance, usability, security, reliability)
- Optional LLM-based improvement suggestions (Phi‑3 via Ollama)
- Multiple dashboard scripts for interactive exploration and summary insights

## 🏗️ System Architecture
- **Ingestion:** scraping and/or CSV import
- **Preprocessing:** cleaning, transformation, feature preparation
- **Analysis:** sentiment classification + quality-attribute mapping
- **Suggestion:** optional LLM-assisted recommendations (Ollama)
- **UI:** Streamlit dashboard(s)


**Architecture flow (text):**  
`Google Play Store Reviews → Scraping/CSV → Preprocessing → Sentiment + Quality Attributes → (Optional) LLM Suggestions → Streamlit Dashboard`

##### Use Case Diagram
<img width="969" height="742" alt="image" src="https://github.com/user-attachments/assets/5c072785-6a15-4667-8fc8-76ecfd537ecd" />

##### Sequence Diagram
<img width="942" height="835" alt="image" src="https://github.com/user-attachments/assets/3fb7a009-d1d0-4413-9e75-93c67813c176" />


## 🖥️ UI Interface

                                              # Reviews Scrapping
<img width="1126" height="1002" alt="image" src="https://github.com/user-attachments/assets/c464c9ee-f7dd-4d14-8f78-f6ecf11cb7d2" />

                                              # Dataset Creation
<img width="1303" height="580" alt="image" src="https://github.com/user-attachments/assets/f5c1bbab-e218-4a50-910d-0cd87999115b" />

                                                    # Menu Bar
<img width="599" height="767" alt="image" src="https://github.com/user-attachments/assets/43ab4b76-4a32-4aa6-ae48-0101a54caac3" />

                                                # LLM Suggestions
<img width="1225" height="712" alt="image" src="https://github.com/user-attachments/assets/056d2872-6dac-45d6-8ff8-4969d85f9d62" />



## 🧰 Tech Stack
- Python
- Web scraping: Beautiful Soup *(optional: Selenium if enabled)*
- NLP/ML: scikit-learn, Transformers *(as used in your pipeline)*
- LLM (optional): Ollama (Phi‑3)
- Data/visualisation: Pandas, NumPy, Plotly/Matplotlib/Seaborn
- UI: Streamlit

## ⚙️ Installation and Setup

### 1) Clone
```bash
git clone https://github.com/HamnaIqbal44/Sentiment-Analysis-of-Software-Requirements-in-Social-Media-Platform-FYP-.git
cd Sentiment-Analysis-of-Software-Requirements-in-Social-Media-Platform-FYP-
```

### 2) Create and activate a virtual environment
```bash
python -m venv .venv
```

**Windows**
```bash
.venv\Scripts\activate
```

**macOS/Linux**
```bash
source .venv/bin/activate
```

### 3) Install dependencies
```bash
pip install -r requirements.txt
```

### 4) Run the Streamlit dashboard
> This repository contains multiple candidate entrypoints (examples include `dashboard.py`, `senti_dash.py`, `sentidash.py`).  
> Choose one and set it here:

```bash
streamlit run <STREAMLIT_ENTRYPOINT>.py
```

## 🗃️ Dataset
- Data source: Google Play Store reviews (scraped) and/or local CSVs in this repository.

## 🧪 Usage / Demo
1. Run the Streamlit entrypoint.
2. Load sample CSV or run scraping (if enabled).
3. Review sentiment trends and quality-attribute breakdowns.
4. Inspect suggestion outputs (if LLM option enabled).

## 📄 Licence
Recommended: MIT (add `LICENSE` if missing and your dataset usage permits).

### 👩‍🎓 Author
Hamna Iqbal

🎓 Final Year BS Software Engineering
📌 Project Domain: Software Engineering, Artificial Intelligence, Data Science
