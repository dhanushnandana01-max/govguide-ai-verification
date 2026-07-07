# GovGuide AI – Government Document Verification Assistant

## Overview
GovGuide AI is an AI-powered web application that helps users verify government documents before submission. It uses OCR and Google Gemini AI to analyze uploaded documents, detect issues, and provide guidance for government services.

## Features
- User Registration & Login
- AI-powered document verification
- OCR-based text extraction
- Government service guidance
- Secure authentication
- Modern responsive interface

## Tech Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

### Backend
- FastAPI
- Python
- SQLAlchemy
- JWT Authentication

### AI & OCR
- Google Gemini AI
- Tesseract OCR

## Project Structure

```
govguide-ai-verification/
├── frontend/
├── backend/
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/dhanushnandana01-max/govguide-ai-verification.git
```

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Live Demo

Frontend:
https://paperpilot-flame.vercel.app

Backend API:
https://paperpilot-vdow.onrender.com

API Documentation:
https://paperpilot-vdow.onrender.com/docs

## Future Improvements

- Aadhaar verification
- PAN verification
- Passport verification
- AI chatbot enhancements
- Email notifications
- Mobile application

## Author

**Dhanush N**

GitHub:
https://github.com/dhanushnandana01-max
