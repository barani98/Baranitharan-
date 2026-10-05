# Baranitharan-
LegalEase is an AI-powered legal assistance platform designed to make legal information easier to understand and access. It helps users understand legal documents, identify important clauses, summarize complex legal content, and get simple explanations of legal terms.
 LegalEase

AI-powered legal document drafting application based on the supplied project specification.

## Run

1. Create a virtual environment:
   `python -m venv .venv`

2. Activate it on Windows:
   `.venv\Scripts\activate`

3. Install:
   `pip install -r requirements.txt`

4. Copy `.env.example` to `.env` and add your Gemini API key.

5. Start backend:
   `uvicorn main:app --reload`

6. In another terminal start frontend:
   `streamlit run app.py`

The application provides document generation, editing, and TXT/DOCX/PDF export.

Important: generated legal text is an AI draft and should be reviewed by a qualified legal professional.
