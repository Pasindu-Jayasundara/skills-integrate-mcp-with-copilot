# Add Auth: Google OAuth + JWT

Implement authentication using Google OAuth for login and issue JWTs for API auth.

## Tasks

- Add Google OAuth flow (client id/env config) and callback handling.
- Issue and verify JWTs for API requests; protect resolvers/endpoints.
- Add login/logout UI, store token in cookie/localStorage, and client-side auth handling.
- Add tests for auth flows and token expiry handling.

## Rationale

Authentication is required to restrict administrative operations and map actions to users.

Suggested labels: security, backend
