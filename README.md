# Sudoku Support Site

A minimal static support and privacy policy website for the Sudoku app, used
for Apple App Store Connect's Support URL and Privacy Policy URL fields.

No build system, no framework, no JavaScript — just plain HTML and CSS.

## Files

- `index.html` — support homepage
- `privacy.html` — privacy policy
- `404.html` — not found page
- `style.css` — shared styles (light/dark mode via `prefers-color-scheme`)

## Before publishing

- Support email is currently set to `anton-i-bor@hotmail.com` in
  `index.html` and `privacy.html`. Update if this changes.
- Replace the `[REPLACE THIS]` sections in `privacy.html` with information
  that accurately describes the app's actual data practices.
- Canonical URLs in `index.html` and `privacy.html` are set to
  `https://KlasseBrasse.github.io/sudoku-support/`.

## Enabling GitHub Pages

1. Push this repository to GitHub (branch: `main`).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. GitHub will publish the site at:

   ```
   https://KlasseBrasse.github.io/sudoku-support/
   ```

## URLs for App Store Connect

- **Support URL:** `https://KlasseBrasse.github.io/sudoku-support/`
- **Privacy Policy URL:** `https://KlasseBrasse.github.io/sudoku-support/privacy.html`
