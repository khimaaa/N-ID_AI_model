# N-ID — AI Identity Resolution Platform

## Project Overview
N-ID is an AI-powered identity resolution platform designed to unify and standardize identity records across multilingual and inconsistent administrative systems.  
It helps detect duplicates, normalize multilingual identity variations, and provide explainable AI decisions for administrative systems.

---

## Features
- Multilingual identity resolution (Arabic, French, Latin scripts, Hassaniya, Pulaar, Wolof)
- Duplicate detection and clustering
- Long-context document analysis
- Batch processing (CSV / Excel / large datasets)
- Real-time scoring system
- Explainable AI decisions
- Persistent identity graph storage

---

## Installation

### Backend
```bash
cd ai_project_backend
python -m venv venv
.\venv\Scripts\Activate.ps1  # Windows PowerShell
pip install -r requirements.txt
uvicorn main:app --reload --port 8000


### frontend
cd ai_project_frontend
npm install
npm run dev
