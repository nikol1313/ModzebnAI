<div align="center">
  
# ModzebnAI

🌐 [modzebnai.ge](https://...)

**An AI-powered job radar for the Georgian job market**

Watches job boards, compares every new listing against your CV, and makes applying easier.

🇬🇪 [ქართული ვერსია](README.ka.md)
</div>

---

## The Problem

Job hunting in Georgia means checking jobs.ge, hr.ge and other sites every day, reading through dozens of irrelevant listings, and rewriting the same cover letter over and over.

## How It Works

```
jobs.ge, hr.ge, …  →  Scrapers  →  PostgreSQL  →  AI Scoring  →  Email + Dashboard
```

1. **Collect** — Scheduled scrapers pull new listings from Georgian job sites into a single database.
2. **Score** — AI compares each listing to your CV, rates the match, and explains why.
3. **Notify** — When there's a strong match, you get an email with a cover letter tailored to that job.
4. **Dashboard** — See relevant jobs, their scores, and prepared cover letters in one place.

## Tech Stack

| Layer          | Technology                              |
|----------------|-----------------------------------------|
| Frontend       | React, TypeScript                       |
| Backend        | FastAPI, Python                         |
| Database       | PostgreSQL                              |
| AI             | LLM API  |
| Scraping       | Web automation: Playwright
| Scheduling     | Celery / cron |
| Infrastructure | Docker, Docker Compose                  |

## Project Structure

```
modzebnai/
├── backend/          
├── frontend/           
├── scrapers/           
├── docker-compose.yml
├── .env.example
└── README.md
```

## Status

This project is under active development.
