# Guichet ML

API FastAPI qui detecte la langue d'un texte (mode mock hors ligne ou Hugging Face).

## Installation (Windows PowerShell)

    py -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install -r requirements.txt
    Copy-Item .env.example .env

## Lancer

    uvicorn app.main:app --reload

Puis ouvrir http://127.0.0.1:8000/docs

## Tests

    pytest -q
