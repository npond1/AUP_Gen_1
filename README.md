# AUP Generator Web App

This is a Flask-based web app that allows clients to input their company information, upload a logo, and generate a customized Acceptable Use Policy (AUP) as a downloadable Word document.

## Features
- Form input for key AUP fields
- Optional logo upload (inserted in header)
- Signature acknowledgment block at the end

## Setup Instructions
1. Clone this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app locally:
   ```bash
   python app.py
   ```

## Deploy on Render
- Ensure `Procfile` and `requirements.txt` are present
- Set build command: `pip install -r requirements.txt`
- Set start command: `gunicorn app:app`
