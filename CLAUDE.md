# Personal Projects Workspace

This is a personal workspace containing multiple projects and vacation/travel planning.

## Structure

- `_vacations/` — travel planning (itineraries, budgets, accommodation research)
- `_ideas/` — project ideas
- `_building/` — projects in progress
- Other top-level directories — individual projects (cookember, ellohell, growwell, etc.)

## Current focus: Summer 2026 trip

Planning a 5-week family road trip (June 13 – July 18) across the Balkans and Central Europe.
- 2 adults + 3 kids (ages 2, 8, 11), traveling by car
- 12 stops: Romania → Bulgaria → Greece → Albania → Montenegro → Croatia → Slovenia → Austria → Poland → Ukraine
- Trip details in `_vacations/2026/summer/`
- Language: planning docs are in Ukrainian

## MCP servers

### Airbnb (`@openbnb/mcp-server-airbnb`)
Use for: searching and comparing accommodation listings across all trip destinations.
- Search by location, dates, guests (2 adults + 3 children)
- Get listing details, pricing, amenities
- Primary tool for finding family-friendly stays with enough space for 5 people

### Chrome DevTools (`chrome-devtools-mcp`)
Use for: browsing Booking.com and Expedia in Chrome to search and compare hotels, apartments, and deals.
- Open Booking.com or Expedia in Chrome, then use this MCP to interact with the pages
- Use when Airbnb doesn't have good options for a destination, or to compare prices
- Also useful for researching excursions, restaurants, and other travel info

### When to use which
- **Accommodation search** → start with Airbnb MCP for direct search, fall back to Chrome DevTools for Booking.com/Expedia
- **Price comparison** → use Chrome DevTools to check Booking.com/Expedia alongside Airbnb results
- **Excursions, restaurants, general research** → use Chrome DevTools to browse relevant sites
