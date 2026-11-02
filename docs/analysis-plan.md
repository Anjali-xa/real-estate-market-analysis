# Real Estate Market Analysis Plan

## Scope
Analyse listing prices, property characteristics, and geographic patterns. Treat asking prices as listings, not confirmed transaction prices, unless the source explicitly records sales.

## Core measures
- Median asking price by property type and location.
- Price per square foot or square metre, with the unit stated.
- Listing count and new listings by reporting period.
- Median days on market, if reliable listing dates exist.
- Distribution of bedrooms, bathrooms, and floor area.

## Data-quality checks
- Validate currency and floor-area units before comparisons.
- Flag zero or negative prices and implausible floor areas.
- Standardise location names while retaining original values.
- Identify duplicate listings using source IDs or documented matching rules.
- Check date order for listed, updated, and removed timestamps.
- Separate missing property attributes from true zero values.

## Analysis questions
1. Which areas have the highest median asking prices?
2. How does price per area vary by property type?
3. Are listing volumes seasonal?
4. Which property attributes are associated with higher asking prices?

## Limitations
Listing data may contain stale, duplicated, or selectively advertised properties. Avoid causal claims from descriptive comparisons.