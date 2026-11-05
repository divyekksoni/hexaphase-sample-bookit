# BookIt

A web app for booking appointments with local service providers (salons, tutors, clinics).

[![Built with Hexaphase](https://img.shields.io/badge/built%20with-Hexaphase-6f42c1)](https://github.com/divyekksoni/hexaphase)

A sample project built with the **Hexaphase SDLC Framework** by Divyek Soni. Mode: **Standard**.

## Status
See [project-health.md](project-health.md). Current phase: **1 – Planning**.

## Structure
```
sample-bookit/
├── ai-instructions.md
├── project-health.md
├── 1-Planning/ … 3-Design/
├── 4-Coding/
│   ├── main-app/             ← Customer-facing booking web app (the launchable product)
│   ├── booking-api/          ← Backend API: providers, slots, bookings
│   ├── admin-portal/         ← Provider dashboard to manage availability and bookings
│   ├── shared/               ← Shared types and validation used by all three apps
├── 5-Testing/
└── 6-Deployment/
```

## Run
The launchable app is `4-Coding/main-app/`. Instructions are in its README once Phase 4 starts.
