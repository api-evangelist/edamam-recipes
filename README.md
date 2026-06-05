# Edamam (edamam-recipes)

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
