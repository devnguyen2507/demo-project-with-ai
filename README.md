# demo-project-with-ai

Project bootstrap for a demo app combining a Rust (Axum) backend, Next.js 16 frontend (App Router), and PostgreSQL database.

Project structure
- backend/: Rust + Axum backend
- frontend/: Next.js 16 App Router frontend
- db/: Database helpers (docker-compose for PostgreSQL)

Quick start
- Start Postgres: `docker compose -f db/docker-compose.yml up -d`
- Start backend: `cd backend && cargo run`
- Start frontend: `cd frontend && npm install && npm run dev`

See individual folders for minimal starter code.