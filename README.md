# Hi, I'm Usama Waqas

Full-stack engineer building production mobile and web apps end to end — React Native with custom native modules, MERN/Next.js on the web, Supabase-backed data layers, and AI-powered features.

3 years experience · Lahore, Pakistan

## Stack

![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![NativeWind](https://img.shields.io/badge/NativeWind-Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

## What I do

- **React Native / Expo product engineering** — production apps with custom native modules, not just JS-only wrappers: accessibility services, VPN-based content filtering, device admin, and geofencing, all written in Kotlin and bridged into Expo.
- **Full-stack web with the MERN stack & Next.js** — React/Next.js front ends over Node.js/Express APIs and MongoDB, containerized with Docker for consistent local-to-production deployment.
- **AI-powered & on-device ML features in React Native** — on-device OCR (Google ML Kit text recognition) for real-world input like receipt scanning, and LLM-integrated features (Gemini API) for turning raw app data into plain-language insights.
- **Supabase / Postgres backends** — schemas with row-level security scoping every table to the signed-in user, auth flows (signup/login/password reset), and pure business-logic layers (debt simplification, currency conversion) kept separate from data fetching.

## Featured projects

### [LockFocus](https://github.com/UsamaWaqas/LockFocus) — FocusWarden, a screen-time & digital-wellbeing app

Blocks distracting apps and sites at the OS level via a custom native Android module — not just inside the app itself.

- Custom Expo native module (Kotlin): `AccessibilityService`-based app blocking, `VpnService`-based web/content filtering, `DeviceAdmin`-protected Strict Mode, and geofenced profile switching
- A rule-snapshot architecture so enforcement keeps running even if the JS app is killed or the device reboots
- Boot/tamper/battery watchdogs for OEM battery-killers (Xiaomi/MIUI, etc.)

*(Private repository — available on request.)*

### [DutchUp](https://github.com/UsamaWaqas/DutchUP) — Splitwise-style expense splitting

Group expenses, itemized receipts, and multi-currency balances on Supabase (Postgres + Auth + RLS), with no custom backend of its own.

- Pure debt-simplification math — reduces a group's tangled balances to the fewest actual payments
- On-device receipt OCR (ML Kit) that prefills an expense total from a photo, no cloud call
- Live currency conversion for balances, degrading gracefully to a 1:1 rate if the rate API is unreachable

*(Private repository — available on request.)*

## Links

- 💼 Upwork — [ADD YOUR UPWORK PROFILE LINK]
