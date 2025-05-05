# SkillSync

SkillSync is a smart, AI-powered job matching system that enables professionals to discover the most relevant job listings based on their resume content. Using advanced NLP techniques like Granite, BERT embeddings and cosine similarity, it evaluates semantic alignment between resumes and job descriptions.

## 🚀 Features

- **Job Scraping:** Gathers fresh job listings from multiple platforms (LinkedIn, Indeed, Glassdoor, Google Jobs, and more).
- **Resume Parsing:** Supports PDF and Markdown formats, extracting text for analysis.
- **Semantic Matching:** Leverages Granite and BERT embeddings for understanding and ranks jobs using cosine similarity.
- **Smart Filters:** Eliminates irrelevant roles based on location, keywords, and job-type preferences.
- **Interactive UI:** Powered by Streamlit, offering a smooth interface to upload resumes and view top job matches.

## 🧰 Tech Stack

- Python
- Hugging Face Transformers (Granite, BERT)
- Streamlit
- scikit-learn
- PyPDF2
- rake-nltk
- JobSpy

## 📂 Setup

```bash
pip install -r requirements.txt
streamlit run filter.py

## Contributors
Sreekar Gadasu | Aanshi Patwari
