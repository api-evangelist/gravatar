# Gravatar (gravatar)

Gravatar (Globally Recognized Avatar) is a service that provides universally recognized avatars and rich identity profiles tied to email addresses via SHA256 hash. Developers can fetch user avatars, profile information, verified social accounts, and identity data using a REST API with API key or OAuth authentication. The service offers both a public avatar CDN (no auth required) and a REST API (v3) for profiles, avatar management, QR codes, and verified account lookups.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gravatar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gravatar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Avatars
- Identity
- Profiles
- Social
- Images
- GraphQL
- REST

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Gravatar Avatar API

Public CDN-based API for fetching user avatars by SHA256 email hash. Supports image size customization, default image fallbacks, and content rating filters. Avatar requests do not count against rate limits.

- **Human URL:** [https://docs.gravatar.com/api/avatars/](https://docs.gravatar.com/api/avatars/)
- **Base URL:** `https://0.gravatar.com`

#### Tags

- Avatars
- Images
- CDN

#### Properties

- [Documentation](https://docs.gravatar.com/api/avatars/)
- [OpenAPI](https://api.gravatar.com/v3/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Gravatar REST API

REST API (v3) for retrieving and managing Gravatar user profiles, avatars, QR codes, and verified account lookups by SHA256 email hash or profile slug. Supports API key (Bearer token) and WordPress OAuth2 authentication. Unauthenticated requests are limited to 100/hour; authenticated requests receive 1,000/hour.

- **Human URL:** [https://docs.gravatar.com/rest-api/](https://docs.gravatar.com/rest-api/)
- **Base URL:** `https://api.gravatar.com/v3`

#### Tags

- Profiles
- Avatars
- Identity
- Verified Accounts
- QR Codes

#### Properties

- [Documentation](https://docs.gravatar.com/rest-api/)
- [OpenAPI](https://api.gravatar.com/v3/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.gravatar.com/rest/getting-started/)
- [Authentication](https://docs.gravatar.com/rest/getting-started/#authentication)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/gravatar/refs/heads/main/rate-limits/rate-limits.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/gravatar/refs/heads/main/plans/plans.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/gravatar/refs/heads/main/finops/finops.yml)
- [Graph Q L](graphql/gravatar-graphql.md)

## Common Properties

- [Portal](https://docs.gravatar.com/)
- [Documentation](https://docs.gravatar.com/api/)
- [OpenAPI](https://api.gravatar.com/v3/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.gravatar.com/rest/getting-started/)
- [Authentication](https://docs.gravatar.com/rest/getting-started/#authentication)
- [Pricing](https://docs.gravatar.com/general/pricing/)
- [Status](http://status.automattic.com/9931/136545/Gravatar)
- [GitHub Organization](https://github.com/Automattic/gravatar)
- [Android S D K](https://docs.gravatar.com/sdk/android/)
- [i O S S D K](https://docs.gravatar.com/sdk/ios/)
- [A P I Explorer](https://docs.gravatar.com/api/explorer/)
- [Terms of Service](https://gravatar.com/tos)
- [Privacy Policy](https://gravatar.com/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
