# New Web — Website Structure

What the site is for: get a company founder or marketing lead to **book a call** (primary) or **send a brief** (secondary). Every page ends pointing at one of those two.

## Sitemap

```
/                      Home (the landing page)
├── /work              Portfolio grid
│   └── /work/:slug    Case study (one per client project)
├── /services          What we build + pricing packages
├── /process           How a project runs, week by week
├── /about             Who we are, why we do this
├── /contact           Book a call / send a brief
├── /blog              (later) Articles on landing pages and conversion
├── /privacy           Privacy policy
└── /terms             Terms of service
```

## Global elements (on every page)

| Element | Contents |
|---|---|
| **Navbar** | Logo · Work · Services · Process · About · **Book a call** button. Sticky, shrinks on scroll. Hamburger menu on mobile. |
| **Footer** | Short tagline · page links · email · social links (LinkedIn, X, Instagram, Dribbble/Behance) · © year · Privacy · Terms |
| **Floating CTA** (mobile) | "Book a call" bar pinned to the bottom of the screen after the hero scrolls out |

---

## Home `/`

The full pitch on one page. Section order is the order a visitor's questions come up.

| # | Section | Visitor's question | What goes in it |
|---|---|---|---|
| 1 | **Hero** | What is this? | Headline (what we build, for whom), one-line subhead, **Book a call** + **See our work** buttons, a live preview or animated mockup of a site we built |
| 2 | **Client logos** | Who trusts them? | Row of client/brand logos, auto-scrolling marquee |
| 3 | **Problem** | Why should I care? | 2–3 short pain points: site looks dated, visitors don't convert, agencies take months |
| 4 | **Services** | What exactly do they do? | 3–4 cards: Landing pages · Company websites · Redesigns · Ongoing care & updates. Each: icon, one line, "Learn more" → /services |
| 5 | **Selected work** | Are they any good? | 3–6 featured projects, big screenshots, client name + one result line, hover preview. "View all work" → /work |
| 6 | **Process** | How does it work? | 4 steps: Discovery call → Design → Build → Launch, with timeline for each. "See full process" → /process |
| 7 | **Results / numbers** | Does it pay off? | 3–4 stat counters (sites launched, avg. delivery days, conversion lift, clients) — real numbers only |
| 8 | **Testimonials** | What do clients say? | 3–6 quotes with name, role, company, photo. Carousel on mobile |
| 9 | **Pricing preview** | What will it cost? | 3 packages (e.g. Starter landing page / Business website / Custom) with "starting at" price and 3–4 bullets each. "Compare packages" → /services |
| 10 | **FAQ** | What about…? | 6–8 accordion questions: timeline, revisions, who owns the code, hosting, CMS, payment terms, post-launch support |
| 11 | **Final CTA** | OK, what now? | Big headline, **Book a call** button, email link, response-time promise |

## Work `/work`

- Page header: title + one line
- Filter chips: All · Landing pages · Websites · Redesigns · by industry
- Project grid: thumbnail, client, type, one result line → links to case study
- Final CTA

## Case study `/work/:slug`

One template, filled per project:

1. **Header** — client name, project type, year, live site link, hero screenshot
2. **Overview** — client, industry, timeline, services delivered
3. **The challenge** — what was wrong before
4. **Our approach** — strategy, design decisions, key screens
5. **Before / after** — side-by-side or slider
6. **Results** — metrics (conversion, speed, bounce rate, leads)
7. **Client quote**
8. **Next project** link + Final CTA

## Services `/services`

1. Header
2. **Service blocks** — one per service: what's included, who it's for, typical timeline
3. **Pricing table** — 3 packages side by side, feature comparison rows, "Most popular" tag
4. **Add-ons** — copywriting, SEO setup, CMS, analytics, maintenance plan
5. Services FAQ
6. Final CTA

## Process `/process`

1. Header
2. **Timeline** — each step with what happens, what the client gives, what they get, duration
3. **What we need from you** — checklist (brand assets, copy, access)
4. **Tools we use** — design + dev stack logos
5. Final CTA

## About `/about`

1. **Story** — why New Web exists
2. **Values / how we work** — 3–4 principles
3. **Team** — photos, names, roles, links
4. Numbers strip
5. Final CTA

## Contact `/contact`

Two paths side by side:

- **Book a call** — embedded calendar (Calendly / Cal.com)
- **Send a brief** — form: name, email, company, website (optional), what you need (landing page / website / redesign / other), budget range, timeline, message
- Below: email, WhatsApp, response-time promise, location

---

## Pages to build first

1. Home (all 11 sections)
2. Contact
3. Work + one case study template
4. Services
5. Process, About
6. Legal pages
7. Blog (later)
