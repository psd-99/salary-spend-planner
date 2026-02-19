# Survive — Salary-Based Spending Planner

A Flutter app that helps you manage spending based on your salary cycle.
Instead of tracking categories like a typical expense tracker, **Survive** focuses on answering one key question:

> “How much is safe to spend today until my next payday?”

## Core Idea
You enter your salary and payday, then the app calculates:
- **Days remaining** until next salary
- **Remaining balance**
- **Safe-to-spend per day**
- Whether you're **on track** or **overspending**

## Tech Stack
### Mobile (Flutter)
- Flutter (Dart)
- MVVM-style architecture
- Riverpod (state management) *(planned)*
- Local persistence (Hive) *(planned)*

### Backend (planned)
- ASP.NET Core Web API
- Database (PostgreSQL or SQL Server)
- EF Core
- JWT Authentication

## Project Goals (Learning-Focused)
This project is built to gain solid hands-on experience with:
- Building a real Flutter app with scalable architecture
- Designing and consuming REST APIs
- Database modeling and persistence
- Authentication and secure API communication
- Clean code + maintainable project structure

## Roadmap
### Phase 1 — Offline MVP (Flutter only)
- [ ] Setup salary & payday
- [ ] Add expenses
- [ ] Dashboard summary (safe-to-spend today)
- [ ] Persist locally

### Phase 2 — Backend + Database
- [ ] Build API (auth + expenses + salary config)
- [ ] Add DB schema + migrations

### Phase 3 — Sync + Production
- [ ] Connect Flutter to API
- [ ] Cloud sync for multi-device support
- [ ] Deployment

## Getting Started
### Prerequisites
- Flutter SDK installed
- Android Studio / Xcode configured

### Run
```bash
flutter pub get
flutter run
