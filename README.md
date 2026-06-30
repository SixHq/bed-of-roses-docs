# Bed of Roses — Documentation

Source for the [Bed of Roses](https://github.com/SixHq/bed-of-roses) documentation site,
authored with [Mintlify](https://mintlify.com).

Bed of Roses (BOR) is an AI-native macOS companion: a draggable presence lives above your
desktop, and every chat turn can produce generated apps, widgets, files, theme changes, or
tool calls.

## Local preview

```bash
npm i -g mint
mint dev
```

Then open the URL Mintlify prints (default http://localhost:3000).

## Structure

- `docs.json` — site config, theme, and navigation.
- `getting-started/`, `concepts/`, `features/`, `providers/`, `mcp/`, `cli/`,
  `contributing/`, `reference/` — documentation pages.
- `assets/` — images and static files.
