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

**AI-ზე დაფუძნებული სამუშაოს რადარი ქართული ბაზრისთვის**

აკვირდება ვაკანსიების საიტებს, ყოველ ახალ განცხადებას შენს CV-ს ადარებს და განაცხადის გაგზავნას გიმარტივებს.

🇬🇧 [English version](README.md)

</div>

---

## პრობლემა

საქართველოში სამუშაოს ძებნა ნიშნავს jobs.ge-ის, hr.ge-ისა და სხვა საიტების ყოველდღიურ შემოწმებას, ათობით შეუსაბამო ვაკანსიის კითხვას და ერთი და იმავე სამოტივაციო წერილის ხელახლა წერას.

## როგორ მუშაობს

```
jobs.ge, hr.ge, …  →  სკრეიპერები  →  PostgreSQL  →  AI შეფასება  →  ელფოსტა + დაფა
```

1. **შეგროვება** — განრიგით გაშვებული სკრეიპერები ქართული საიტებიდან ახალ ვაკანსიებს ერთ ბაზაში აგროვებს.
2. **შეფასება** — AI თითოეულ ვაკანსიას შენს CV-ს ადარებს, აფასებს შესაბამისობას და ხსნის, რატომ.
3. **შეტყობინება** — კარგი დამთხვევისას ელფოსტაზე მოდის შეტყობინება, ვაკანსიაზე მორგებულ სამოტივაციო წერილთან ერთად.
4. **დაფა** — ერთ ადგილას ჩანს შესაბამისი ვაკანსიები, მათი შეფასებები და მომზადებული წერილები.

## ტექნოლოგიები

| ფენა           | ტექნოლოგია             |
|----------------|------------------------|
| Frontend       | React, TypeScript      |
| Backend        | Node.js, Express       |
| მონაცემთა ბაზა | PostgreSQL             |
| AI             | LLM API                |
| სკრეიპინგი     | Playwright, python       |
| განრიგი        | Celery / cron          |
| ინფრასტრუქტურა | Docker, Docker Compose |

## პროექტის სტრუქტურა

```
modzebnai/
├── backend/
├── frontend/
├── scrapers/
├── docker-compose.yml
├── .env.example
└── README.md
```

## სტატუსი

პროექტი აქტიური დეველოპმენტის პროცესშია.
