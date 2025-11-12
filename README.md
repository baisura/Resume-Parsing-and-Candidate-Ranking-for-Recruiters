**Resume Parsing and Candidate Ranking for Recruiters**


**Project Overview**

This project automates the extraction of key information from unstructured resumes and ranks candidates based on specified job criteria using AI-powered Natural Language Processing (NLP). Leveraging large language models such as Mistral or llama2 via Ollama, resumes and job descriptions are parsed into structured data. Candidates are then scored and ranked to assist recruiters in making fast, accurate, and unbiased hiring decisions.

**Features**
NLP-driven resume and job description parsing

Candidate matching and ranking based on job criteria

Modular backend built with FastAPI

Interactive frontend using Streamlit

Local LLM inference for data privacy and cost efficiency

API integration for scalable deployment

**Installation**

Clone the repo

**Install dependencies:**

bash
pip install -r requirements.txt
Run Ollama or your preferred local LLM runtime

**Start the FastAPI backend:**

bash
uvicorn main:app --reload
Launch the Streamlit frontend:

bash
streamlit run app.py


**Usage**
Input your resume and job description texts in the frontend.

The backend APIs extract, process, and rank candidates.

Results are displayed interactively for recruiter review.

**Future Work**
Support for multiple resume formats (PDF, DOCX)

Multi-lingual parsing and global recruitment support

Enhanced candidate scoring and predictive analytics

Integration with Applicant Tracking Systems (ATS)
