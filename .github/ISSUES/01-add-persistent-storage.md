# Add persistent storage for activities

Replace the in-memory activities store with persistent storage so activity data persists across restarts and we can enable analytics and user accounts in future.

## Tasks

- Choose and configure a database (suggest MongoDB) and add connection via env var `MONGO_URL`.
- Create an `Activity` model and a migration/seed to populate sample activities.
- Update `src/app.py` endpoints to read/write from the DB instead of the in-memory dict.
- Add tests for signup/unregister and DB integration.
- Update `README.md` with run instructions and required environment variables.

## Rationale

Persistent storage ensures reliability, enables analytics and scaling, and is required before adding user accounts or dashboards.

Suggested labels: enhancement, backend

*Created by automation — open a pull request to add this file to the repository, or convert this file into a GitHub Issue.*
