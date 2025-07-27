# 🎂 Sweet Shop Management System&nbsp;(SSMS)

A full‑stack web application that lets customers browse and buy sweets while admins manage inventory.  
Built with **Node.js + Express + TypeScript** on the back end and **React 18 + Vite + Tailwind** on the front end.  
100 % open source and ready to deploy on Vercel / Render / Railway.

---

## ✨ Features

| Area        | What’s included                                                                                     |
|-------------|------------------------------------------------------------------------------------------------------|
| **Backend** | RESTful API, JWT auth, role‑based access, CRUD for sweets, purchase & restock endpoints, PostgreSQL / SQLite, Jest + Supertest tests |
| **Frontend**| Responsive shop page with search & live stock, login form, admin dashboard to add/edit/delete/ restock sweets, Vitest + RTL tests |
| **Dev Ops** | npm workspaces monorepo, ESLint / Prettier, Tailwind, GitHub Actions CI, sample Docker & Render configs |
| **TDD**     | In‑memory SQLite for tests, coverage target ≥ 90 %, red‑green‑refactor workflow built‑in            |
| **AI Usage**| Generated boilerplate & tests are marked with `Co‑authored‑by: AI Assistant <ai@openai.com>`         |

---

## 🔧 Project Structure

ssms/
├─ backend/ ← Express API + TypeORM entities
│ ├─ src/
│ └─ tests/ ← Jest + Supertest
├─ frontend/ ← React 18 app
│ ├─ src/
│ └─ tests/ ← Vitest + RTL
├─ package.json ← npm workspaces root
└─ .env.sample ← copy to .env and fill secrets

yaml
Copy
Edit
