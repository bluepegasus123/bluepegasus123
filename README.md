### Hi, I'm William 👋

Software engineer building distributed backend systems — and increasingly focused
on developer experience, platform, and infrastructure work: the tools, pipelines,
and services that make other engineers faster and systems more reliable.

- 🔭 Currently: Member of Technical Staff @ Envoy (Oct 2025–present)
- 🌱 Exploring: developer experience, platform engineering, infrastructure,
  distributed systems, operating systems, storage

### What I do now — Envoy

Primary owner of the **Reservations** service and the **Maps** service, powering
enterprise workplace reservations and floor map view/edit operations.

- Cut floor map view API P95 latency from **3s → 500ms** with service-level
  caching, PostgreSQL indexes for common query patterns, and parallelized
  scatter-gather requests across three backend services — supporting
  **28.5M monthly requests**.
- Leading the rollout of a Next.js + MapLibre floor map viewing and editing
  frontend replacing Envoy's legacy floor map viewer/editor across live, shared,
  and kiosk views — reaching **~9M employees** across **~87K companies**.
  - Improved map pan, zoom, and tap frame rate on low-end kiosk displays by
    **~17% (46 → 54 FPS)** by cutting per-frame main-thread work: rendering
    selected markers in a lightweight overlay instead of re-sending all marker
    data, and skipping label recomputation and re-renders unless the data
    actually changed.
- Led a migration of Envoy's Next.js apps to versioned static asset hosting
  (S3 + CloudFront), so open sessions no longer break when a new version rolls
  out. Built shared CI workflows used across **7 repos** that deploy about
  **70 times a month**.

### Previously — DoorDash (Aug 2023–Sep 2025)

- Designed and built an asynchronous **Kafka-based message routing platform**
  for reliable bidirectional communication between Dasher app chat and SMS,
  with ordered delivery per conversation, idempotency, and retry semantics —
  saving ~**$1M/year** in delivery costs.
- Developed production-scale load tests that simulated peak production traffic
  against the chat platform's golden paths, run monthly to continuously
  validate reliability, latency, and scalability.
- Automated customer support workflows that increased self-service adoption,
  reducing support costs by ~**$1M/year**.

### Stack

- **Languages:** Java, Kotlin, SQL, TypeScript / JavaScript, Python, C
- **Backend:** Spring Boot, REST APIs, Kafka, PostgreSQL, event-driven
  architecture, distributed systems
- **Infrastructure:** Docker, ArgoCD, Git, CI/CD
- **Frontend:** React, Next.js
- **Education:** B.A. Computer Science, UC Berkeley (2019–2023) —
  Database Systems, Operating Systems

### Reach me

- 📧 wlouis23@berkeley.edu
- 💼 linkedin.com/in/williammlouis
