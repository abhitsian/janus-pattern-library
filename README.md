# Janus Pattern Library

A self-contained HTML/CSS design system for mocking Janus screens — no Figma, no build tools, no installs required.

## Quick Start (2 minutes)

1. **Clone or download** this repo
2. Open **`new-mock.html`** in a text editor
3. Save it with a new name: `my-feature.html`
4. Follow the `STEP 1 / 2 / 3` comments to set your title, active nav, and content
5. Open **`snippets.html`** in your browser to browse and copy components
6. Paste components into your mock, open in browser, done ✓

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full pattern library — all tokens, components, and examples |
| `snippets.html` | Searchable copy-paste component library |
| `new-mock.html` | Blank starter template — duplicate this for every new mock |
| `tokens.css` | Shared CSS design tokens (colors, spacing, typography, shadows) |
| `notification-preferences.html` | Example mock: Notification Preferences |

---

## Creating a New Mock

```
1.  Duplicate new-mock.html → rename it (e.g. activity-hub-filters.html)
2.  Edit STEP 1  → page <title>
3.  Edit STEP 2  → add class="active" to the right nav item
4.  Edit STEP 4  → paste your components between the content markers
5.  Open snippets.html → find a component → click "Copy HTML" → paste
```

---

## Design Tokens

All tokens live in `tokens.css` as CSS custom properties.

### Brand Colors
| Token | Value | Use |
|-------|-------|-----|
| `--interactive` | `#0080a3` | Links, buttons, focus rings |
| `--interactive-hover` | `#006484` | Hover state |
| `--bg-primary` | `#ffffff` | Cards, panels |
| `--bg-secondary` | `#f5f6f7` | Page background |
| `--text-primary` | `#10171a` | Body copy |
| `--text-secondary` | `#4f5c62` | Labels, captions |
| `--border-default` | `#e2e5e7` | Dividers, card borders |

### Status Colors
| Token | Value |
|-------|-------|
| `--color-success-500` | `#349b21` |
| `--color-error-500` | `#fb3e37` |
| `--color-warning-400` | `#fa751a` |

### Typography
- **Headings**: Inter (system fallback) — 600 weight
- **Body**: Inter — 400/500 weight
- **Base size**: 14px / 20px line-height

### Spacing
4px grid: `--space-1` (4px) → `--space-24` (96px)

---

## Component Classes (quick reference)

```html
<!-- Buttons -->
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-ghost">Ghost</button>

<!-- Badges -->
<span class="badge badge-primary">Active</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-error">Error</span>
<span class="badge badge-neutral">Neutral</span>

<!-- Chips (filter pills) -->
<span class="chip active">All</span>
<span class="chip">Open</span>

<!-- Card -->
<div class="card"> … </div>

<!-- Input -->
<input class="input" placeholder="…">
```

---

## Tips

- **Inspect real components** → open `index.html`, right-click any component → Inspect
- **Copy production HTML** → open `snippets.html`, search by name, click "📋 Copy HTML"
- **All mocks are self-contained** — you can email a single `.html` file and it will open correctly in any browser
- **Share a live link** — push to this repo and use GitHub Pages (see below)

---

## Live URL (GitHub Pages)

Once the repo has GitHub Pages enabled, all mocks are accessible at:

```
https://abhisheksivaraman.github.io/janus-pattern-library/
```

Share individual mock links:
```
https://abhisheksivaraman.github.io/janus-pattern-library/notification-preferences.html
```

---

## Design Contacts

For official design sign-off, reach out to the Janus design team:
- Sumit, Paridhi, Parvati, Zoe

---

## Adding New Components to snippets.html

1. Build and test the component in a mock first
2. Open `snippets.html`, find the right section
3. Add a new `.snip-card` block following the existing pattern
4. Include descriptive `data-tags` for searchability
5. Open a PR so everyone gets the update

---

*Generated from Figma → Project Janus Variable Architecture & Components files. Last synced: 2026-02-19.*
