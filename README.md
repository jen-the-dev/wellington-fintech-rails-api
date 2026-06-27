# Wellington FinTech Rails API
Portfolio repository aligned to ANZSCO 261312 (Developer Programmer), demonstrating API-first backend design for fintech-style workflows and regulated-domain requirements.

## Problem
Financial-domain products require maintainable API boundaries, reliable data workflows, and compliance-aware engineering practices.

## Solution
This repository presents a Rails API architecture with modular service structure, domain-focused data modeling, and operational setup patterns suitable for production-oriented teams.

## Architecture
- `app/` for core API domain logic and endpoint behavior.
- `config/` for environment and framework configuration.
- `db/` for schema and data lifecycle management.
- `docker-compose.yml` for local service orchestration.
- `docs/` for integration and operational documentation.

## Tech Stack
- Ruby on Rails (API-focused patterns)
- PostgreSQL
- Redis/background processing patterns
- Docker Compose

## Quick Start
```bash
bundle install
rails db:setup
docker-compose up -d
rails server
```

## Testing
- `rails test`
- API smoke checks against health/status endpoints.

## ANZSCO 261312 Competency Evidence
- **Programming and implementation**: backend API modules and service-oriented structure.
- **Systems integration**: fintech-style integration patterns and deployment workflow support.
- **Quality and maintainability**: documented setup and repeatable testing flow.

## Commit Convention
Use Conventional Commits for presentation clarity:
- `feat(scope): add new user-facing capability`
- `fix(scope): resolve functional defect`
- `test(scope): add or improve automated tests`
- `docs(readme): improve project documentation`

## Evidence Map
- `app/`
- `config/`
- `db/`
- `docker-compose.yml`
- `docs/`
