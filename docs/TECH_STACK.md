# Tech Stack

This document strictly defines the libraries, frameworks, and versions to be used in this project. **AI Agents: Do not deviate from this stack, use alternative libraries, or introduce new major dependencies without asking the user for confirmation.**

## Frontend (`/frontend`)
- **Language:** Dart
- **Framework:** Flutter (Web, iOS, Android)
- **State Management:** [e.g., Riverpod, BLoC - Please specify]
- **Routing:** [e.g., GoRouter - Please specify]
- **API Client:** `http` or `dio` (for Python backend), `cloud_firestore` (for Firebase)

## Primary Backend (`/firebase`)
- **Database:** Firebase Firestore
- **Authentication:** Firebase Auth
- **Storage:** Firebase Cloud Storage

## Secondary Backend (`/backend`)
- **Language:** Python 3.11+
- **Framework:** [e.g., FastAPI, Flask - Please specify]
- **Package Manager:** `pip` / `poetry` / `uv`

## Agent Instructions
*Before importing a package to Flutter (via pubspec.yaml) or Python (via requirements.txt), verify if there is an existing library listed here that solves the problem. If not, add your new dependency to this file as well.*
