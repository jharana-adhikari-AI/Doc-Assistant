# THE DOCASSISTANT

A Medical Assistant System for Symptom Analysis and Drug Recommendation using AI.

## 🧠 Overview

**THE DOCASSISTANT** is a healthcare-focused AI system developed to improve efficiency in medical consultations. It assists in:
- **Symptom Analysis** – helping patients determine the right medical specialty.
- **Drug Recommendation** – supporting healthcare providers in selecting appropriate medications.

This project utilizes **Natural Language Processing (NLP)**, **Topic Modeling (LDA)**, and **Large Language Models (BERT)** to enhance decision-making in clinical environments.

---

## 📋 Features

- 🔍 **Symptom Analysis** using BERT embeddings.
- 💊 **Drug Recommendation System** based on provider patterns.
- 📊 **Exploratory Data Analysis (EDA)** with visual insights.
- 🧪 **Topic Modeling with LDA** for grouping drugs.
- 🤖 **Fine-tuned BERT** for classification tasks.
- 🌐 **Web Interface** built using Flask.

---

## 📁 Data Source

- Source: [Drugs.com](https://www.drugs.com)
- Format: JSONL (JSON Lines)
- Size: Large-scale dataset processed in chunks
- Preprocessing includes:
  - Filtering providers with <40 unique drugs
  - Normalizing nested JSON data
  - Handling class imbalance

---

## 🔍 Exploratory Analysis Highlights

- 29 unique medical specialties identified.
- Bar charts and heatmaps reveal class imbalances and confusion patterns.
- F1-score analysis shows strong performance, especially for major classes.
- Classification Accuracy: **96.67%**
- Weighted Precision: **97.06%**

---

## 🧵 Topic Modeling with LDA

Latent Dirichlet Allocation (LDA) was used to:
- Discover hidden drug groupings
- Reduce dimensionality
- Improve feature relevance for classification

### Sample Topics:
- Sedatives: *Temazepam, Lorazepam, Clonazepam*
- HIV Medications: *Norvir, Truvada, Isentress*
- MS Medications: *Copaxone, Baclofen, Avonex*

---

## 🧠 BERT-based Language Modeling

- Leveraged **BERT embeddings** to encode symptoms and drug text semantically.
- Fine-tuned BERT for **symptom-to-drug classification**.
- Outperformed traditional ML models on F1-score.
- Applied strategies to handle **imbalanced class distribution**.

---

## 🚀 Future Work

- Develop a custom Large Language Model (LLM).
- Improve performance for underrepresented classes.
- Enhance real-time recommendation system for hospitals and clinics.

---

## 💻 Frontend

- Built with **Flask**
- Interactive user interface for medical staff and patients

Live Project: [GitHub Repository](https://github.com/rishabhjha1/Doc-Assistant)

---

## 👥 Team

- **Jharana Adhikari**
- **Uma Maheshwari**
- **Rishabh Jha**
- **Shishir Mishra**

---

## 📚 References

- Bajwa J, Munir U, Nori A, Williams B. *Artificial intelligence in healthcare.* Future Healthc J. 2021.
- Hao T, Huang Z, Liang L, et al. *Health NLP Methodologies and Applications.* JMIR Med Inform. 2021.
- Tamang S, Humbert-Droz M, et al. *NLP Systems for Population Health.* JMIR Med Inform. 2023.
- Yadav SK, Singh AK. *AI in Medical Imaging.* Multimedia Tools and Applications. 2022.
