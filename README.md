# Edamam (edamam-recipes)

Edamam is a food and nutrition data platform powering recipe search, NLP-based nutrition analysis, food database lookup (keyword / brand / UPC / AI Vision), and personalized meal planning. The flagship Recipe Search API v2 covers a 2M+ recipe index with 30+ filters across diet, health, cuisine, meal, dish, nutrients, time, glycemic index, and CO2 emissions class.

**Website:** https://www.edamam.com/
**Developer Portal:** https://developer.edamam.com/
**Base URL:** https://api.edamam.com
**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** company
- **x-tier:** 3 (bulk-registered from public-apis, enriched 2026-05-30)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Food & Drink

## APIs

### Edamam Recipe Search API
Search and look up recipes from a 2M+ recipe index with 30+ filters and rich nutrient + CO2e data.
- [Documentation](https://developer.edamam.com/edamam-docs-recipe-api)
- [OpenAPI](openapi/edamam-recipe-search-v2-openapi.yml)
- JSON Schemas: [recipe](json-schema/edamam-recipe-schema.json), [search response](json-schema/edamam-recipe-search-response-schema.json), [nutrient info](json-schema/edamam-nutrient-info-schema.json)
- JSON Structure: [recipe](json-structure/edamam-recipe-structure.json)
- Examples: [search](examples/recipe-search-search-recipe-example.json), [lookup by id](examples/recipe-search-lookup-recipe-by-id-example.json), [lookup by uri](examples/recipe-search-lookup-recipes-by-uri-example.json), [shopping list](examples/recipe-search-shopping-list-example.json)
- Naftiko Capabilities: [Recipe Search](capabilities/recipe-search-recipe-search.yaml), [Shopping List](capabilities/recipe-search-shopping-list.yaml)

### Edamam Nutrition Analysis API
NLP-driven nutrient analysis for full recipes or single ingredient text lines.
- [Documentation](https://developer.edamam.com/edamam-docs-nutrition-api)
- [OpenAPI](openapi/edamam-nutrition-analysis-v1-openapi.yml)
- Example: [full recipe analysis](examples/nutrition-analysis-full-recipe-analysis-example.json)
- Naftiko Capability: [Nutrition](capabilities/nutrition-analysis-nutrition.yaml)

### Edamam Food Database API
Food parsing by keyword, brand, UPC/EAN, AI Vision photo recognition, and autocomplete.
- [Documentation](https://developer.edamam.com/food-database-api-docs)
- [OpenAPI](openapi/edamam-food-database-v2-openapi.yml)
- JSON Schema: [food](json-schema/edamam-food-schema.json)
- JSON Structure: [food](json-structure/edamam-food-structure.json)
- Example: [food search](examples/food-database-food-search-example.json)
- Naftiko Capability: [Food Database](capabilities/food-database-food-database.yaml)

### Edamam Meal Planner API
Personalized meal plans (up to 14 days), DRI calculation, shopping list aggregation, Instacart integration.
- [Documentation](https://developer.edamam.com/meal-planner-api)
- [OpenAPI](openapi/edamam-meal-planner-v1-openapi.yml)
- JSON Schema: [meal plan](json-schema/edamam-meal-plan-schema.json)
- JSON Structure: [meal plan](json-structure/edamam-meal-plan-structure.json)
- Example: [create meal plan](examples/meal-planner-create-plan-example.json)
- Naftiko Capability: [Meal Planner](capabilities/meal-planner-meal-planner.yaml)

## Shared Artifacts

| Artifact | Path |
|---|---|
| Plans & Pricing | [plans/edamam-recipes-plans-pricing.yml](plans/edamam-recipes-plans-pricing.yml) |
| Rate Limits | [rate-limits/edamam-recipes-rate-limits.yml](rate-limits/edamam-recipes-rate-limits.yml) |
| FinOps | [finops/edamam-recipes-finops.yml](finops/edamam-recipes-finops.yml) |
| Spectral Rules | [rules/edamam-recipes-rules.yml](rules/edamam-recipes-rules.yml) |
| Vocabulary | [vocabulary/edamam-recipes-vocabulary.yml](vocabulary/edamam-recipes-vocabulary.yml) |
| JSON-LD Context | [json-ld/edamam-recipes-context.jsonld](json-ld/edamam-recipes-context.jsonld) |

## MCP Server (Anthropic / LLM Tooling)

Edamam ships an official MCP server for the Food Database API.

- **Endpoint:** `https://mcp.edamam.com/mcp/food`
- **Source:** [edamam-llc/mcp-edamam-food](https://github.com/edamam-llc/mcp-edamam-food)
- **Install in Claude Code:**
  ```
  claude mcp add --transport http edamam-food \
    https://mcp.edamam.com/mcp/food \
    --header "Authorization: Bearer <app_id>:<app_key>"
  ```
- **Tools:** `get_food_nutrition`, `analyze_food_image`

## Pricing Snapshot

| API | Plan | Price | Quota |
|---|---|---|---|
| Recipe Search | Enterprise Basic | $9/mo | 10K calls/mo, 10/min |
| Recipe Search | Enterprise Core | $99/mo | 500K calls/mo, 100/min |
| Recipe Search | Enterprise Plus | $399/mo | 1M calls/mo, 300/min |
| Recipe Search | Enterprise Unlimited | Custom | Unlimited |
| Food Database | Basic Vision | $14/mo | 100K calls + 500 Vision |
| Food Database | Core | $69/mo | 750K calls, PAYG Vision |
| Food Database | Plus | $299/mo | 5M calls + 10K Vision |
| Meal Planner | Developer | Free | 10 MAU, 20 meal-plan calls/day |
| Meal Planner | Enterprise Core | $300/mo | 1K MAU, 30 meal-plan calls/day |

See [plans/edamam-recipes-plans-pricing.yml](plans/edamam-recipes-plans-pricing.yml) for full plan details.

## Tags
Food And Drink, Recipes, Nutrition, Diet, Allergens, Meal Planning, Sustainability, Carbon Footprint, Public APIs

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers
- **Kin Lane** — kin@apievangelist.com
