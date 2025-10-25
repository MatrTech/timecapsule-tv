# TimeCapsule TV

TimeCapsule TV is a curated video library that preserves and surfaces community and historical video content from our youth — intentionally curated collections, not algorithmic "brainrot." The project aims to provide a calm, searchable archive of meaningful videos: home recordings, community events, local TV, school projects, and other media that shaped a generation.

Goals
- Preserve community video content and metadata
- Provide curated, human-led collections and themed playlists
- Offer simple upload and moderation tooling for contributors
- Deliver reliable playback via HLS with transcoding for multiple bitrates
- Avoid algorithmic feed mechanics; emphasize editorial discovery

MVP features
- Browse curated collections by decade, event, or theme
- Video playback (HLS) with adaptive bitrate
- Basic upload flow with moderation and metadata (title, year, people, tags)
- Search and filters (year, tags, people)
- User collections / playlists and editorial front page

Quick start (developer)
1. Clone the repo
   git clone https://github.com/matrtech/timecapsule-tv.git
2. Install dependencies (example for Node.js stack)
   cd timecapsule-tv
   npm install
3. Configure environment
   cp .env.example .env
   Fill in storage (S3), DB, and auth values
4. Run locally
   npm run dev

Suggested tech stack
- Frontend: React + TypeScript
- Backend: Node.js + Express or Django REST Framework
- Storage: S3-compatible object storage + CDN (CloudFront)
- Video: ffmpeg for transcoding, HLS for streaming
- DB: PostgreSQL; search via Meilisearch / Elasticsearch
- Auth: OAuth / magic link

Contributing
We welcome contributions. Please open issues for discussion and submit PRs that follow the repository's style. Add tests for new features when possible.

License
This repository is intended to use the MIT license. See LICENSE file for details.

Contact
Project owner: @visschersm (matrtech)

---

This is the initial README for the TimeCapsule TV repository in the matrtech organization. Please tell me if you want additional files (LICENSE, CODE_OF_CONDUCT, CONTRIBUTING, .github workflows) and I will add them.