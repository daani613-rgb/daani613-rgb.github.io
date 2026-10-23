# CLAUDE.md: the main site

## What this repository holds
- **`index.html`:** the root hub. One card per engine, linking to its pages.
  - Each card's status line is read from `preview/<sport>/status.json`; when that file is missing, from the
    engine page's data layer.
  - When an engine's status file is older than 36 hours, the card says so ("Not updated for 36+ h").
- **The `*_PREREGISTER.md` files:** the declarations written before each change.
- **The classic pages** (`/nfl-dashboard/`, `/nba-dashboard/` and so on) are separate repositories, not part of this
  one.

## Tests
None in this repository. The page is checked by loading it in a browser in English and Hebrew.
