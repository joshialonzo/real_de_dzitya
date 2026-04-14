# System Architecture

## Overview
This application uses a federated architecture separating the client app from the backend and database layers.

### 1. Frontend (`/frontend`)
- **Framework**: Flutter (Dart)
- **Platforms**: iOS, Android, Web
- **Role**: Presentation, user interaction, client-side state management.

### 2. Backend - Phase 1 (`/firebase`)
- **Technology**: Firebase (Firestore, Auth, Cloud Functions)
- **Role**: Core data storage, real-time sync, serverless computing for initial logic.

### 3. Backend - Phase 2 (`/backend`)
- **Technology**: Python (FastAPI/Django - TBD)
- **Role**: Will eventually handle complex business logic, background processing, and heavy compute tasks that Firebase functions are ill-suited for.

## Data Flow
* [To be filled out: e.g., "The frontend listens to Firestore via Streams. When a user requests a heavy report, it hits the Python API which processes it and saves the result to Firestore"]*

## Agent Instructions
*When suggesting architectural changes, please review this document to ensure consistency with the master plan. If a change modifies this flow, update this document.*
