# New Web

Modern landing pages and websites for companies. This repo holds the studio's own site: what we build, past work, pricing and a way to get in touch.

**Website structure (pages, sections, what goes where):** [docs/site-structure.md](docs/site-structure.md)

## Structure

```
new-web/
├── public/                 Static files served as-is (favicon, og image, robots.txt)
│   └── images/             Photos, client logos, portfolio screenshots
├── src/
│   ├── components/
│   │   ├── layout/         Navbar, Footer, page wrapper
│   │   ├── sections/       Landing page blocks: Hero, Services, Work, Process,
│   │   │                   Testimonials, Pricing, FAQ, CTA, Contact
│   │   └── ui/             Small reusable pieces: Button, Card, Badge, Input
│   ├── pages/              Full pages: Home, Work, Case study, About, Contact
│   ├── data/               Site content kept out of components (services,
│   │                       projects, testimonials, pricing tiers, FAQs)
│   ├── styles/             Global CSS, theme tokens (colors, type, spacing)
│   ├── lib/                Helpers and utilities
│   └── assets/             Icons, SVGs and fonts imported by components
└── docs/                   Notes, briefs, design references
```

## Conventions

- One component per file, named in PascalCase (`Hero.tsx`, `PricingCard.tsx`).
- Copy, links and numbers live in `src/data/`, so changing text doesn't mean touching layout code.
- Landing sections go in `src/components/sections/` and are composed in `src/pages/`.
