# Add GraphQL API & types

Introduce a GraphQL API and generated TypeScript types to support richer queries and client integrations.

## Tasks

- Design GraphQL schema for Activities (+ future models: centers, groups, students, instructors).
- Implement resolvers and server (GraphQL over HTTP).
- Add TypeScript type generation for client usage (`generated/graphql`).
- Update frontend to use GraphQL queries/mutations where appropriate.

## Rationale

GraphQL enables flexible queries for UI, stronger typing across client/server, and easier evolution of API.

Suggested labels: enhancement, api
