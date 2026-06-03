# Nutritionix (nutritionix)

Nutritionix operates the world's largest verified nutrition database, exposing a Track API (v2) that converts natural-language food and exercise descriptions into full nutrient analysis, and powers food search, branded item lookup, and restaurant menu data for diet, fitness, and health applications.

**URL:** [Visit APIs.json URL](https://developer.nutritionix.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Health, Nutrition, Food, Fitness, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-06-03

## APIs

### Nutritionix Track API v2

REST API for translating plain-text food and exercise descriptions into detailed nutrient and calorie analysis, searching the verified nutrition database, and looking up branded and restaurant menu items. Base URL: https://trackapi.nutritionix.com/v2.

**Human URL:** [https://developer.nutritionix.com/docs/v2](https://developer.nutritionix.com/docs/v2)

#### Tags:

 - Health, Nutrition, Food, Fitness

#### Properties

- [OpenAPI](openapi/nutritionix-track-openapi.yml)
- [Documentation](https://developer.nutritionix.com/docs/v2)
- [APIReference](https://docx.syndigo.com/developers/docs/nutritionix-api-guide)
- [Authentication](https://docx.syndigo.com/developers/docs/authentication)
- [Node.js SDK](https://github.com/nutritionix/nodejs-client-library)
- [Python SDK](https://github.com/nutritionix/library-python)
- [PHP SDK](https://github.com/nutritionix/api-library-php)
- [Ruby on Rails SDK](https://github.com/nutritionix/api-library-ror)
- [Angular Client](https://github.com/nutritionix/track-api-angular-client)

This API also carries 4 Naftiko capability references, 15 JSON Schema references, 15 JSON Structure references, and 15 example references (see the Artifacts and Capabilities sections below).

## Common Properties

- [Website](https://www.nutritionix.com/)
- [DeveloperPortal](https://developer.nutritionix.com/)
- [Documentation](https://developer.nutritionix.com/docs/v2)
- [SignUp](https://developer.nutritionix.com/signup)
- [Pricing](https://www.nutritionix.com/api)
- [GitHubOrganization](https://github.com/nutritionix)
- [API Documentation](https://github.com/nutritionix/api-documentation)
- [Node.js Client Library (npm)](https://www.npmjs.com/package/nutritionix)
- [Nutrition Label Component](https://github.com/nutritionix/nutrition-label)
- [Vue Nutrition Label Component](https://github.com/nutritionix/vue-nutrition-label)
- [API Data Utilities](https://github.com/nutritionix/nutritionix-api-data-utilities)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [SpectralRules](rules/nutritionix-rules.yml)
- [Vocabulary](vocabulary/nutritionix-vocabulary.yml)
- [JSON-LD](json-ld/nutritionix-track-context.jsonld)
- [Plans](plans/nutritionix-plans-pricing.yml)
- [RateLimits](rate-limits/nutritionix-rate-limits.yml)
- [FinOps](finops/nutritionix-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Natural Language Nutrition | Convert free-text meal descriptions into full nutrient breakdowns including calories, macros, and micronutrients. |
| Natural Language Exercise | Convert free-text activity descriptions into calorie-burn estimates personalized by gender, weight, height, and age. |
| Instant Food Search | Typeahead search returning matched common foods and branded foods for autocomplete experiences. |
| Branded & Restaurant Item Lookup | Retrieve detailed nutrition for branded grocery and restaurant menu items by nix_item_id or UPC. |
| Verified Nutrition Database | Access the world's largest verified nutrition database, including USDA NDB-linked common foods and over a million branded items. |

## Use Cases

| Name | Description |
|------|-------------|
| Diet & Calorie Tracking | Power food logging and calorie-counting apps with natural-language meal entry. |
| Fitness & Activity Tracking | Estimate calories burned from logged workouts and activities. |
| Restaurant Menu Nutrition | Surface accurate nutrition facts for restaurant and chain menu items. |
| Nutrition Label Rendering | Generate FDA-style nutrition labels from API nutrient data. |

## Integrations

| Name | Description |
|------|-------------|
| USDA NDB | Common-food results are linked to USDA National Nutrient Database (NDB) numbers and nutrient attribute IDs. |
| Syndigo / Riversand | Nutritionix is part of Syndigo; developer documentation is hosted on the Syndigo docs platform. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Nutritionix Track API v2](openapi/nutritionix-track-openapi.yml) — 6 operations across Natural Language, Search, Item, and Brands.

### JSON Schema

15 schema files in [`json-schema/`](json-schema/) covering Food, FullNutrient, AltMeasure, Photo, CommonFood, BrandedFood, Exercise, Brand, the natural-language request/response models, and the search/item/brand response envelopes.

### JSON Structure

15 [`json-structure/`](json-structure/) files mirroring the JSON Schemas in the json-structure.org type system.

### JSON-LD

- [Nutritionix Track Context](json-ld/nutritionix-track-context.jsonld) — linked-data context mapping Track API properties to schema.org and a Nutritionix namespace.

### Examples

15 example payloads in [`examples/`](examples/), one per JSON Schema.

## Capabilities

Naftiko capabilities, one self-contained file per business surface (OpenAPI tag), each exposing both a REST and an MCP adapter.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Natural Language](capabilities/track-natural-language.yaml) | Track | 2 | App Developer, Fitness App |
| [Search](capabilities/track-search.yaml) | Track | 1 | App Developer |
| [Item](capabilities/track-item.yaml) | Track | 2 | App Developer, Retail Integrator |
| [Brands](capabilities/track-brands.yaml) | Track | 1 | App Developer |

## Vocabulary

- [Nutritionix Vocabulary](vocabulary/nutritionix-vocabulary.yml) — Unified taxonomy mapping 5 resources, 3 actions, 4 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Nutritionix Rules](rules/nutritionix-rules.yml) — 33 Spectral rules across info, servers, paths, operations, tags, parameters, responses, schemas, security, and HTTP method categories enforcing Nutritionix API conventions.

## Plans, Rate Limits & FinOps

- [Plans](plans/nutritionix-plans-pricing.yml) — API Commons Plans 0.1 (tiered annual subscription; figures unreconciled pending a live quote).
- [Rate Limits](rate-limits/nutritionix-rate-limits.yml) — API Commons Rate Limits 0.1 (per-credential daily quota; numbers unpublished).
- [FinOps](finops/nutritionix-finops.yml) — FOCUS-aligned FinOps 1.0 (tiered subscription billing, per-request meters).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
