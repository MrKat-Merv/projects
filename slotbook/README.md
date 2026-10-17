# SlotBook

A booking app for a small tutoring centre. Customers book and pay for 1-hour sessions; staff manage tutors and their open slots.
It's my foundation project: auth, roles, database constraints, transactions, payments, background jobs, tests and deployment, all in one app.

## Layout

```
slotbook/
├── backend/     Django project (API, models, management commands, tests)
├── frontend/    React + TypeScript
└── docs/        decisions, notes, failure drills
```

## Milestones

| | Milestone | Status |
|---|---|---|
| M1 | | |
| M2 | | |
| M3 | | |
| M4 | | |
| M5 | | |
| M6 | | |
| M7 | Deployment: nginx + gunicorn + HTTPS | |
| M8 | | |

## Run locally

```sh
cd backend && python -m venv .venv && . .venv/bin/activate && pip install -r requirements.txt && python manage.py runserver
cd frontend && npm install && npm run dev
```

Secrets go in `.env` (ignored); `.env.example` lists the names.
