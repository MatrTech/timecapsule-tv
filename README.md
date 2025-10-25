# TimeCapsule TV

TimeCapsule TV is a curated video library that preserves and surfaces community and historical video content from our youth — intentionally curated collections, not algorithmic "brainrot."

This repository contains a minimal starter skeleton:
- frontend/: Svelte (Vite) single-page app (development)
- backend/: .NET minimal Web API providing a simple API surface
- .github/: CI workflow and issue templates
- LICENSE, CONTRIBUTING, CODE_OF_CONDUCT and helper files

Quick start (developer)

- Frontend
  1. cd frontend
  2. npm install
  3. npm run dev
  4. Open http://localhost:5173

- Backend
  1. cd backend
  2. dotnet restore
  3. dotnet run
  4. API health: GET http://localhost:5231/health

Suggested local environment
- Node.js 18+ (for frontend)
- .NET 8.0 SDK
- Optional: Docker / Docker Compose

What’s next
- Add authentication (magic links / OAuth)
- Add media ingestion pipeline (ffmpeg transcoding)
- Add object storage config (S3) and HLS integration
- Add editorial admin UI for curated playlists
