# Cat Facts (catfact.ninja) (cat-facts-catfact)

Cat Facts is a free, no-authentication community REST API at catfact.ninja that serves random cat trivia and a catalog of cat breeds. It exposes three documented endpoints — a single random fact, a paginated list of facts, and a paginated list of breeds — and ships a Swagger UI based OpenAPI 3.0 document at /docs. The service is widely used in API onboarding tutorials, demos, and sample apps because it requires no API key and returns small, predictable JSON payloads.

**URL:** [Visit APIs.json URL](https://catfact.ninja/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Animals, Cats, Trivia, Public APIs, Community, No Authentication, REST

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Cat Facts API

REST API exposing random cat trivia and a catalog of cat breeds. Three GET endpoints — /fact (a single random fact), /facts (paginated list of facts) and /breeds (paginated list of breeds) — return Laravel-style paginated JSON for the list endpoints.

**Human URL:** [https://catfact.ninja/](https://catfact.ninja/)

#### Tags:

 - Animals, Cats, Trivia, Public APIs

#### Properties

- [Documentation](https://catfact.ninja/)
- [SwaggerUI](https://catfact.ninja/)
- [OpenAPI](openapi/cat-facts-catfact-openapi.yml)
- [OpenAPISource](https://catfact.ninja/docs?api-docs.json)
- [NaftikoCapability](capabilities/cat-facts-catfact-facts.yaml)
- [NaftikoCapability](capabilities/cat-facts-catfact-breeds.yaml)

## Common Properties

- [Website](https://catfact.ninja/)
- [SwaggerUI](https://catfact.ninja/)
- [OpenAPI](https://catfact.ninja/docs?api-docs.json)
- [ContactEmail](mailto:contact@catfact.ninja)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Authentication — No Authentication Required](https://catfact.ninja/)
- [Tools — MCP Server (Community — cursethevulgar)](https://github.com/cursethevulgar/catfact-mcp-server)
- [Tools — MCP Server (Community — mtrmarko)](https://github.com/mtrmarko/cat-facts-mcp)
- [Tools — MCP Server (Community — Volspan)](https://github.com/volspan-deployments/cat-facts-mcp)
- [SpectralRules](rules/cat-facts-catfact-rules.yml)
- [Vocabulary](vocabulary/cat-facts-catfact-vocabulary.yml)
- [JSONLDContext](json-ld/cat-facts-catfact-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Free and Open | No API key, no signup, no quota header. Anyone can hit catfact.ninja and start getting JSON back. Ideal for first-class onboarding examples in tutorials and SDK quickstarts. |
| Paginated Listings | The /facts and /breeds endpoints return Laravel-style paginated responses with current_page, last_page, per_page, total, and a links array suitable for "next/prev" UI patterns. |
| Length-Filtered Facts | Both /fact and /facts accept a max_length query parameter, letting clients restrict trivia length for SMS-friendly, push-notification-friendly, or banner use cases. |
| Self-Describing OpenAPI | A live OpenAPI 3.0 document is published at /docs?api-docs.json and rendered as Swagger UI at /docs — usable directly by codegen tools, Postman import, and AI agent toolkits. |

## Use Cases

| Name | Description |
|------|-------------|
| API Onboarding Tutorials | Used in countless "hello-world" REST tutorials because it returns small JSON, requires no auth, and is CORS-friendly. A canonical first call for browsers, mobile apps, and SDKs. |
| SMS and Chatbot Daily Facts | The original Cat Facts service became a meme around texting friends a daily cat fact. catfact.ninja is the easiest backend for any "daily fact" bot, including SMS, Discord, and Slack integrations. |
| Load Testing and Demo Apps | Engineering teams point load generators, screen-recording demos, and observability sample apps at catfact.ninja because it tolerates traffic, returns tiny payloads, and never requires credential rotation. |
| MCP and Agent Tool Demos | Several community Model Context Protocol servers wrap catfact.ninja as a "hello world" tool because the surface is small, safe, and read-only — perfect for showing Claude using a tool. |

## Integrations

| Name | Description |
|------|-------------|
| Public APIs Index | Listed in the popular public-apis/public-apis index as a free, no-auth Animals API. |
| Community MCP Servers | At least three community-built MCP servers wrap the catfact.ninja endpoints as Claude tools. |
| Swagger UI | Ships a live Swagger UI at https://catfact.ninja/ that imports the OpenAPI spec from /docs. |

## Solutions

| Name | Description |
|------|-------------|
| Lowest-Friction Demo API | When you need a public, free, no-auth REST API to demo SDK generation, OpenAPI tooling, mock servers, or agent tool calls, catfact.ninja is the smallest acceptable surface area. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Cat Facts API](openapi/cat-facts-catfact-openapi.yml)

### JSON Schema

- [Breed](json-schema/cat-facts-catfact-breed-schema.json)
- [BreedList](json-schema/cat-facts-catfact-breed-list-schema.json)
- [CatFact](json-schema/cat-facts-catfact-cat-fact-schema.json)
- [CatFactList](json-schema/cat-facts-catfact-cat-fact-list-schema.json)
- [PaginationLink](json-schema/cat-facts-catfact-pagination-link-schema.json)

### JSON Structure

- [Breed](json-structure/cat-facts-catfact-breed-structure.json)
- [BreedList](json-structure/cat-facts-catfact-breed-list-structure.json)
- [CatFact](json-structure/cat-facts-catfact-cat-fact-structure.json)
- [CatFactList](json-structure/cat-facts-catfact-cat-fact-list-structure.json)
- [PaginationLink](json-structure/cat-facts-catfact-pagination-link-structure.json)

### JSON-LD

- [Cat Facts Context](json-ld/cat-facts-catfact-context.jsonld)

### Examples

- [Breed](examples/cat-facts-catfact-breed-example.json)
- [BreedList](examples/cat-facts-catfact-breed-list-example.json)
- [CatFact](examples/cat-facts-catfact-cat-fact-example.json)
- [CatFactList](examples/cat-facts-catfact-cat-fact-list-example.json)
- [PaginationLink](examples/cat-facts-catfact-pagination-link-example.json)

## Capabilities

Naftiko capabilities organized as one self-contained file per OpenAPI tag, each exposing both REST and MCP adapters.

### Cat Facts API

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cat Facts API — Facts](capabilities/cat-facts-catfact-facts.yaml) | Cat Facts API | 2 | Tutorial Author, Demo Builder |
| [Cat Facts API — Breeds](capabilities/cat-facts-catfact-breeds.yaml) | Cat Facts API | 1 | Tutorial Author, Content Author |

## Vocabulary

- [Cat Facts Vocabulary](vocabulary/cat-facts-catfact-vocabulary.yml) — Unified taxonomy mapping 3 resources, 2 actions, 2 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Cat Facts Spectral Rules](rules/cat-facts-catfact-rules.yml) — 33 rules across 11 categories enforcing Cat Facts API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
