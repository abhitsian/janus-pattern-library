# Janus Pattern Library

Generate Janus mocks from a PRD in seconds using Claude Code.

## Download

**[⬇ Download ZIP](https://github.com/abhitsian/janus-pattern-library/archive/refs/heads/main.zip)**

No git required. Just download and unzip.

---

## Setup (one time, 3 steps)

**Step 1 — Download and unzip**
Click the link above, or go to the GitHub page → green "Code" button → "Download ZIP". Unzip it anywhere on your computer.

**Step 2 — Install Claude Code** (if you haven't already)
```
npm install -g @anthropic/claude-code
```
Then run `claude` once to log in with your Anthropic account.

**Step 3 — Open the folder in Claude Code**

On Mac, open Terminal, then drag the unzipped folder into the Terminal window and press Enter. Then type:
```
claude
```

This is important — Claude needs to be opened *inside* the folder so it can read the Janus design system context automatically.

---

## How to use

Once inside Claude Code, just describe what you need:

> "Create a mock for the Approval Detail page. The user should see the request summary, a timeline of events, and approve/reject buttons."

> "Mock the Activity Hub with a filter bar, a list of work items with status badges, and a detail panel that slides in from the right."

Claude generates a `.html` file — open it in your browser. Done.

No Figma access, no design knowledge, no build tools needed.

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
