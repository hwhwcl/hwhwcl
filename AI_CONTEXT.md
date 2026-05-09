# AI Context

This file provides context and working rules for ChatGPT, Codex, Cursor, and other AI coding assistants.

## Repository Status

This repository has been newly initialized. It is prepared for future development, but the main product direction has not yet been fixed in code.

AI assistants should treat this repository as an early-stage workspace.

## General Working Principles

AI assistants should:

1. Read `README.md`, `PROJECT_INDEX.md`, `AI_CONTEXT.md`, and `TASKS.md` before making changes.
2. Keep the project structure clean and easy to understand.
3. Prefer simple, maintainable code over over-engineered solutions.
4. Use clear file names and folder names.
5. Add comments only where they help explain non-obvious logic.
6. Update documentation when adding important functionality.
7. Avoid deleting existing files unless explicitly requested.
8. Avoid introducing unnecessary dependencies.
9. Keep business logic separated from UI code where possible.
10. Make changes in small, understandable steps.

## Preferred Development Style

The preferred style is practical and business-oriented:

- Clear structure
- Direct implementation
- Easy future maintenance
- Suitable for iterative development with AI tools
- Avoid excessive abstraction at the early stage

## Possible Project Directions

This repository may later be used for one or more of the following:

### 1. AI Stock Selection / Trading Research Tool

Potential features:

- Daily stock recommendations
- Multi-factor stock screening
- Recommendation reasons
- Watchlist for next-day verification
- Historical recommendation records
- Backtesting and performance review
- Market news and policy signal integration

### 2. Salary and Benefits Calculator Website

Potential features:

- China salary and social insurance calculator
- Shanghai / Beijing / Guangdong regional rules
- Forward calculation and reverse calculation
- Mobile-friendly web UI
- SEO content pages
- Advertisement link monetization

### 3. Daily Intelligence Report Automation

Potential features:

- Daily news collection
- Business and financial report generation
- Fashion / beauty / licensing industry intelligence
- Email delivery
- Source links and deduplication
- Deep insights section

### 4. Business Management / Brand Management Tools

Potential features:

- Brand project tracking
- Partner and licensee pipeline management
- Deal term summaries
- Retail channel management
- Document and proposal templates

## Coding Guidelines

If the project becomes a web application:

- Separate frontend and backend clearly.
- Keep API routes organized.
- Use environment variables for secrets.
- Do not commit API keys, tokens, passwords, or private credentials.
- Add example config files instead of real secrets.

If the project becomes a Python data project:

- Use clear data folders.
- Separate raw data, processed data, and output files.
- Add retry and checkpoint logic for long-running downloads.
- Store large data files outside Git if necessary.

## Security Rules

Never commit:

- API keys
- Access tokens
- Passwords
- Private certificates
- Personal identity documents
- Large confidential business files
- Sensitive customer or employee data

Use `.env` locally and provide `.env.example` for documentation.

## Documentation Rules

When adding major functions, update:

- `PROJECT_INDEX.md`
- `TASKS.md`
- Relevant README or docs files

## Response Preference for AI Assistants

When explaining changes, be concise and practical:

- What was changed
- Why it was changed
- How to run or test it
- What should be done next
