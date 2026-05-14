# Changelog — Estética Yess

All notable changes to this project are documented here.

---

## [1.0.0] — 2026-05-13

### Added

- **Full single-page website** — sections: hero, services, gallery, location, and social links.
- **Dark / light theme toggle** — moon/sun icon button in the nav header.
  - Dark palette uses deep warm browns (`#120A04`, `#1C1008`) consistent with the brand.
  - Theme persists via `localStorage` across page reloads.
  - Respects the OS `prefers-color-scheme` setting on first visit.
  - Anti-FOUC inline script prevents a flash of the wrong theme on reload.
  - Smooth `0.35s` `background-color` transitions on theme switch.
- **Full ARIA support** on the toggle button (`aria-pressed` + dynamic `aria-label`).

### Fixed

- Contrast on contact section labels.
- Google Maps link in the location section.
- Footer copy text.
- Intro band styling.

### Assets added

| File | Description |
|---|---|
| `index.html` | Main site (1 623 lines) |
| `gallery-1.jpg` … `gallery-9.jpg` | Gallery images |
| `logo-transparent.png` | Primary logo |
| `logo-dark.png` | Logo variant for dark mode |
| `icon-transparent.png` | Site icon / favicon source |

---

## [0.0.1] — 2026-05-13

- Initial commit — empty repository setup.
