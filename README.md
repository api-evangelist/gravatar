# Gravatar

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Gravatar (Globally Recognized Avatar) is a service that provides universally recognized avatars and rich identity profiles tied to email addresses via SHA256 hash. Developers can fetch user avatars, profile information, verified social accounts, and identity data using a REST API with API key or OAuth authentication. The service offers both a public avatar CDN (no auth required) and a REST API (v3) for profiles, avatar management, QR codes, and verified account lookups.

**Areas:** Avatars · Identity · Profiles · Social · Image · GraphQL · REST

## Gravatar on APIs.io

Everything profiled for Gravatar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gravatar/](https://apis.io/providers/gravatar/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Gravatar Avatars API](https://apis.io/apis/gravatar/gravatar-avatars-api/) — Operations about user avatars
- [Gravatar Experimental API](https://apis.io/apis/gravatar/gravatar-experimental-api/) — Experimental operations that might be subject to change. Use with caution.
- [Gravatar Profiles API](https://apis.io/apis/gravatar/gravatar-profiles-api/) — Operations about user profiles
- [Gravatar Qr Code API](https://apis.io/apis/gravatar/gravatar-qr-code-api/) — Operations about QR codes

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/gravatar/](https://apis.io/graphqls/gravatar/gravatar-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gravatar Agentic Access](https://apis.io/agentic-access/gravatar/gravatar-agentic-access/)

#### JSON Schema (11)

The data models the API reads and writes.

- [AssociatedResponse](https://apis.io/schemas/gravatar/associatedresponse/)
- [Avatar](https://apis.io/schemas/gravatar/avatar/)
- [CryptoWalletAddress](https://apis.io/schemas/gravatar/cryptowalletaddress/)
- [Error](https://apis.io/schemas/gravatar/error/)
- [GalleryImage](https://apis.io/schemas/gravatar/galleryimage/)
- [Interest](https://apis.io/schemas/gravatar/interest/)
- [Language](https://apis.io/schemas/gravatar/language/)
- [Link](https://apis.io/schemas/gravatar/link/)
- [Profile](https://apis.io/schemas/gravatar/profile/)
- [Rating](https://apis.io/schemas/gravatar/rating/)
- [VerifiedAccount](https://apis.io/schemas/gravatar/verifiedaccount/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [context Context](https://apis.io/jsonld/gravatar/context/)

#### Examples (12)

Example requests and responses.

- [Associatedemail](https://apis.io/examples/gravatar/associatedEmail/)
- [Deleteavatar](https://apis.io/examples/gravatar/deleteAvatar/)
- [Getavatars](https://apis.io/examples/gravatar/getAvatars/)
- [Getprofile](https://apis.io/examples/gravatar/getProfile/)
- [Getprofilebyid](https://apis.io/examples/gravatar/getProfileById/)
- [Getqrcodebysha256Hash](https://apis.io/examples/gravatar/getQrCodeBySha256Hash/)
- [Getverifiedaccountservices](https://apis.io/examples/gravatar/getVerifiedAccountServices/)
- [Searchprofilesbyverifiedaccount](https://apis.io/examples/gravatar/searchProfilesByVerifiedAccount/)
- [Setemailavatar](https://apis.io/examples/gravatar/setEmailAvatar/)
- [Updateavatar](https://apis.io/examples/gravatar/updateAvatar/)
- [Updateprofile](https://apis.io/examples/gravatar/updateProfile/)
- [Uploadavatar](https://apis.io/examples/gravatar/uploadAvatar/)

#### Collections (4)

Postman and Open Collection request collections.

- [Gravatar Public avatars API](https://apis.io/collections/gravatar/open-gravatar-avatars-api/)
- [Gravatar Public avatars experimental API](https://apis.io/collections/gravatar/open-gravatar-experimental-api/)
- [Gravatar Public avatars profiles API](https://apis.io/collections/gravatar/open-gravatar-profiles-api/)
- [Gravatar Public avatars qr-code API](https://apis.io/collections/gravatar/open-gravatar-qr-code-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Gravatar — jsonschema rules](https://apis.io/rules/gravatar/gravatar-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Gravatar Authentication](https://apis.io/security/gravatar/gravatar-authentication/)
- [Gravatar Domain Security](https://apis.io/security/gravatar/gravatar-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Gravatar Scopes](https://apis.io/scopes/gravatar/gravatar-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/gravatar/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/gravatar/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/gravatar/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.gravatar.com/)
- [Documentation](https://docs.gravatar.com/api/)
- [Getting started](https://docs.gravatar.com/rest/getting-started/)
- [Pricing](https://docs.gravatar.com/general/pricing/)
- [Blog](https://blog.gravatar.com/feed/)
- [Terms of service](https://gravatar.com/tos)
- [Privacy policy](https://gravatar.com/privacy-policy)
- [GitHub](https://github.com/Automattic/gravatar)

## API Evangelist rating

**Kin Score 38.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 55.3 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 45.2 |
| Access clarity | 26.3 |

**Agent readiness 33.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gravatar/](https://apis.io/providers/gravatar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Gravatar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gravatar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
