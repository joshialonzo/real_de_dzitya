# Real de Dzityá

Manager for the Real de Dzityá Condominio.

## Folder Structure

This repository is organized to support a multi-platform frontend, scalable backends, and agentic coding workflows ("vibe-coding"):

- **/frontend/**: The Flutter application tailored for Android, iOS, and Web.
- **/backend/**: Designated for future backend APIs (e.g., Python FastAPI/Django) to handle advanced business logic and processing.
- **/firebase/**: Contains Firebase configuration, security rules, Firestore indexes, and Cloud Functions.
- **/docs/**: Markdown documentation for project parameters, keeping developers and AI coding agents aligned (includes PRD, tech stack, and API agreements).
- **/scripts/**: Utility or bash scripts for launching emulators, local dev servers, and deployment automation.

## Running the Environments

For instructions on how to run, build, and deploy specific parts of the stack, see the dedicated READMEs inside each folder:

- 📱 [**Frontend / Flutter App Instructions**](./frontend/README.md)
- 🔥 [**Firebase & Emulator Instructions**](./firebase/README.md)
- 🐍 [**Python Backend Instructions**](./backend/README.md)

## Documentation

Project-level documentation lives in the [`docs/`](./docs/) directory:

- 📋 [**PRD (Product Requirements)**](./docs/PRD.md) — What we are building, target audience, roles, and feature index.
- 🏗️ [**Architecture**](./docs/ARCHITECTURE.md) — How the frontend, Firebase, and Python backend connect.
- 🧰 [**Tech Stack**](./docs/TECH_STACK.md) — Approved frameworks, libraries, and versions.
- 🎨 [**Style Guide**](./docs/STYLE_GUIDE.md) — Coding conventions for Dart and Python.
- 🔌 [**API Contracts**](./docs/API_CONTRACTS.md) — Firestore schemas and backend endpoint definitions.

### Feature Specs

Individual feature requirements are in [`docs/features/`](./docs/features/):

- 🔐 [Authentication](./docs/features/01_authentication.md)
- 🏘️ [Sections Management](./docs/features/02_sections_management.md)
- 🏠 [Houses Management](./docs/features/03_houses_management.md)
- 👤 [Neighbors Management](./docs/features/04_neighbors_management.md)
- 💰 [Payments Management](./docs/features/05_payments_management.md)
- 💸 [Expenses Management](./docs/features/06_expenses_management.md)
- 📊 [Financial Reports](./docs/features/07_reports.md)
