# BetaLife Medical Center — Digital Clinic DEMO

This folder contains the first working UX/UI prototype and the target production architecture.

## Run locally
Open `index.html` in a browser. No external packages are required.

## Demo scenarios
1. Public landing → services/doctors.
2. Online booking → multi-step form → confirmation.
3. Hair-loss test → 10 questions → non-diagnostic result → booking/WhatsApp.
4. DEMO CRM → Dashboard, Clients, Appointments, Doctors, Services, Leads, Analytics.
5. Language switcher is represented in the UI; production version should use i18n dictionaries for TJ/RU/EN.

## Next production phase
Split the monolith into Next.js frontend + NestJS API + PostgreSQL/Prisma + RBAC + notification adapters. The domain model and API contract are documented in ARCHITECTURE.md.
