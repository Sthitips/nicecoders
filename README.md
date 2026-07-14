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

# Development Workflow

Please do **not** commit directly to the `main` branch.

## 1. Pull the latest changes

```bash
git checkout main
git pull origin main
```

## 2. Create a feature branch

```bash
git checkout -b feature/<feature-name>
```

Examples:

```text
feature/auth
feature/wardrobe
feature/listings
feature/dashboard
feature/semantic-search
```

## 3. Work on your feature

Commit your changes regularly.

```bash
git add .
git commit -m "Add JWT authentication"
```

## 4. Push your branch

```bash
git push origin feature/<feature-name>
```

## 5. Merge into `main`

Open a Pull Request on GitHub (recommended), or merge after reviewing the changes.


## Setup

Backend

pip install -r requirements.txt

uvicorn app.main:app --reload

Frontend

npm install

npm run dev
