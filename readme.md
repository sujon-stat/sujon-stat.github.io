# Portfolio Website — Delivery Brief

## What was built
A single-page personal portfolio website for Sujon, a final-year Statistics undergraduate at Jagannath University and researcher at StatAid Research Lab. The site is built as plain HTML/CSS/JS with no framework dependencies — fast-loading, fully responsive, and accessible.

## File structure
```
DELIVERY/
├── index.html      — Full semantic HTML, all 8 sections + hero + footer
├── styles.css      — Complete design system, responsive, dark mode, animations
└── script.js       — Nav behavior, scroll reveal, dark mode toggle, form handler
```

## Sections delivered (in order)
1. **Hero / Landing** — Name, identity, tagline, 3 CTA buttons (View Research, Download CV, Contact Me), data-inspired SVG background (line chart + scatter + network graph motifs)
2. **About** — Academic background, StatAid role, research philosophy, career goal, info card sidebar, draft mark
3. **Education & Test Prep** — Timeline: Jagannath University degree, IELTS/GRE prep, domestic master's options (BUET/CUET/RUET)
4. **Featured Projects** — 4 case-study cards: SurveyNCD, EpiAgent, KAP Research, RDW in Pediatric CAP — each with description, tech stack tags, repo link placeholder
5. **Research & Publications** — Health diplomacy scoping review (in progress) + placeholder for future papers
6. **Skills** — 4 groups: Statistical Methods, Programming, Tools, Domain Knowledge
7. **Content & Community** — LinkedIn R package series + planned video content
8. **Achievements** — Timeline: lab role, package development, Kaggle capstone, scoping review, coursework
9. **Contact** — Email/LinkedIn/GitHub links, static contact form, CV download

## Design system
- **Primary color**: Deep slate navy (#1e293b)
- **Accent color**: Teal (#14b8a6)
- **Typography**: Sora for headings, Inter for body
- **Light mode** default with **dark mode toggle** (persisted via localStorage)
- **Scroll reveal animations** via IntersectionObserver
- **Sticky nav** with active section highlighting and mobile hamburger menu

## Technical features
- Mobile-first responsive (breakpoints at 768px and 480px)
- Semantic HTML5 with proper heading hierarchy
- ARIA labels on interactive elements
- `prefers-reduced-motion` support
- SEO meta tags + Open Graph + Twitter Card
- SVG favicon (inline, no external file)
- No external JS libraries; Google Fonts only

## Placeholders to fill in
- `your.email@example.com` → real email (in contact section, form handler, and footer)
- `href="#"` on LinkedIn/GitHub links → real profile URLs
- `href="#"` on Download CV → path to CV file
- `href="#"` on project repo links → real GitHub repo URLs
- `og-image.png` → Open Graph image (optional)
- `og:url` → live site URL when deployed
- Hero headshot photo (not included — space available in hero if desired)
- About section text is a draft (marked with editable note)
