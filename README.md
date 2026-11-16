# MEEZAK — public informational website

This repository hosts **only public, static pages** for مِيزَك (MEEZAK).

## Routes
- `/` — Marketing homepage with real Android UI captures (v1.0.5).
- `/privacy/` — Existing public privacy policy (unchanged).
- `/delete-account/` — Existing public account-deletion policy (unchanged).
- `/support/` — Public contact information, no form or backend.
- `/terms/` — Static terms adapted from the backend reference dated 2026-09-27.

## Isolation & privacy
There are **no** API calls, database connections, analytics trackers, authentication flows, user data, or subscription changes in this website. All visual assets are checked-in static files. Account deletion is only explained; the existing deletion instructions remain the source of truth.

## Screenshot provenance
- `assets/screen-home-v5.png` — local file `meezak-captured-20261105/V5/01-v5-home.png`
- `assets/screen-highlights-v5.png` — `meezak-banner-v105qa-20261105/docs/ui-evidence/UI-005/after-final.png`
- `assets/screen-account-v5.png` — `meezak-banner-v105qa-20261105/docs/ui-evidence/UI-006/after.png`
- `assets/screen-errors-v5.png` — `meezak-banner-v105qa-20261105/docs/ui-evidence/UI-007/after.png`
- `assets/screen-question-v5.png` — `Pictures/meezak_home_selected.png` (observed under the V5 era; release build provenance of this particular screenshot has **not** been independently verified)
- `assets/meezak-logo.png` — original Android app logo `app/src/main/res/drawable-nodpi/meezak_logo_original.png`

Captured sample accounts and UI percentages are demo/testing data; they do not represent real learners' progress. Teacher and guardian feature cards are **abstract illustrations**, labeled as such, not forged screenshots.

## Publishing
GitHub Pages project-site compatible (relative URLs), suitable for a custom domain later after DNS, ownership, HTTPS, and Google Play URL verification. Review before merging to `main` so the existing public policy links remain available.

## Manual QA
Check mobile (360 px, 390 px), tablet (768 px), desktop (1440 px), links, keyboard focus, reduced motion, screen-reader reading order, and screenshot provenance.