# aeo-demo-beauty

## Overview
A static HTML template demonstrating AI-Engine Optimization (AEO) for the beauty industry. It serves as a reference implementation for integrating Schema.org structured data, `llms.txt` for AI crawlers, and semantic markup to improve visibility in AI search results.

## Tech Stack
- **Core:** HTML5
- **SEO/AIO:** Schema.org (JSON-LD), llms.txt, FAQ Schema
- **Styling:** Plain CSS (Minimal/None)

## Architecture
- `index.html`: Main entry point with semantic structure and embedded Schema.
- `llms.txt`: Text file describing content for Large Language Models.
- `faq`: Section or separate file handling FAQ structured data.

## Commands
- **Local Server:** `python3 -m http.server` or `npx serve` to view the template.
- **Validation:** Use Google's Rich Results Test to verify Schema implementation.

## Coding Style
- Semantic HTML5 (`<main>`, `<article>`, `<section>`).
- Valid JSON-LD embedded in `<head>` or body.
- Clean, readable indentation.

## Important Rules
- **Mandatory:** Maintain all JSON-LD scripts; do not minify/obfuscate them.
- **Accessibility:** Ensure semantic tags are used correctly for screen readers.
- **AI-Optimization:** Do not block `llms.txt` in `robots.txt`.