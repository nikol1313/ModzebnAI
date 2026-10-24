<div align="center">
  
# ModzebnAI

![frontend](https://img.shields.io/badge/frontend-React-61DAFB?logo=react&logoColor=white)
![backend](https://img.shields.io/badge/backend-Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![database](https://img.shields.io/badge/database-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![scraping](https://img.shields.io/badge/scraping-Playwright-2EAD33)
![queue](https://img.shields.io/badge/queue-Celery-37814A?logo=celery&logoColor=white)
![docker](https://img.shields.io/badge/docker-compose-2496ED?logo=docker&logoColor=white)
![AI](https://img.shields.io/badge/AI-LLM-8A2BE2)
![license](https://img.shields.io/badge/license-MIT-blue)

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
| Backend        | Node.js, Express                       |
| Database       | PostgreSQL                              |
| AI             | LLM API  |
| Scraping       | Web automation: Playwright, python
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
