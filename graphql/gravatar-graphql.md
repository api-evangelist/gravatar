# Gravatar GraphQL

## Description

Gravatar does not expose a native GraphQL endpoint. This schema is a conceptual GraphQL representation of the Gravatar REST API v3, derived from the public REST types documented at https://docs.gravatar.com/rest-api/ and the OpenAPI specification available at https://api.gravatar.com/v3/openapi.

The schema models the core Gravatar identity primitives — profiles, avatars, and hover cards — as they exist in the REST API, translated into GraphQL SDL for use in schema stitching, federation overlays, or client-side tooling that prefers a GraphQL interface.

## Endpoint

No native GraphQL endpoint. REST base URL: https://api.gravatar.com/v3

## Documentation

- REST API Reference: https://docs.gravatar.com/rest-api/
- Getting Started: https://docs.gravatar.com/rest/getting-started/
- Avatar API: https://docs.gravatar.com/api/avatars/
- OpenAPI Spec: https://api.gravatar.com/v3/openapi
- GitHub: https://github.com/Automattic/gravatar

## Schema Source

Conceptual model derived from Gravatar REST API v3 types. No native GraphQL API exists as of June 2026.
