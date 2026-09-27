# CarePrep

CarePrep is an English/Korean educational healthcare visit-preparation prototype.

This consolidated repository uses the `careprep` branch and contains:

- `backend/` — FastAPI API, curated health-resource retrieval, OpenAI integration, summaries, and tests.
- `frontend/` — static HTML/CSS/JavaScript interface for GitHub Pages.

It is not a diagnostic service or validated triage tool. Configure the backend API key in a local or Render environment variable; never commit `.env` or place a key in the frontend.

See [backend/README.md](backend/README.md) and [frontend/README.md](frontend/README.md) for setup and deployment details.
