# Aleksandr Magdysyuk

**Senior Full Stack Engineer — backend focus.** Brest, Belarus.

5+ years of commercial Node.js / TypeScript. Since 2023 I've been at **AIScreen**, a B2B SaaS
digital signage platform running a fleet of 10K+ connected screens, where I own features end to
end: NestJS services, device identity and synchronisation, content delivery and analytics
dashboards — and the Vue client on top of them. Before that, event-driven CRM at **EPAM Systems**
on Kafka, PostgreSQL and Redis.

The problems I like are the ones that show up at scale: cache invalidation, exactly-once delivery,
a query that got slow, and devices that lose their connection and have to come back on their own.

> **Open to Senior Backend / Full Stack roles — remote or relocation.**

---

## Stack

**Backend**
Node.js · TypeScript · NestJS · REST · WebSocket · SSE · TypeORM · JWT / OAuth 2.0

**Data**
PostgreSQL · Redis · query tuning & indexing · migrations · SQLite

**Messaging & reliability**
Kafka · BullMQ · transactional outbox · idempotency · DLQ · circuit breaker

**Infrastructure**
Docker · GitHub Actions · DigitalOcean · Cloudflare · Nginx · Linux

**Frontend**
Vue 3 · Nuxt 4 · Composition API · Pinia · Tailwind CSS · Vite

**Testing**
Jest · Playwright

---

## Projects

Built end to end — backend, frontend and deployment.

### Sketch Duel

A doodle-guessing duel against a neural network: you draw and it guesses, or it replays a real
human drawing from Google's QuickDraw set and you guess. The classifier is an MLP trained from
scratch in plain JavaScript, quantised to int8 (~300 KB) and run in the browser — no backend, no
API call, nothing ever leaves the device. Training and inference share one stroke-rasterisation
implementation, so the model never sees a different input shape than the one it was trained on.

`JavaScript` · `Vue` · `custom MLP` · `int8 quantisation`
→ [draw.gitignore.space](https://draw.gitignore.space) · [source](https://github.com/CredoRevolution/sketch-duel)

### AI Changelog Monitor

Watches the official changelogs of OpenAI, Anthropic, Google and Mistral and notifies on model
changes. Scheduled jobs, diffing and delivery by email and Slack.

`Nuxt 4` · `TypeScript` · `Turso` · `Drizzle ORM` · `Trigger.dev` · `Resend`
→ [source](https://github.com/CredoRevolution/AI-changelog-monitor)

### ourtracks

A shared, invite-only map where a place holds a song, photos and a memory. Google OAuth, an
invite list enforced in the database with row-level security, and photo storage.

`Nuxt 4` · `Supabase (PostgreSQL, RLS, Storage)` · `MapLibre GL` · `Vercel`
→ [ourtracks.gitignore.space](https://ourtracks.gitignore.space) · [source](https://github.com/CredoRevolution/ourtracks)

### Comma

A Git-based worklog that turns focus sessions into structured Markdown logs.

`Nuxt 4` · `TypeScript` · `Drizzle ORM` · `Turso` · `Octokit`
→ [comma.gitignore.space](https://comma.gitignore.space)

### Users API

A small NestJS service kept as a reference for how I set a backend up: registration, JWT with
refresh-token rotation, pagination, soft delete, migration-driven schema (`synchronize` off) and
Swagger.

`NestJS` · `PostgreSQL` · `TypeORM` · `Docker`
→ [source](https://github.com/CredoRevolution/nest-users-api)

---

## Contact

[Telegram](https://t.me/AlexGitignore) ·
[LinkedIn](https://www.linkedin.com/in/aliaksandr-mahdysiuk/) ·
[sadistik871m@gmail.com](mailto:sadistik871m@gmail.com)
