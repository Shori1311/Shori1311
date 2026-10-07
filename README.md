# Uros Simonovic

Full-stack developer in Belgrade, Serbia. React and TypeScript on the front end, NestJS and Prisma on the back end, React Native (Expo) on the phone.

Most of my code lives in private company repositories, so the contribution graph shows the volume but not the source. The short version is below.

## What I'm building

**GoSchool** is a multi-tenant school management platform used daily by private schools in Serbia: a NestJS API, a React admin, a React Native parent app and a Next.js website in one Turborepo monorepo. In 2026 I merged 258 pull requests there, about half of the project's total, as one of three developers.

Areas I own or co-own:

- **Grading**: configurable grading systems (numeric, letter, descriptive, Cambridge), period-scoped grades, typed final grades, analytics and server-rendered PDF report cards.
- **Notifications**: a single `emit()` entry point over a shared category catalog, per-recipient translation, push digests per parent and child, an in-app inbox in the mobile app.
- **Communication**: bulk email and SMS campaigns to parents and staff with delivery tracking and per-school quotas, branded HTML templates.
- **Design system**: 84 reusable React components, light and dark themes with per-school brand colors, contrast checked by an automated Playwright audit and enforced through custom ESLint rules.
- **Releases**: 20 production releases with blue-green zero-downtime deploys, mobile releases v1.2 to v1.4 on the App Store and Google Play, and an in-app "What's new" changelog in 7 languages.

## Stack

| Area | Tools |
| --- | --- |
| Frontend | React 19, TypeScript, Vite, TailwindCSS v4, TanStack Query, react-hook-form + Zod, i18next, Vitest |
| Mobile | React Native, Expo (expo-router, Reanimated, push notifications, OTA updates), EAS Build and Submit |
| Backend | Node.js, NestJS 11, Prisma 7, MySQL/MariaDB, Redis + Bull, Socket.io, Jest |
| Tooling | Docker, GitHub Actions, Sentry, Playwright, Turborepo, ESLint, husky + commitlint |

## How I work

TypeScript everywhere, pull requests with code review before every push, Conventional Commits, unit and end-to-end tests, Sentry-driven production triage. I use Claude Code daily for implementation and agentic code review, with the project's conventions encoded as an agent rulebook.

## Before GoSchool

GoKinder and GoFitness (React web apps and hybrid Android apps published on Google Play), WooCommerce, WordPress and Magento stores, and a year of SQL and Excel automation as a database developer.

## Contact

shorry.us@gmail.com
