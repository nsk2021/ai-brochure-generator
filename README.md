# AI-Powered Brochure Generator (Website Scraper + Intelligent Navigation)

This project generates a clean, client-ready **Markdown brochure** for any company by:
1. Scraping the homepage
2. Intelligently selecting high-signal pages (About, Product, Solutions, Pricing, Customers, Careers)
3. Optionally using an LLM to synthesize a polished brochure

Primary artifact: `ai_brochure_generator.ipynb`  
Outputs are written to `outputs/`.

## Features
- Polite website crawling defaults (timeouts, page limits, light throttling)
- Link discovery + scoring using simple, transparent heuristics
- Optional LLM-powered link selection for better navigation
- Optional LLM brochure writing step (Markdown)
- Repo-friendly output structure (`outputs/`)

## Project Structure
```text
.
├── ai_brochure_generator_github_ready.ipynb
├── outputs/
└── src/                # optional, if you later extract code from the notebook
