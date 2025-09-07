# 💊 Drug-Drug Interaction (DDI) Prediction Web App

This project is a web-based application for predicting **drug-drug interactions (DDIs)** using machine learning models. It integrates biomedical datasets (like TWOSIDES, DrugBank, and RDF2Vec embeddings) with pre-trained models (MLP, XGBoost) to identify potential adverse interactions between drugs.

---

## 🧠 Project Highlights

- ✅ Built with **Flask** (Python)
- 🧬 Uses drug embeddings (`rdf2vec`) and curated drug name mappings
- 🤖 Pre-trained models:
  - `MLP` (`.h5` file)
  - `XGBoost` (`.pkl` and `.json`)
- 📊 Data: TWOSIDES, DrugBank, RxNorm mappings
- 🧪 Web interface for predicting and displaying interactions

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Logicrithm/DDI.git
cd DDI
```
2. Install Dependencies

Make sure you have Python 3.8+ installed. Then install required packages:

```bash
pip install -r requirements.txt
```
3. Run the Web App
```bash
cd app
python app.py
```
