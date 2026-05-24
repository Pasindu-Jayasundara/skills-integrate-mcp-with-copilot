# Add Role-Separated Frontends

Create distinct frontends for back-office (admin) and teachers/managers, with role-aware routing and UI.

## Tasks

- Bootstrap `front_bo` (admin) and `front_m` (manager) Next.js apps or separate routes.
- Implement access control based on user roles.
- Share UI components via a local `ui` package.

## Rationale

Separation keeps admin workflows focused and reduces risk of accidental admin actions by regular users.

Suggested labels: frontend, enhancement
