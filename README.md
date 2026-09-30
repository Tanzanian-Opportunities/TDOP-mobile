# TDOP Mobile

**Tanzania Digital Opportunity Platform (TDOP)** — mobile application for
opportunity seekers (browse, search, apply, track, notifications).

## Tech Stack

| Area | Technology |
|---|---|
| Framework | Flutter |
| Language | Dart |
| Target platforms | Android + iOS (single codebase for all supported devices) |
| Backend | TDOP REST API (`/api/v1`) — same contracts as the web app |
| State/state mgmt | Flutter-native (Riverpod/Provider — confirmed at scaffold time) |
| i18n | English + Swahili, parity with the web application |

The Flutter/Dart choice is the stack of record for the mobile application
(Decision **DEC-010**): one codebase keeps behavior, styling, and maintenance
consistent across all devices instead of maintaining separate native apps.

## Status

**Planned — stack decided, no code yet.** Implementation begins when its owning
phase starts (never ahead of the phase order, `PROJECT_MANAGEMENT.md` entry rules).
Until then this repository documents the plan only.

## What this repository will hold

- The Flutter/Dart seeker client (browse, search, apply, track, notifications).
- App scaffolding, widget tests, and platform build configuration (Android/iOS).
- Setup and test instructions in this README when development starts.

## Where to look in the meantime

| Resource | Location |
|---|---|
| Software requirements (SRS) | [TDOP-docs/Specs/SRS.md](https://github.com/Tanzanian-Opportunities/TDOP-docs/blob/develop/Specs/SRS.md) (§3.11 mobile requirements) |
| Product requirements | [TDOP-docs/README_PRD.md](https://github.com/Tanzanian-Opportunities/TDOP-docs/blob/develop/README_PRD.md) |
| Project management / roadmap | [TDOP-docs/PROJECT_MANAGEMENT.md](https://github.com/Tanzanian-Opportunities/TDOP-docs/blob/develop/PROJECT_MANAGEMENT.md) |
| Task boards (177 tasks, 33 phases) | [TDOP-docs/TASK_BREAKDOWN.md](https://github.com/Tanzanian-Opportunities/TDOP-docs/blob/develop/TASK_BREAKDOWN.md) |
| Backend API | [TDOP-backend](https://github.com/Tanzanian-Opportunities/TDOP-backend) |
| Web application | [TDOP-frontend](https://github.com/Tanzanian-Opportunities/TDOP-frontend) |
| Kanban board | https://github.com/orgs/Tanzanian-Opportunities/projects/1 |

## Branches

Like every TDOP repository: `develop` (default, integration) and `main`
(releases). See `TDOP-docs/DEVELOPMENT_GUIDE.md` §6.

## License

MIT - see [`LICENSE`](https://github.com/Tanzanian-Opportunities/TDOP-docs/blob/develop/LICENSE) (single license of record, kept in `TDOP-docs`).
