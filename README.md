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

- Replace `YOUR_SUPPORT_EMAIL@example.com` in `index.html` and
  `privacy.html` with your real support email address.
- Replace the `[REPLACE THIS]` sections in `privacy.html` with information
  that accurately describes the app's actual data practices.
- Replace the canonical URL placeholders (`https://USERNAME.github.io/sudoku-support/`)
  in `index.html` and `privacy.html` with your actual GitHub Pages URL.

## Enabling GitHub Pages

1. Push this repository to GitHub (branch: `main`).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. GitHub will publish the site at:

   ```
   https://USERNAME.github.io/sudoku-support/
   ```

   (replace `USERNAME` with your GitHub username or organization).

## URLs for App Store Connect

- **Support URL:** `https://USERNAME.github.io/sudoku-support/index.html`
  (or `https://USERNAME.github.io/sudoku-support/`)
- **Privacy Policy URL:** `https://USERNAME.github.io/sudoku-support/privacy.html`
