# API Contracts

This file defines the data contracts and schemas passed between the frontend, Firebase, and Python backend.

## Firestore Collections

### `users` collection
```json
{
  "uid": "string",
  "email": "string",
  "displayName": "string",
  "createdAt": "timestamp"
}
```

## Python API Endpoints (Future)

### `GET /api/v1/health`
**Response:**
```json
{
  "status": "ok"
}
```

## Agent Instructions
*When adding a new Firestore collection or a new endpoint in Python, document the JSON shape and URLs here so the frontend can easily generate its models.*
