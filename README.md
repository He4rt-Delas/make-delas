# 💄 Makeup Products Research & Comparison Platform (MVP) - Make Delas
<div align="center">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="Test Lover" />
  <img src="https://img.shields.io/badge/HeartDelas-💜-purple" alt="Heart Delas" />
  <img src="https://img.shields.io/badge/In--Progress-🚧-black" alt="Status" />
</div>

## 📌 Project Overview

This project aims to develop an MVP (Minimum Viable Product) of a web platform for researching and comparing makeup products.

The platform allows users to:

- Search for makeup products
- Compare different brands
- View consolidated pricing information

The goal is to centralize relevant product data into a single, user-friendly platform, making it easier for users to make informed purchasing decisions.

## 🏗 Project Structure

- Architecture: Monolithic
- Repository Strategy: Monorepo

This project follows a monolithic architecture within a single repository, containing backend, frontend, and data-related services.

## 🔄 Development Model
### Git Flow

We follow the Git Flow branching strategy:

- `main` – Production-ready code
- `develop` – Integration branch
- `feature/*` – New features
- `release/*` – Release preparation
- `hotfix/*` – Production fixes

### Commit Convention

All commits must be written in English.

Commit pattern:
```bash
<feat|fix|chore>/DELAS-01 - Short description
```

Example:
```bash
feat/DELAS-01 - Add product comparison endpoint
fix/DELAS-01 - Fix price formatting issue
chore/DELAS-01 - Update dependencies
```

## 📋 Methodology

We use the Kanban methodology for task management and workflow organization.

## 🛠 Technologies

### 📊 Data Layer

- Python (data processing, scraping, or data consolidation)

### 🔙 Backend

- JavaScript or PHP
- Relational Database (e.g., PostgreSQL, MySQL)

### 🎨 Frontend

- React

### 🧪 Testing

- Postman – Backend API testing
- Playwright (TypeScript) – End-to-end testing

### ☁ Hosting

Infrastructure decisions will be defined by the Infra Girls team.

## 📁 Suggested Project Structure

```bash
/root
 ├── backend/
 ├── frontend/
 ├── data/
 ├── tests/
 ├── docs/
 └── README.md
```

🚀 MVP Scope

The MVP includes:

- Product search functionality
- Brand comparison
- Price aggregation
- Product rating visualization
- Basic filtering capabilities

Future improvements may include user accounts, personalized recommendations, and advanced analytics.

## 📖 Documentation

- All project documentation must be written in English.
- API documentation should be maintained and updated alongside development.
- Technical decisions should be documented inside the /docs directory.

## 👩‍💻 Contribution Guidelines

- Follow Git Flow.
- Use the commit pattern defined above.
- Write clean, maintainable, and documented code.
- Add tests whenever applicable.
- Open Pull Requests targeting the `develop` branch.