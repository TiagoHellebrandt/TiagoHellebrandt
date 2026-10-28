# Tiago Hellebrandt

**Senior Full-Stack & Mobile Developer** · TypeScript, Go, React Native and LLM-based products

Várzea Grande (Cuiabá metro area), MT, Brazil (UTC−4) · Building software since 2018 · **Open to remote roles**

I build whole products end to end — backend, web, mobile, infrastructure and the pipelines that ship them — and I care about the boring parts that keep them running: tests, migrations, observability and security.

> Catholize's code is private. The best public sample of my current work is [Replider](https://github.com/TiagoHellebrandt/replider); older repos here are mostly early or personal projects.

---

### Highlights

**[Catholize](https://catholize.com)** · Founder & Tech Lead (2022–2026)

A Catholic platform in production on web, iOS and Android: geolocated Mass and confession search, social feed, video channels, courses, events with payments, chat and voice rooms. Investor-backed; I designed and built it from scratch and led a team of 3 developers.

- **Backend migration:** moved a live AdonisJS (Node.js/TypeScript) API to Go one route at a time, with identical responses and both stacks sharing one database during the cutover. It now serves 400+ endpoints across 30+ domain modules on PostgreSQL/PostGIS.
- **Mobile:** React Native apps (new architecture) with a native video module I wrote in Swift and Kotlin, plus in-app purchases and push notifications.
- **Video & payments:** a Go orchestrator that spins up spot GPU VMs on demand to transcode to adaptive HLS/DASH (ffmpeg/NVENC), which cut the largest item on the cloud bill; Stripe, Apple/Google in-app purchases and PIX, including payouts to event organizers.
- **Trust & safety:** AI-assisted moderation with human review, and child protection compliant with Brazil's ECA Digital law (age assurance, guardian approval, data retention).
- **AI:** MCP server giving AI assistants access through scoped, revocable tokens; LLM-based content classification.
- **Infrastructure & quality:** Kubernetes, infrastructure as code with OpenTofu (DigitalOcean, Google Cloud, Cloudflare), signed container images, load tests, ~9,000 Go tests with real-PostgreSQL integration tests and a CI coverage gate, automated App Store and Google Play releases.
- Led the team's move to AI-assisted development (Claude Code, agents, spec-driven development), with a strong focus on security.

**[Replider](https://github.com/TiagoHellebrandt/replider)** · AI customer-service platform · Solo builder (2026, discontinued, now open source)

- Built and ran it in production on my own: Go API, Flutter dashboard, Astro landing page, infrastructure and CI/CD.
- **AI:** RAG over each business's own content (PostgreSQL + pgvector), tool calling, Gemini/OpenAI behind circuit breakers, per-account spend caps, encrypted bring-your-own-key.
- **Omnichannel:** WhatsApp, Telegram, Instagram, e-mail and an embeddable web widget, with live human takeover over WebSockets (Redis fan-out across instances).
- **Reliability:** transactional outbox for webhooks, ~3,900 Go tests, end-to-end tests against a real database gating every deploy, OpenTelemetry, Prometheus and Sentry, backups with automated restore drills.
- MCP server exposing the platform to AI assistants.

**Open source:** [react-native-htmlviewer](https://github.com/TiagoHellebrandt/react-native-htmlviewer) renders HTML content in React Native apps. I wrote it for the Estuda.com app.

### Earlier experience

| Company | Role | Years |
| --- | --- | --- |
| Rondon Gerenciamento de Risco | Software Developer (logistics risk-management systems) | 2022–2024 |
| Checkplant / Farmbox | Frontend Developer (migrated a legacy ActionScript app to React) | 2021–2022 |
| Cuiabá Med | Software Developer | 2020–2021 |
| Meu Trampo | Co-founder (recruiting SaaS) | 2019–2022 |
| Estuda.com | Mobile & Backend Developer: sole mobile developer of the React Native app (1M+ downloads on Google Play) on a 5-person dev team, later mentored a new teammate; also worked on the PHP backend | 2018–2020 |

### Tech stack

- **Strongest:** TypeScript / JavaScript, Node.js, React, React Native
- **Also in production:** Go, Flutter, Python · PostgreSQL (PostGIS, pgvector), MySQL, Redis · Docker, Kubernetes, OpenTofu, Google Cloud, DigitalOcean, Cloudflare · GitHub Actions, Fastlane · OpenTelemetry, Prometheus, Sentry
- **AI:** LLM APIs (Gemini, OpenAI), RAG, tool calling, MCP servers, agent-based development workflows
- **Working knowledge:** AWS, native mobile modules in Swift and Kotlin

### Talks

- React Native components · DevFest Cuiabá 2019
- In-app purchases in mobile apps · DevMT (UFMT)

---

### Let's talk

I'm open to remote full-stack, mobile and AI product roles. The fastest way to reach me is by email or LinkedIn.

[thellebrandtsilva@gmail.com](mailto:thellebrandtsilva@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tiago-hellebrandt)

Portuguese (native) · English (intermediate, B1)
