# 🏠 MaisonQuest
A bilingual real estate marketplace connecting property seekers with verified agencies across Cameroon bridging the gap between local listings and the global Cameroonian diaspora.

## The Problem
Finding housing or land in Cameroon currently means scrolling through fragmented WhatsApp broadcasts and Facebook groups with no central platform, no verification, and no guarantee the listing is legitimate. For Cameroonians abroad, the challenge is even greater: searching for property back home without being physically present leaves them especially vulnerable to fraud.

MaisonQuest solves this by giving users a single trusted platform where every listing comes from a verified agency bringing transparency and peace of mind to one of the most important decisions a person can make.

## The Solution
MaisonQuest operates on a B2B2C model. Real estate agencies list their verified properties on the platform, and MaisonQuest delivers those listings directly to renters and buyers actively searching or browsing.

For agencies, subscription tiers offer increased visibility, detailed analytics on listing performance, and actionable insights to help them reach more potential clients. For users, the platform is free to browse removing any barrier between them and finding their next home.

A built-in review system creates accountability on both sides, agencies can see how renters perceive their service and improve accordingly, while renters can make informed decisions based on the experiences of others.

## Platform Features

### 🔐 Authentication
Separate login and signup flows for renters and agencies, with role-based redirects ensuring each user lands in the right place.

### 🏢 Agency Dashboard
A full property management system where agencies can add, edit, pause, and delete listings, track inquiries, view detailed analytics on listing performance, manage their subscription plan, and respond to reviews.

### 👤 Agency Public Profile
A public-facing page where renters can browse an agency's listings, read reviews, see ratings, and make direct contact via the platform or WhatsApp.

### 🏠 Renter Dashboard
A personalised space where renters can manage saved listings, track inquiries, send and receive messages directly on the platform, write reviews, and update account settings.

### 🔍 Search & Filters
Homepage and listings page with filters for property type, location, number of bedrooms, and budget range, helping users find exactly what they need quickly.

### 🌍 Bilingual & Multi-Currency
Full English and French language toggle across all pages, with a currency switcher supporting XAF, USD, EUR and GBP designed for both local users and the Cameroonian diaspora abroad.

### 📄 About & Contact
Pages explaining MaisonQuest's mission and providing direct contact options for users and prospective agency partners.

## Project Management & Execution

MaisonQuest was structured across 6 phases using a project Gantt chart (included in this repository) to track progress, ownership, timelines, and priorities across every deliverable.

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 0 — Initiation | Project vision, market research, business model | ✅ Complete |
| Phase 1 — Planning | Requirements, tech stack, design system | ✅ Complete |
| Phase 2 — Frontend | 10-page frontend build & deployment | ✅ Complete |
| Phase 3 — Testing & QA | Cross-browser, filters, navigation, auth testing | 🔄 In Progress |
| Phase 4 — Backend | Supabase integration, real data, payments | 📋 Planned |
| Phase 5 — Launch | Agency onboarding, domain, marketing | 📋 Planned |
| Phase 6 — Growth | New cities, mobile app, partnerships | 📋 Planned |

The full project Gantt chart tracking all tasks, owners, dates and priorities is available in `MaisonQuest_Gantt.xlsx` in this repository.

## Tech Stack

| Tool | Purpose |
|------|---------|
| HTML / CSS / JavaScript | Frontend development |
| Claude AI | Code development — translating product requirements into code |
| Netlify | Hosting and deployment |
| Supabase | Backend database and authentication (Phase 4 — planned) |
| Microsoft Excel | Project Gantt chart and delivery tracking |
| Chrome / Safari + DevTools | Cross-browser testing and debugging |
| GitHub | Version control and portfolio documentation |

## Live Demo

🌐 [View MaisonQuest Live](https://visionary-pastelito-e7bd94.netlify.app/maisonquest.html)

> Note: Currently a frontend prototype. Backend integration (Supabase) is planned for Phase 4.
