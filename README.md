# Nutritionix (nutritionix)

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

Nutritionix operates the world's largest verified nutrition database, exposing a Track API (v2) that converts natural-language food and exercise descriptions into full nutrient analysis, and powers food search, branded item lookup, and restaurant menu data for diet, fitness, and health applications.

**APIs.json:** [https://developer.nutritionix.com/](https://developer.nutritionix.com/)

## Tags

- Restaurant
- Health
- Nutrition
- Food
- Fitness
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-06-03

## APIs

### Nutritionix Track API v2

REST API for translating plain-text food and exercise descriptions into detailed nutrient and calorie analysis, searching the verified nutrition database, and looking up branded and restaurant menu items. Base URL: https://trackapi.nutritionix.com/v2.

- **Human URL:** [https://developer.nutritionix.com/docs/v2](https://developer.nutritionix.com/docs/v2)
- **Base URL:** `https://trackapi.nutritionix.com/v2`

#### Tags

- Health
- Nutrition
- Food
- Fitness

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nutritionix/main/openapi/nutritionix-track-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developer.nutritionix.com/docs/v2)
- [API Reference](https://docx.syndigo.com/developers/docs/nutritionix-api-guide)
- [Authentication](https://docx.syndigo.com/developers/docs/authentication)
- [SDK](https://github.com/nutritionix/nodejs-client-library)
- [SDK](https://github.com/nutritionix/library-python)
- [SDK](https://github.com/nutritionix/api-library-php)
- [SDK](https://github.com/nutritionix/api-library-ror)
- [SDK](https://github.com/nutritionix/track-api-angular-client)
- [JSON Schema](json-schema/track-alt-measure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-brand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-brand-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-branded-food-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-common-food-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-exercise-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-food-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-foods-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-full-nutrient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-instant-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-natural-exercise-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-natural-exercise-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-natural-nutrients-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-natural-nutrients-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track-photo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/track-alt-measure-structure.json)
- [JSON Structure](json-structure/track-brand-search-response-structure.json)
- [JSON Structure](json-structure/track-brand-structure.json)
- [JSON Structure](json-structure/track-branded-food-structure.json)
- [JSON Structure](json-structure/track-common-food-structure.json)
- [JSON Structure](json-structure/track-exercise-structure.json)
- [JSON Structure](json-structure/track-food-structure.json)
- [JSON Structure](json-structure/track-foods-response-structure.json)
- [JSON Structure](json-structure/track-full-nutrient-structure.json)
- [JSON Structure](json-structure/track-instant-search-response-structure.json)
- [JSON Structure](json-structure/track-natural-exercise-request-structure.json)
- [JSON Structure](json-structure/track-natural-exercise-response-structure.json)
- [JSON Structure](json-structure/track-natural-nutrients-request-structure.json)
- [JSON Structure](json-structure/track-natural-nutrients-response-structure.json)
- [JSON Structure](json-structure/track-photo-structure.json)
- [Example](examples/track-alt-measure-example.json)
- [Example](examples/track-brand-example.json)
- [Example](examples/track-brand-search-response-example.json)
- [Example](examples/track-branded-food-example.json)
- [Example](examples/track-common-food-example.json)
- [Example](examples/track-exercise-example.json)
- [Example](examples/track-food-example.json)
- [Example](examples/track-foods-response-example.json)
- [Example](examples/track-full-nutrient-example.json)
- [Example](examples/track-instant-search-response-example.json)
- [Example](examples/track-natural-exercise-request-example.json)
- [Example](examples/track-natural-exercise-response-example.json)
- [Example](examples/track-natural-nutrients-request-example.json)
- [Example](examples/track-natural-nutrients-response-example.json)
- [Example](examples/track-photo-example.json)
- [Postman Collection](collections/nutritionix-track.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nutritionix-track.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.nutritionix.com/)
- [Developer Portal](https://developer.nutritionix.com/)
- [Documentation](https://developer.nutritionix.com/docs/v2)
- [Sign Up](https://developer.nutritionix.com/signup)
- [Pricing](https://www.nutritionix.com/api)
- [GitHub Organization](https://github.com/nutritionix)
- [GitHub Repository](https://github.com/nutritionix/api-documentation)
- [SDK](https://www.npmjs.com/package/nutritionix)
- [Tools](https://github.com/nutritionix/nutrition-label)
- [Tools](https://github.com/nutritionix/vue-nutrition-label)
- [Tools](https://github.com/nutritionix/nutritionix-api-data-utilities)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/nutritionix/main/rules/nutritionix-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/nutritionix/main/vocabulary/nutritionix-vocabulary.yml)
- [J S O N- L D](https://raw.githubusercontent.com/api-evangelist/nutritionix/main/json-ld/nutritionix-track-context.jsonld)
- [Plans](plans/nutritionix-plans-pricing.yml)
- [Rate Limits](rate-limits/nutritionix-rate-limits.yml)
- [Fin Ops](finops/nutritionix-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
