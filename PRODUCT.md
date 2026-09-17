# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Hiring managers, recruiters, and prospective clients (agencies, startups, enterprises) evaluating Serhii Kovalchuk for senior product design roles or contract engagements, particularly in regulated or data-heavy domains (fintech, medtech/pharma, enterprise SaaS). They arrive with a specific role or brief in mind and scan quickly for signal — seniority, domain fit, quantified impact, process rigor — rather than browsing for visual inspiration.

## Product Purpose

A personal portfolio site presenting Serhii's experience, working method, and selected case studies, built to convert a visit into an interview or contract conversation. Success is a visitor reaching out (email, LinkedIn, phone, Telegram) or opening a case study page to support a hiring decision.

## Positioning

Not a generalist UI/UX portfolio — a specialist position built around regulated, data-heavy software where a wrong click is costly (KYC/compliance onboarding, pharmacovigilance/clinical workflows, multi-device enterprise systems). The differentiator is a named method — research first, then removal of unnecessary steps, then documentation so removed complexity doesn't return — backed by quantified before/after metrics rather than visual-only case pieces.

## Operating Context

Static site on GitHub Pages (kovalchuk-design.github.io): a single long-scroll homepage with anchor navigation (Cases, AI in my process, Skills, Contact), linking out to standalone case-study pages under `work/*.html` that share `assets/case.css`. No backend and no forms; contact happens through `mailto:`, `tel:`, LinkedIn, and Telegram links. Real screenshots live under `/shots` and `/work/shots`.

## Capabilities and Constraints

- Static HTML/CSS/vanilla JS only — no build tooling, framework, or backend. Must stay deployable as-is on GitHub Pages.
- This round is scoped to the homepage (`index.html`) only. The `work/*.html` case-study pages and `assets/case.css` are out of scope and must not be modified.
- Homepage links into `work/*.html` must keep working — hrefs to existing case pages are a fixed integration point.
- Delivery for this round: build the redesigned homepage as a separate comparison page (not an in-place replacement of `index.html`), so the current live homepage stays untouched until the user decides to swap it in.
- Light copy edits are allowed for legibility/clarity (e.g. shortening a line that fails a readability check), but every fact, metric, client name, and date must be preserved — no rewriting for tone or adding claims.

## Brand Commitments

Name: "Serhii Kovalchuk"; nav mark "SK". Existing visual identity is dark, technical, and editorial: near-black background, off-white ink, a saturated blue accent, set in Archivo (display) + Instrument Sans (body) + JetBrains Mono (data/labels). **The color palette is a binding constraint carried into the redesign** — the improved version must reuse the same color tokens (`--bg #0D0F12`, `--bg-lift #14171C`, `--ink #E9EAE5`, `--ink-2 #9AA1A9`, `--ink-3 #8A9199`, `--accent #1B3FD8`, `--accent-lift #7C97FF`), not a new palette. Voice is terse, factual, non-hype, and metrics-forward.

## Evidence on Hand

Real client/employer names and dates: RxLogix (2025–present), NewDay (2023–2025), Carnival (2022–2023), plus agency history 2012–2022 (Silk Design, The Yard Design, HelloClicks, freelance). Quantified before/after metrics per case, including one metric explicitly marked "Est." (estimated from an observed distribution, not directly measured) — that distinction must stay visible, never silently upgraded to a bare claim. Real screenshots exist under `/shots`. Real contact channels: email, LinkedIn, phone, Telegram. No testimonials, logos, or additional metrics exist beyond what's on the current page — none may be fabricated.

## Product Principles

1. Every claim stays traceable to what already exists on the site — no invented clients, metrics, or testimonials.
2. Speed-to-signal for a scanning recruiter beats decorative flourish: seniority, domain fit, and quantified impact must read within the first viewport.
3. The measured/estimated distinction on metrics stays visible.
4. Domain specialization (regulated, data-heavy software) is the differentiator and must stay foregrounded, not diluted into generic "UI/UX portfolio" framing.
5. Case-study hrefs into `work/*.html` are fixed this round; the homepage must keep linking to them unchanged.

## Accessibility & Inclusion

The Capabilities section claims "Accessibility (WCAG 2.1)" as a professional skill, so the designer's own homepage should not visibly fail basic accessibility/legibility floors — that would undercut the claim. A detector pass on the current homepage already found concrete failures to fix in the redesign: functional text below the 11px legibility floor, a paragraph with line-height of 0.12× (should be ≥1.3×), and multiple containers with text flush against their borders (no inset padding).
