# Wellington FinTech Rails API Suite

> **🏦 Enterprise-grade financial services API built for Wellington's fintech ecosystem** - Demonstrating API design, multi-tenant patterns, and compliance-minded modeling.

[![Rails Version](https://img.shields.io/badge/Rails-7.1-red.svg)](https://rubyonrails.org/)
[![Ruby Version](https://img.shields.io/badge/Ruby-3.2-red.svg)](https://www.ruby-lang.org/)

---

## 🚀 Live demo

- **Try it in GitHub Codespaces (recommended):** https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1070408263
- **Sample requests:** `samples/requests.http`

---

## 🛠️ Getting Started

### Quick Setup
```bash
# Clone and setup
git clone https://github.com/arcaneglam/wellington-fintech-rails-api.git
cd wellington-fintech-rails-api

# Install dependencies
bundle install

# Setup database
rails db:setup
rails db:seed

# Start services
docker-compose up -d
rails server
```

---

## 📖 Documentation

- **[RBNZ Prudential Requirements](docs/rbnz-compliance.md)**
- **[IRD Integration Guide](docs/ird-integration.md)**
- **[FMA Compliance Framework](docs/fma-compliance.md)**
- **[Open Banking NZ](docs/open-banking.md)**
- **[Xero Integration Patterns](docs/xero-patterns.md)**
- **[Kiwibank Digital Strategy](docs/kiwibank-digital.md)**
- **[Trade Me Financial Services](docs/trademe-fintech.md)**
- **[Wellington Startup Ecosystem](docs/wellington-ecosystem.md)**

---

## Demo endpoints

A few useful ones (see `samples/requests.http`):
- `GET /health`
- `GET /api/v1/status`
- `GET /api/v1/financial_transactions`
- `GET /api/v1/compliance/audit_logs`

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
