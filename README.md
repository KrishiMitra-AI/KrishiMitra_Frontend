# KrishiMitra AI

> Ek app. Saare faisle. Har kisan ke liye.

AI-powered farming assistant built for Indian farmers. 6 features in one app.

## Features
- Disease Scanner (Gemini Vision + Hindi voice output)
- Price Forecast (Agmarknet API + 7-day prediction)
- Mandi Swipe (Tinder-style buyer-farmer matching)
- Weather Alert (farming-specific Hindi alerts)
- Crop Advisor (AI crop recommendations)
- KisanBot (Hindi AI chat assistant)

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React + Vite + Tailwind CSS |
| Backend | Java 17 + Spring Boot 3 |
| Database | Supabase (PostgreSQL) |
| AI | Gemini 1.5 Flash API |
| Prices | Agmarknet API |
| Weather | OpenWeatherMap API |
| Deploy | Vercel (frontend) + Render (backend) |

## Team
| Role | Responsibility |
|------|---------------|
| P1 — Frontend Lead | React UI, Vercel deploy |
| P2 — AI & APIs | Gemini, Agmarknet, OpenWeatherMap |
| P3 — Backend & DB | Spring Boot, Supabase, Render |
| P4 — Pitch & QA | Testing, demo, presentation |

## Setup

### Frontend
```bash
cd krishimitra-frontend
npm install
cp .env.example .env.local
# Fill in your API keys in .env.local
npm run dev
```

### Backend
```bash
cd krishimitra-backend
# Fill in application.properties with your keys
mvn spring-boot:run
```

## Live Demo
- Frontend: [Vercel URL — add after deploy]
- Backend API: [Render URL — add after deploy]
