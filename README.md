# James Han

Self-taught software engineer. I build and ship complete products on my own, from the native mobile
app down to the backend and the deploy pipeline behind it.

I built Fyt, a social fitness app that has been live on the App Store since July 2026: a SwiftUI
iOS and watchOS app, a TypeScript and PostgreSQL backend, and a Claude-powered coach. Sole engineer,
front to back.

- Live on the App Store: [Fyt: Run Club & Gym Tracker](https://apps.apple.com/us/app/fyt-run-club-gym-tracker/id6783633047)
- Westminster, CA, open to remote
- hanjames55@gmail.com

## What I work with

- Languages: TypeScript, Swift, Rust, Python, SQL
- Backend: Node.js, Fastify, PostgreSQL, Drizzle ORM, pg-boss job queues, REST API design
- Apple: SwiftUI, watchOS, HealthKit, WorkoutKit, WidgetKit, Live Activities, App Intents, StoreKit
- Infrastructure: Fly.io, Docker, GitHub Actions, Cloudflare R2, Vitest, Playwright
- AI: Anthropic Claude API, Claude Agent SDK, tool use, prompt caching, MCP servers

## Some of my work

**Fyt: Run Club & Gym Tracker**, live on the App Store with 370+ registered users. A native iOS and
watchOS app plus a full backend: a 390-endpoint Fastify API on a 202-table Postgres schema, a workout
ingestion pipeline that merges HealthKit, Strava, Garmin, and FIT uploads into one record, a weekly
coach and an iMessage assistant built on Claude, and 13,500 tests behind a pre-push gate and blue-green
deploys. [See it on the App Store](https://apps.apple.com/us/app/fyt-run-club-gym-tracker/id6783633047).
Source is private, but I'm glad to walk through it.

**tradebot**, a research-first trading platform in Python. Every strategy is a frozen spec with kill
criteria set before its first backtest; an event-driven backtester with shuffled-entry, one-bar-delay,
and fill-pessimism controls decides whether a result counts. 26k lines, 2,680 tests, a mutation-testing
gate. Available on request.

**poly-rs**, an async market maker in Rust for Polymarket's binary markets (Tokio, WebSockets, on-chain
settlement on Polygon) with regime detection, adverse-selection spread widening, and a circuit breaker.
Ran live on real capital in February 2026; 118 tests. Available on request.

---

Most of my repositories are private, since they are a live commercial product and trading systems.
I'm happy to walk through the code or share access for interviews. Just reach out.
