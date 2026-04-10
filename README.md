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
<img width="1337" height="1069" alt="image" src="https://github.com/user-attachments/assets/9ddc1c77-906e-4079-98d3-9733c0420c69" />

##### Activity Diagram
<img width="1391" height="1237" alt="image" src="https://github.com/user-attachments/assets/aa4bb207-0859-49cc-80fa-9c31e841f598" />

## 🖥️ UI Interface

                                              # Reviews Scrapping
<img width="994" height="865" alt="image" src="https://github.com/user-attachments/assets/f003d350-7c19-472d-a8d8-6d01ca870e80" />

                                              # Dataset Creation
<img width="1140" height="526" alt="image" src="https://github.com/user-attachments/assets/566a324b-0df6-4df0-8069-b48c0b1a79c9" />

                                                    # Menu Bar
<img width="546" height="659" alt="image" src="https://github.com/user-attachments/assets/fb666ae3-30f8-4460-86d8-d88a760dc953" />

                                                # LLM Suggestions
<img width="1264" height="748" alt="image" src="https://github.com/user-attachments/assets/479537d7-ba1d-46f8-b40b-61327183ccf1" />


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

## 🏷️ Suggested Topics/Tags
nlp, sentiment-analysis, requirements-engineering, streamlit, python, transformers, ollama, quality-attributes, data-science

## 📄 Licence
Recommended: MIT (add `LICENSE` if missing and your dataset usage permits).

### 👩‍🎓 Author
Hamna Iqbal

🎓 Final Year BS Software Engineering
📌 Project Domain: Software Engineering, Artificial Intelligence, Data Science
