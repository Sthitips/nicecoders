# Circular Fashion AI

AI-powered marketplace for buying, renting and swapping clothes sustainably.

## Tech Stack

Frontend
- React
- TailwindCSS

Backend
- FastAPI

Database
- PostgreSQL

AI
- Gemini
- Sentence Transformers

## Project Structure

Circular-Fashion-AI
│
├── backend
│   ├── app
│   │   ├── ai
│   │   ├── models
│   │   ├── routes
│   │   ├── schemas
│   │   ├── services
│   │   ├── utils
│   │   ├── config.py
│   │   ├── database.py
│   │   ├── dependencies.py
│   │   └── main.py
│   ├── uploads
│   ├── requirements.txt
│   └── .env.example
│
├── frontend
│   ├── src
│   │   ├── pages
│   │   ├── components
│   │   ├── api
│   │   ├── context
│   │   ├── hooks
│   │   ├── utils
│   │   ├── assets
│   │   └── routes
│   └── package.json
│
├── docs
│   ├── API.md
│   ├── DATABASE.md
│   ├── ROADMAP.md
│   └── TODO.md
│
├── README.md
├── .gitignore
└── LICENSE

## Setup

Backend

pip install -r requirements.txt

uvicorn app.main:app --reload

Frontend

npm install

npm run dev