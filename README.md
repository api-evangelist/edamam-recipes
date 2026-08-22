# Edamam (edamam-recipes)

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

Edamam is a food and nutrition data platform powering recipe search, NLP-based nutrition analysis, food database lookup (keyword / brand / UPC / AI Vision), and personalized meal planning. The flagship Recipe Search API v2 covers a 2M+ recipe index with 30+ filters across diet, health, cuisine, meal, dish, nutrients, time, glycemic index, and CO2 emissions class.

**APIs.json:** [https://www.edamam.com/](https://www.edamam.com/)

## Tags

- Food And Drink
- Recipes
- Nutrition
- Diet
- Allergens
- Meal Planning
- Sustainability
- Carbon Footprint
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Edamam Recipe Search API

Search and look up recipes from a 2M+ recipe index with 30+ filters (q, diet, health, cuisineType, mealType, dishType, calories, time, excluded, nutrients, glycemicIndex, random) plus per-recipe nutrient breakdowns and CO2 emissions class (A+ through G).

- **Human URL:** [https://developer.edamam.com/edamam-docs-recipe-api](https://developer.edamam.com/edamam-docs-recipe-api)
- **Base URL:** `https://api.edamam.com/api/recipes/v2`

#### Tags

- Recipes
- Food And Drink
- Search

#### Properties

- [Documentation](https://developer.edamam.com/edamam-docs-recipe-api)
- [API Reference](https://developer.edamam.com/edamam-docs-recipe-api)
- [OpenAPI](openapi/edamam-recipe-search-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edamam-recipe-search-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edamam-recipe-search-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/edamam-recipe-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/edamam-recipe-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/edamam-nutrient-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/edamam-recipe-structure.json)
- [Example](examples/recipe-search-search-recipe-example.json)
- [Example](examples/recipe-search-lookup-recipe-by-id-example.json)
- [Example](examples/recipe-search-lookup-recipes-by-uri-example.json)
- [Example](examples/recipe-search-shopping-list-example.json)
- [Authentication](https://developer.edamam.com/api/faq)
- [Rate Limits](rate-limits/edamam-recipes-rate-limits.yml)
- [Pricing](https://developer.edamam.com/edamam-recipe-api)

### Edamam Nutrition Analysis API

Natural-language nutrition analysis. Submit free-text ingredient lines or full recipes and receive computed energy, macronutrients, diet/health labels, and recipe classification (cuisine / meal / dish type).

- **Human URL:** [https://developer.edamam.com/edamam-docs-nutrition-api](https://developer.edamam.com/edamam-docs-nutrition-api)
- **Base URL:** `https://api.edamam.com/api/nutrition-details`

#### Tags

- Nutrition
- Food And Drink
- NLP

#### Properties

- [Documentation](https://developer.edamam.com/edamam-docs-nutrition-api)
- [OpenAPI](openapi/edamam-nutrition-analysis-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edamam-nutrition-analysis-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edamam-nutrition-analysis-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/nutrition-analysis-full-recipe-analysis-example.json)
- [Authentication](https://developer.edamam.com/api/faq)
- [Pricing](https://developer.edamam.com/edamam-nutrition-api)

### Edamam Food Database API

Look up nutrition data for foods by keyword, brand, UPC/EAN barcode, AI Vision photo analysis, or autocomplete. Returns per-100g nutrient values, allergen / health labels, and category classification (generic foods, packaged foods, generic meals, fast foods).

- **Human URL:** [https://developer.edamam.com/food-database-api-docs](https://developer.edamam.com/food-database-api-docs)
- **Base URL:** `https://api.edamam.com/api/food-database/v2`

#### Tags

- Food And Drink
- Nutrition
- UPC
- AI Vision

#### Properties

- [Documentation](https://developer.edamam.com/food-database-api-docs)
- [OpenAPI](openapi/edamam-food-database-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edamam-food-database-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edamam-food-database-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/edamam-food-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/edamam-food-structure.json)
- [Example](examples/food-database-food-search-example.json)
- [Authentication](https://developer.edamam.com/api/faq)
- [Pricing](https://developer.edamam.com/food-database-api)

### Edamam Meal Planner API

Generate personalized meal plans (up to 14 days) with daily structure of sections and slots, fit to nutritional ranges and diet/health constraints. Includes DRI calculation, recipe lookup, shopping list aggregation, and (Enterprise) Instacart integration.

- **Human URL:** [https://developer.edamam.com/meal-planner-api](https://developer.edamam.com/meal-planner-api)
- **Base URL:** `https://api.edamam.com/api/meal-planner/v1`

#### Tags

- Meal Planning
- Food And Drink
- Nutrition

#### Properties

- [Documentation](https://developer.edamam.com/meal-planner-api)
- [OpenAPI](openapi/edamam-meal-planner-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edamam-meal-planner-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edamam-meal-planner-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/edamam-meal-plan-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/edamam-meal-plan-structure.json)
- [Example](examples/meal-planner-create-plan-example.json)
- [Authentication](https://developer.edamam.com/api/faq)
- [Pricing](https://developer.edamam.com/meal-planner-api)

## Common Properties

- [Website](https://www.edamam.com/)
- [Developer Portal](https://developer.edamam.com/)
- [Documentation](https://developer.edamam.com/)
- [Sign Up](https://developer.edamam.com/admin/applications/new)
- [Login](https://developer.edamam.com/admin)
- [F A Q](https://developer.edamam.com/api/faq)
- [Support](https://developer.edamam.com/support)
- [Terms of Service](https://www.edamam.com/page/api-terms-and-conditions)
- [Privacy Policy](https://www.edamam.com/page/privacy-policy)
- [Plans](plans/edamam-recipes-plans-pricing.yml)
- [Rate Limits](rate-limits/edamam-recipes-rate-limits.yml)
- [Spectral Rules](rules/edamam-recipes-rules.yml)
- [Vocabulary](vocabulary/edamam-recipes-vocabulary.yml)
- [JSON-LD](json-ld/edamam-recipes-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [GitHub Organization](https://github.com/edamam-llc)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [Tools](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
