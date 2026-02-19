# Janus Pattern Library

Generate Janus mocks from a PRD in seconds using Claude Code.

## How to use

1. Download this folder
2. Open it in Claude Code (`claude` in the terminal from the folder)
3. Paste your PRD or describe what you want to mock
4. Claude generates a `.html` file — open it in your browser

That's it. No installs, no Figma access, no design knowledge needed.

## Example prompts

> "Create a mock for the Approval Detail page. The user should see the request summary, a timeline of events, and approve/reject buttons."

> "Mock the Knowledge Article view — title, breadcrumb, article body with a table of contents on the right, and a feedback section at the bottom."

> "Build the Activity Hub with a filter bar at the top (All / Assigned to Me / Awaiting Approval), a list of work items with status badges, and a detail panel that opens on the right when you click a row."

## Live reference

- **Pattern library**: https://abhitsian.github.io/janus-pattern-library/
- **Component snippets**: https://abhitsian.github.io/janus-pattern-library/snippets.html

## Files in this folder

| File | What it is |
|------|-----------|
| `CLAUDE.md` | Instructions Claude reads automatically — don't delete this |
| `tokens.css` | Design tokens (colors, spacing, etc.) |
| `new-mock.html` | Blank starter template |
| `index.html` | Full design system reference |
| `snippets.html` | Searchable component library |
| `notification-preferences.html` | Example mock |
