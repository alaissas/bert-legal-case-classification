# 🏛️ LexBERT: Intelligent Legal Case Classification and Summarization using BERT

A comprehensive NLP project for automating **legal case classification**, **summarization**, **similarity search**, **topic modeling**, and **explainability** using state-of-the-art transformer models like **BERT**, **SBERT**, **BART**, and **BERTopic**.

## 📌 Project Features

- ✅ **Legal Case Classification** using fine-tuned BERT
- ✅ **Case Summarization** with BART (facebook/bart-large-cnn)
- ✅ **Semantic Similarity Search** via SBERT embeddings
- ✅ **Topic Modeling** using BERTopic
- ✅ **Explainable AI (XAI)** with SHAP for understanding predictions
- ✅ **Legal Case Exploration CLI/Script** (optional Streamlit deployment-ready)
- ✅ Clean and modular notebook-based implementation

---

## 🎯 Project Aim

To develop an AI-powered system that understands legal case facts, classifies them into issue areas, generates concise summaries, and provides similar past cases — enhancing decision support in the legal domain.

---

## 🎯 Objectives

- Build a robust **text classification** pipeline for legal issues.
- Summarize lengthy legal case descriptions using transformer-based summarization.
- Integrate **semantic similarity search** for retrieving relevant cases.
- Apply **topic modeling** to uncover hidden legal themes and clusters.
- Incorporate **model explainability (SHAP)** to interpret model decisions.
- Deliver a clear, modular, and scalable codebase.

---


---

## 🔧 Technologies Used

- `transformers` (HuggingFace)
- `sentence-transformers`
- `BERTopic`
- `SHAP`
- `Pandas`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `Plotly`
- `PyTorch`

---

## 🧠 Models Used

- **BERT (bert-base-uncased)** – for legal issue classification
- **BART (facebook/bart-large-cnn)** – for abstractive summarization
- **SBERT (all-MiniLM-L6-v2)** – for case similarity search
- **BERTopic** – for unsupervised topic modeling
- **SHAP** – for feature attribution-based explainability

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/alaissas/legal-bert-classification.git
cd legal-bert-classification
