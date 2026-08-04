# Cat Facts (catfact.ninja) (cat-facts-catfact)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cat Facts is a free, no-authentication community REST API at catfact.ninja that serves random cat trivia and a catalog of cat breeds. It exposes three documented endpoints — a single random fact, a paginated list of facts, and a paginated list of breeds — and ships a Swagger UI based OpenAPI 3.0 document at /docs. The service is widely used in API onboarding tutorials, demos, and sample apps because it requires no API key and returns small, predictable JSON payloads.

**APIs.json:** [https://catfact.ninja/](https://catfact.ninja/)

## Tags

- Animals
- Cats
- Trivia
- Public APIs
- Community
- No Authentication
- REST

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Cat Facts API

REST API exposing random cat trivia and a catalog of cat breeds. Three GET endpoints — /fact (a single random fact), /facts (paginated list of facts) and /breeds (paginated list of breeds) — return Laravel-style paginated JSON for the list endpoints.

- **Human URL:** [https://catfact.ninja/](https://catfact.ninja/)
- **Base URL:** `https://catfact.ninja`

#### Tags

- Animals
- Cats
- Trivia
- Public APIs

#### Properties

- [Documentation](https://catfact.ninja/)
- [Swagger U I](https://catfact.ninja/)
- [OpenAPI](openapi/cat-facts-catfact-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cat-facts-catfact.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cat-facts-catfact.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Source](https://catfact.ninja/docs?api-docs.json)

## Common Properties

- [Website](https://catfact.ninja/)
- [Swagger U I](https://catfact.ninja/)
- [OpenAPI](https://catfact.ninja/docs?api-docs.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Contact Email](mailto:contact@catfact.ninja)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Authentication](https://catfact.ninja/)
- [Tools](https://github.com/cursethevulgar/catfact-mcp-server)
- [Tools](https://github.com/mtrmarko/cat-facts-mcp)
- [Tools](https://github.com/volspan-deployments/cat-facts-mcp)
- [Spectral Rules](rules/cat-facts-catfact-rules.yml)
- [Vocabulary](vocabulary/cat-facts-catfact-vocabulary.yml)
- [J S O N L D Context](json-ld/cat-facts-catfact-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
