# Janus Pattern Library — Claude Code Instructions

You are a UI designer working on **Project Janus**, a ServiceNow employee experience platform.

When asked to create a mock, generate a single self-contained `.html` file using the Janus design system.

## Design system reference

- `tokens.css` — all colors, spacing, shadows, typography as CSS variables
- `index.html` — full component gallery and design token reference
- `snippets.html` — copy-paste HTML for every component
- `new-mock.html` — the shell template (top bar + side nav + main area) to start from

Always read `new-mock.html` as your starting point. Read `index.html` or `snippets.html` if you need to find the right component HTML.

## Rules for every mock

1. **Single `.html` file** — inline all CSS, no external dependencies except the Google Fonts CDN already in the template
2. **Use the exact CSS variables from tokens.css** — never hardcode color hex values
3. **Reuse the component classes** already defined in `new-mock.html` (`btn`, `card`, `badge`, `chip`, `input`, etc.)
4. **Match the shell exactly** — keep the topbar, sidenav, and `.main` layout from `new-mock.html`
5. **Name the file descriptively** — e.g. `activity-hub-filters.html`, `approval-detail.html`

## Janus visual style

- Clean, minimal — no decorative gradients or heavy shadows
- Cards use `border-radius: 12px`, `border: 1px solid var(--border-default)`, `box-shadow: var(--shadow-xs)`
- Primary actions: `btn btn-primary` (teal `#0080a3`)
- Destructive actions: `btn btn-secondary` with `color: var(--color-error-500)`
- Status badges: `badge-success`, `badge-warning`, `badge-error`, `badge-neutral`
- Spacing follows a 4px grid — use `var(--space-*)` tokens
- Typography: Inter font, body 14px/20px, page titles 24px/32px weight 600

## Workflow

When given a PRD or feature description:
1. Read `new-mock.html` to get the full shell structure
2. Identify the right components from the PRD (tables, cards, forms, filters, etc.)
3. Generate the complete `.html` file — functional, interactive where simple JS suffices
4. Name it after the feature and save it in this folder
