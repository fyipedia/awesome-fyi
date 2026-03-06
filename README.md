# Awesome FYI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source tools, packages, and resources from the [FYIPedia](https://github.com/fyipedia) ecosystem.

FYIPedia builds developer-friendly data packages and reference websites across domains like color science, Unicode, typography, emoji, distance calculation, timezones, unit conversion, beverages, and more. With 20 Python packages, 10 npm packages, and 70+ REST API endpoints, every package ships structured data with zero external dependencies. Available as Python packages, npm packages, CLI tools, MCP servers for AI assistants, and API client libraries.

## Contents

- [Python Packages](#python-packages)
  - [Data Packages](#data-packages)
  - [Infrastructure](#infrastructure)
  - [API Client Packages](#api-client-packages)
- [npm Packages](#npm-packages)
- [CLI Tools](#cli-tools)
- [MCP Servers](#mcp-servers)
- [Websites](#websites)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)

## Python Packages

All packages are available on [PyPI](https://pypi.org/) with zero required dependencies. Install with `pip install <package>`.

### Data Packages

- [colorfyi](https://github.com/fyipedia/colorfyi) - Color conversion (7 spaces), WCAG contrast, harmony generation, color blindness simulation, Tailwind shades, and 809 named colors.
- [emojifyi](https://github.com/fyipedia/emojifyi) - 3,953 emoji metadata with 8 encoding formats including UTF-8, HTML entities, and CLDR names.
- [symbolfyi](https://github.com/fyipedia/symbolfyi) - Symbol encoding in 11 formats with full Unicode property lookups.
- [unicodefyi](https://github.com/fyipedia/unicodefyi) - Unicode character information with 17 encoding formats and 90 HTML entity mappings.
- [fontfyi](https://github.com/fyipedia/fontfyi) - Metadata for 50 Google Fonts including CSS snippets, font pairings, and classification.
- [distancefyi](https://github.com/fyipedia/distancefyi) - Haversine distance, bearing, midpoint, and travel time calculations between any two coordinates.
- [timefyi](https://github.com/fyipedia/timefyi) - Timezone operations, UTC offsets, DST detection, time conversion, business hours overlap, and sunrise/sunset.
- [namefyi](https://github.com/fyipedia/namefyi) - Korean Revised Romanization, Five Elements classification, CJK stroke counting, and population formatting.
- [unitfyi](https://github.com/fyipedia/unitfyi) - Unit conversion engine with 220 units across 20 measurement categories, Decimal precision.
- [holidayfyi](https://github.com/fyipedia/holidayfyi) - Public holidays for 100+ countries, Easter date calculation (Western and Orthodox), and date utilities.

### Infrastructure

- [fyipedia](https://github.com/fyipedia/fyipedia) - Unified CLI aggregating all 10 data packages into a single `fyi` command with lazy plugin loading.
- [fyipedia-mcp](https://github.com/fyipedia/fyipedia-mcp) - Unified MCP hub server exposing 53 tools from all 10 packages for AI assistants.

### API Client Packages

Typed Python clients for FYIPedia beverage REST APIs. Each package wraps a free, public JSON API with Pydantic models and async support.

- [cocktailfyi](https://github.com/fyipedia/cocktailfyi) - 636 cocktail recipes with ABV, calories, flavor profiles, and techniques. API client for [CocktailFYI](https://cocktailfyi.com).
- [vinofyi](https://github.com/fyipedia/vinofyi) - Wine varieties, grapes, regions, and wineries with food pairings. API client for [VinoFYI](https://vinofyi.com).
- [beerfyi](https://github.com/fyipedia/beerfyi) - 112 beer styles, 82 hops, 41 malts, 29 yeast strains with BJCP guidelines. API client for [BeerFYI](https://beerfyi.com).
- [brewfyi](https://github.com/fyipedia/brewfyi) - 72 coffee varieties, 21 brew methods, and roasting profiles. API client for [BrewFYI](https://brewfyi.com).
- [whiskeyfyi](https://github.com/fyipedia/whiskeyfyi) - 80 whiskey expressions, distilleries, and tasting notes. API client for [WhiskeyFYI](https://whiskeyfyi.com).
- [teafyi](https://github.com/fyipedia/teafyi) - 60 tea varieties, teaware, and brewing guides. API client for [TeaFYI](https://teafyi.com).
- [nihonshufyi](https://github.com/fyipedia/nihonshufyi) - 80 sake grades, rice varieties, and 50 breweries. API client for [NihonshuFYI](https://nihonshufyi.com).
- [drinkfyi](https://github.com/fyipedia/drinkfyi) - Unified beverage API hub aggregating all 7 beverage sites. API client for [DrinkFYI](https://drinkfyi.com).

## npm Packages

All packages are available on [npm](https://www.npmjs.com/) as pure TypeScript with zero runtime dependencies. Works in Node.js, Deno, Bun, and browsers (ESM).

- [colorfyi](https://github.com/fyipedia/colorfyi-js) - Color conversion (7 spaces), WCAG contrast, harmonies, shades, color blindness simulation for JavaScript/TypeScript.
- [emojifyi](https://github.com/fyipedia/emojifyi-js) - 3,953 emoji metadata and 8 encoding utilities for Node.js and browsers.
- [symbolfyi](https://github.com/fyipedia/symbolfyi-js) - Symbol encoding (11 formats) and Unicode property lookups for JavaScript.
- [unicodefyi](https://github.com/fyipedia/unicodefyi-js) - Unicode character data with 17 encoding formats for JavaScript environments.
- [fontfyi](https://github.com/fyipedia/fontfyi-js) - Google Fonts metadata, CSS generation, and font pairing recommendations for frontend projects.
- [distancefyi](https://github.com/fyipedia/distancefyi-js) - Haversine distance, bearing, midpoint, and travel time calculations for JavaScript/TypeScript.
- [timefyi](https://github.com/fyipedia/timefyi-js) - Timezone operations, time conversion, and DST detection for JavaScript/TypeScript.
- [namefyi](https://github.com/fyipedia/namefyi-js) - Korean romanization, Five Elements, and CJK utilities for JavaScript/TypeScript.
- [unitfyi](https://github.com/fyipedia/unitfyi-js) - Unit conversion (220 units, 20 categories) with high precision for JavaScript/TypeScript.
- [holidayfyi](https://github.com/fyipedia/holidayfyi-js) - Holiday dates, Easter calculation, and date utilities for JavaScript/TypeScript.

## CLI Tools

- [fyipedia](https://github.com/fyipedia/fyipedia) - Unified CLI for all 10 FYIPedia tools. Install with `pip install "fyipedia[all]"`, then use `fyi color info FF6B35`, `fyi distance calc`, `fyi unit convert`, etc.
- [colorfyi CLI](https://github.com/fyipedia/colorfyi) - Standalone color CLI. Install with `pip install "colorfyi[cli]"`.
- [emojifyi CLI](https://github.com/fyipedia/emojifyi) - Standalone emoji CLI. Install with `pip install "emojifyi[cli]"`.
- [symbolfyi CLI](https://github.com/fyipedia/symbolfyi) - Standalone symbol CLI. Install with `pip install "symbolfyi[cli]"`.
- [unicodefyi CLI](https://github.com/fyipedia/unicodefyi) - Standalone Unicode CLI. Install with `pip install "unicodefyi[cli]"`.
- [fontfyi CLI](https://github.com/fyipedia/fontfyi) - Standalone font CLI. Install with `pip install "fontfyi[cli]"`.
- [distancefyi CLI](https://github.com/fyipedia/distancefyi) - Standalone distance CLI. Install with `pip install "distancefyi[cli]"`.
- [timefyi CLI](https://github.com/fyipedia/timefyi) - Standalone time CLI. Install with `pip install "timefyi[cli]"`.
- [namefyi CLI](https://github.com/fyipedia/namefyi) - Standalone name CLI. Install with `pip install "namefyi[cli]"`.
- [unitfyi CLI](https://github.com/fyipedia/unitfyi) - Standalone unit CLI. Install with `pip install "unitfyi[cli]"`.
- [holidayfyi CLI](https://github.com/fyipedia/holidayfyi) - Standalone holiday CLI. Install with `pip install "holidayfyi[cli]"`.

## MCP Servers

[Model Context Protocol](https://modelcontextprotocol.io/) servers for AI assistant integration. Works with Claude Desktop, Cursor, Windsurf, Continue, and any MCP-compatible client.

- [fyipedia-mcp](https://github.com/fyipedia/fyipedia-mcp) - **Unified hub server** with 53 tools from all 10 packages. Install with `pip install "fyipedia-mcp[all]"`.
- [colorfyi MCP](https://github.com/fyipedia/colorfyi) - 9 color tools (info, contrast, harmonies, shades, blindness, mix, compare, gradient, text color). Install with `pip install "colorfyi[mcp]"`.
- [emojifyi MCP](https://github.com/fyipedia/emojifyi) - 7 emoji tools (lookup, search, encode, categories, stats). Install with `pip install "emojifyi[mcp]"`.
- [symbolfyi MCP](https://github.com/fyipedia/symbolfyi) - 3 symbol tools (info, encode, HTML entity lookup). Install with `pip install "symbolfyi[mcp]"`.
- [unicodefyi MCP](https://github.com/fyipedia/unicodefyi) - 4 Unicode tools (info, encode, search, HTML entity). Install with `pip install "unicodefyi[mcp]"`.
- [fontfyi MCP](https://github.com/fyipedia/fontfyi) - 6 font tools (info, search, CSS, pairings, stacks, popular). Install with `pip install "fontfyi[mcp]"`.
- [distancefyi MCP](https://github.com/fyipedia/distancefyi) - 5 distance tools (calculate, bearing, midpoint, flight time, convert). Install with `pip install "distancefyi[mcp]"`.
- [timefyi MCP](https://github.com/fyipedia/timefyi) - 5 time tools (current, diff, convert, business hours, sun info). Install with `pip install "timefyi[mcp]"`.
- [namefyi MCP](https://github.com/fyipedia/namefyi) - 4 name tools (romanize, elements, compatibility, format). Install with `pip install "namefyi[mcp]"`.
- [unitfyi MCP](https://github.com/fyipedia/unitfyi) - 4 unit tools (convert, table, categories, list). Install with `pip install "unitfyi[mcp]"`.
- [holidayfyi MCP](https://github.com/fyipedia/holidayfyi) - 5 holiday tools (upcoming, check date, easter, nth weekday, countdown). Install with `pip install "holidayfyi[mcp]"`.

## Websites

Interactive reference websites powered by FYIPedia data packages. All sites are free, no login required.

- [ColorFYI](https://colorfyi.com) - Color encyclopedia with [converter](https://colorfyi.com/tools/converter/), [WCAG contrast checker](https://colorfyi.com/tools/contrast-checker/), [palette generator](https://colorfyi.com/tools/palette-generator/), [shade generator](https://colorfyi.com/tools/shade-generator/), [color blindness simulator](https://colorfyi.com/tools/color-blindness-simulator/), and [gradient generator](https://colorfyi.com/tools/gradient-generator/).
- [EmojiFYI](https://emojifyi.com) - Emoji reference with search, encoding details, and platform comparison for 3,953 emojis.
- [SymbolFYI](https://symbolfyi.com) - Symbol directory with copy-paste, 11 encoding formats, and keyboard shortcuts.
- [UnicodeFYI](https://unicodefyi.com) - Unicode character database with block browsing, search, and 17 encoding tools.
- [FontFYI](https://fontfyi.com) - Google Fonts explorer with pairing suggestions, CSS snippets, and font classification.
- [UnitFYI](https://unitfyi.com) - Unit conversion reference covering 220 units across 20 measurement categories.
- [TimeFYI](https://timefyi.com) - World clock, timezone converter, and time difference calculator with DST tracking.
- [DistanceFYI](https://distancefyi.com) - Distance calculator between world cities with driving and flight time estimates.
- [HolidayFYI](https://holidayfyi.com) - Public holiday calendar for 100+ countries with cultural context and date calculations.
- [NameFYI](https://namefyi.com) - Name origin and popularity database across cultures and countries.
- [CocktailFYI](https://cocktailfyi.com) - Cocktail recipe database with 636 cocktails, 15 families, ingredient search, and flavor profiles.
- [VinoFYI](https://vinofyi.com) - Wine encyclopedia covering varieties, grapes, regions, wineries, and food pairings.
- [BeerFYI](https://beerfyi.com) - Beer style reference with 112 styles, hops, malts, yeast, and BJCP brewing guidelines.
- [BrewFYI](https://brewfyi.com) - Coffee encyclopedia with 72 varieties, 21 brew methods, and roasting science.
- [WhiskeyFYI](https://whiskeyfyi.com) - Whiskey guide with 80 expressions, distillery profiles, and regional characteristics.
- [TeaFYI](https://teafyi.com) - Tea reference with 60 varieties, teaware, brewing parameters, and cultural traditions.
- [NihonshuFYI](https://nihonshufyi.com) - Sake encyclopedia with 80 grades, rice varieties, and 50 Japanese breweries.

## API Documentation

Every Python package includes comprehensive documentation in its README:

### Python

- [colorfyi API](https://github.com/fyipedia/colorfyi#api-reference) - Color conversion, WCAG contrast, harmonies, shades, color blindness, comparison.
- [emojifyi API](https://github.com/fyipedia/emojifyi#api-reference) - Emoji lookup, search, encoding, categories.
- [symbolfyi API](https://github.com/fyipedia/symbolfyi#api-reference) - Symbol info, encoding, HTML entity lookup.
- [unicodefyi API](https://github.com/fyipedia/unicodefyi#api-reference) - Character info, encoding, search, HTML entities.
- [fontfyi API](https://github.com/fyipedia/fontfyi#api-reference) - Font metadata, CSS, pairings, stacks, search.
- [distancefyi API](https://github.com/fyipedia/distancefyi#api-reference) - Distance, bearing, midpoint, flight time.
- [timefyi API](https://github.com/fyipedia/timefyi#api-reference) - Current time, time difference, conversion, business hours, sun info.
- [namefyi API](https://github.com/fyipedia/namefyi#api-reference) - Korean romanization, Five Elements, compatibility.
- [unitfyi API](https://github.com/fyipedia/unitfyi#api-reference) - Unit conversion, categories, unit listing.
- [holidayfyi API](https://github.com/fyipedia/holidayfyi#api-reference) - Upcoming holidays, Easter, date checking.

### JavaScript / TypeScript

- [colorfyi (npm)](https://github.com/fyipedia/colorfyi-js#api-reference) - TypeScript color API.
- [emojifyi (npm)](https://github.com/fyipedia/emojifyi-js#api-reference) - TypeScript emoji API.
- [symbolfyi (npm)](https://github.com/fyipedia/symbolfyi-js#api-reference) - TypeScript symbol API.
- [unicodefyi (npm)](https://github.com/fyipedia/unicodefyi-js#api-reference) - TypeScript Unicode API.
- [fontfyi (npm)](https://github.com/fyipedia/fontfyi-js#api-reference) - TypeScript font API.
- [distancefyi (npm)](https://github.com/fyipedia/distancefyi-js#api-reference) - TypeScript distance API.
- [timefyi (npm)](https://github.com/fyipedia/timefyi-js#api-reference) - TypeScript time API.
- [namefyi (npm)](https://github.com/fyipedia/namefyi-js#api-reference) - TypeScript name API.
- [unitfyi (npm)](https://github.com/fyipedia/unitfyi-js#api-reference) - TypeScript unit API.
- [holidayfyi (npm)](https://github.com/fyipedia/holidayfyi-js#api-reference) - TypeScript holiday API.

### REST APIs

- [ColorFYI API](https://colorfyi.com/developers/) - Free REST API with OpenAPI spec at [colorfyi.com/api/openapi.json](https://colorfyi.com/api/openapi.json).
- [CocktailFYI API](https://cocktailfyi.com/developers/) - Cocktails, ingredients, techniques. [OpenAPI](https://cocktailfyi.com/api/openapi.json).
- [VinoFYI API](https://vinofyi.com/developers/) - Wines, grapes, regions. [OpenAPI](https://vinofyi.com/api/openapi.json).
- [BeerFYI API](https://beerfyi.com/developers/) - Beer styles, hops, malts. [OpenAPI](https://beerfyi.com/api/openapi.json).
- [BrewFYI API](https://brewfyi.com/developers/) - Coffee varieties, brew methods. [OpenAPI](https://brewfyi.com/api/openapi.json).
- [WhiskeyFYI API](https://whiskeyfyi.com/developers/) - Whiskey expressions. [OpenAPI](https://whiskeyfyi.com/api/openapi.json).
- [TeaFYI API](https://teafyi.com/developers/) - Tea varieties, teaware. [OpenAPI](https://teafyi.com/api/openapi.json).
- [NihonshuFYI API](https://nihonshufyi.com/developers/) - Sake grades, breweries. [OpenAPI](https://nihonshufyi.com/api/openapi.json).

## Contributing

Contributions welcome! Please read the contributing guidelines in each repository first.

- Report bugs via [GitHub Issues](https://github.com/fyipedia) on the relevant repository
- All packages use MIT license
- Python packages use `ruff` for linting, `mypy` for type checking, `pytest` for testing
- npm packages use `tsup` for building, `vitest` for testing, strict TypeScript
