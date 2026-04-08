# Project-to-Income Engine
> VibeHack 2025 — Data Science Club Hackathon

**From Student Project to Monetizable Idea — powered by AI**

---

## Problem Statement
Students build great projects but struggle to convert them into income or real-world opportunities. They don't know how to monetize, who their users are, or how to price their work.

## Solution
A web platform where a student inputs their project idea, and an AI engine instantly generates:
- **Monetization strategies** tailored to their domain
- **Target user segments** they should focus on
- **Pricing tiers** (Free / Pro / Team)
- **30-day action plan** to start earning

## How It Works
1. User enters project description + domain + stage
2. App calls Claude AI API with a structured prompt
3. Claude returns a JSON response with monetization analysis
4. Results are displayed in a clean, structured UI

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (vanilla — no frameworks)
- **AI:** Claude API (claude-sonnet-4-20250514) by Anthropic
- **Hosting:** GitHub Pages

## AI Tools Used
- **Claude (Anthropic)** — used for generating monetization strategies, target user analysis, pricing suggestions, and next-step recommendations
- Claude was used to assist in UI design and code generation during development

## Setup Instructions
1. Clone this repo
2. Open `index.html` in a browser
3. The app calls the Anthropic API directly from the frontend

> **Note:** API key is handled via Anthropic's public endpoint. For production use, move API calls to a backend server to keep keys secure.

## Team X
- Pranav Purwar
- 25BCE11086

## Future Scope
- Save and export results as PDF
- Add competitor analysis using web search
- User accounts to save past analyses
- Pitch deck auto-generator from the output

---
*Built with ❤️ at VibeHack 2025 by Data Science Club*
