# Cat Facts (catfact.ninja)

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

Cat Facts is a free, no-authentication community REST API at catfact.ninja that serves random cat trivia and a catalog of cat breeds. It exposes three documented endpoints — a single random fact, a paginated list of facts, and a paginated list of breeds — and ships a Swagger UI based OpenAPI 3.0 document at /docs. The service is widely used in API onboarding tutorials, demos, and sample apps because it requires no API key and returns small, predictable JSON payloads.

**Areas:** Animals · Cats · Trivia · Public APIs · Community · No Authentication · REST

## Cat Facts (catfact.ninja) on APIs.io

Everything profiled for Cat Facts (catfact.ninja) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cat-facts-catfact/](https://apis.io/providers/cat-facts-catfact/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Cat Facts (catfact.ninja) Breeds API](https://apis.io/apis/cat-facts-catfact/cat-facts-catfact-breeds-api/) — Catalog of cat breeds with country, origin, coat, and pattern.
- [Cat Facts (catfact.ninja) Facts API](https://apis.io/apis/cat-facts-catfact/cat-facts-catfact-facts-api/) — Random cat trivia, individually or in paginated lists.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cat Facts Catfact Agentic Access](https://apis.io/agentic-access/cat-facts-catfact/cat-facts-catfact-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [Breed](https://apis.io/schemas/cat-facts-catfact/cat-facts-catfact-breed/)
- [BreedList](https://apis.io/schemas/cat-facts-catfact/cat-facts-catfact-breed-list/)
- [CatFact](https://apis.io/schemas/cat-facts-catfact/cat-facts-catfact-cat-fact/)
- [CatFactList](https://apis.io/schemas/cat-facts-catfact/cat-facts-catfact-cat-fact-list/)
- [PaginationLink](https://apis.io/schemas/cat-facts-catfact/cat-facts-catfact-pagination-link/)

#### JSON Structure (5)

Data models expressed in JSON Structure.

- [Cat Facts Catfact Breed List Structure](https://apis.io/json-structure/cat-facts-catfact/cat-facts-catfact-breed-list-structure/)
- [Cat Facts Catfact Breed Structure](https://apis.io/json-structure/cat-facts-catfact/cat-facts-catfact-breed-structure/)
- [Cat Facts Catfact Cat Fact List Structure](https://apis.io/json-structure/cat-facts-catfact/cat-facts-catfact-cat-fact-list-structure/)
- [Cat Facts Catfact Cat Fact Structure](https://apis.io/json-structure/cat-facts-catfact/cat-facts-catfact-cat-fact-structure/)
- [Cat Facts Catfact Pagination Link Structure](https://apis.io/json-structure/cat-facts-catfact/cat-facts-catfact-pagination-link-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cat Facts Catfact Context](https://apis.io/jsonld/cat-facts-catfact/cat-facts-catfact-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cat Facts Catfact Vocabulary](https://apis.io/vocabularies/cat-facts-catfact/cat-facts-catfact-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Cat Facts Catfact Breed Example](https://apis.io/examples/cat-facts-catfact/cat-facts-catfact-breed-example/)
- [Cat Facts Catfact Breed List Example](https://apis.io/examples/cat-facts-catfact/cat-facts-catfact-breed-list-example/)
- [Cat Facts Catfact Cat Fact Example](https://apis.io/examples/cat-facts-catfact/cat-facts-catfact-cat-fact-example/)
- [Cat Facts Catfact Cat Fact List Example](https://apis.io/examples/cat-facts-catfact/cat-facts-catfact-cat-fact-list-example/)
- [Cat Facts Catfact Pagination Link Example](https://apis.io/examples/cat-facts-catfact/cat-facts-catfact-pagination-link-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [Cat Facts API](https://apis.io/collections/cat-facts-catfact/open-cat-facts-catfact/)
- [Cat Facts Breeds API](https://apis.io/collections/cat-facts-catfact/open-cat-facts-catfact-breeds-api/)
- [Cat Breeds Facts API](https://apis.io/collections/cat-facts-catfact/open-cat-facts-catfact-facts-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cat Facts (catfact.ninja) — jsonschema rules](https://apis.io/rules/cat-facts-catfact/cat-facts-catfact-jsonschema-spectral-rules/)
- [Cat Facts (catfact.ninja) API Rules](https://apis.io/rules/cat-facts-catfact/cat-facts-catfact-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cat Facts Catfact Domain Security](https://apis.io/security/cat-facts-catfact/cat-facts-catfact-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://catfact.ninja/)

## API Evangelist rating

**Kin Score 19.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 20.9 |
| Contract governance | 27.3 |
| Operational transparency | 0.0 |
| Developer ergonomics | 21.4 |
| Access clarity | 0.0 |

**Agent readiness 25.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cat-facts-catfact/](https://apis.io/providers/cat-facts-catfact/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cat Facts (catfact.ninja): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cat-facts-catfact/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
