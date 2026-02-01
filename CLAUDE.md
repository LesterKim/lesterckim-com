# Lester Kim Personal Website

## Project Overview

Personal website and landing page for Lester Kim's fractional Head of Engineering/CTO consulting services. Static site hosted on Cloudflare Pages, connected to GitHub repo for automatic deployments.

## Value Proposition

I help 10-person engineering teams become AI-native and ship faster—without adding headcount.

## Target Audience

- Startup founders/CTOs with small engineering teams (around 10 people)
- Companies looking to adopt AI tooling without hiring
- Teams that want to increase velocity with existing headcount

## Tech Stack

- Plain HTML/CSS (index.html in root)
- Cloudflare Pages for hosting
- GitHub repo triggers auto-deploy on push to main
- Zola config exists (config.toml) but currently using simple static HTML

## Design Principles

1. **Minimal styling** - Keep CSS and HTML as simple as possible
2. **Fast loading** - No JavaScript frameworks, minimal dependencies
3. **Mobile-first** - Simple responsive design that works on all devices
4. **Clear hierarchy** - One primary CTA per section

## File Structure

```
/
├── index.html          # Main landing page
├── static/
│   ├── css/main.css    # All styles
│   └── images/         # Headshot and assets
├── config.toml         # Zola config (not currently used)
├── content/            # Zola content (not currently used)
└── templates/          # Zola templates (not currently used)
```

## Current State

Simple personal bio page with:
- Brief intro and background
- Tech preferences (Rust, HTMX, GCP, Postgres)
- Engineering philosophy (TDD, Clean Architecture, customer conversations)
- Headshot
- Social links (LinkedIn, X, GitHub)

## Roadmap

### Phase 1: Services Landing Page
- [ ] Clear headline with value proposition
- [ ] Brief description of services
- [ ] Social proof (past roles, companies)
- [ ] Single CTA (likely "Book a call" or similar)

### Phase 2: Lead Magnet & Email Capture
- [ ] Add email signup form for newsletter
- [ ] Create lead magnet (guide, checklist, or similar)
- [ ] Connect to email service (ConvertKit, Buttondown, etc.)

### Phase 3: Content
- [ ] Add articles/blog section
- [ ] Case studies or testimonials

## Inspiration

- Justin Welsh (justinwelsh.me) - Clean design, clear value prop, multiple conversion paths
- Focus on lifestyle-first solopreneurship messaging
- Social proof through media mentions and subscriber counts

## Code Style

- Semantic HTML5 elements
- CSS using system fonts, minimal custom styling
- No build tools required for basic changes
- BEM-style class naming when needed
- Mobile-first media queries

## Deployment

Push to `main` branch triggers automatic Cloudflare Pages deployment.

## Commands

```bash
open index.html
```
