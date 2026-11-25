# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.0.3] - 2026-11-25

### Fixed
- Keyboard focus on tiles: active tiles on the bright plate showed no focus ring at all, and inactive tiles only a faint grey one (about 2.6:1 on the light sky). Focused tiles now get a 2 px ring in the theme blue with a white halo in light mode, at least 3:1 against both sides (WCAG 2.2, 1.4.11). The plate keeps its glow. Needs card-mod, like the other glass extras.

## [1.0.2] - 2026-11-24

### Changed
- README: Clear Sky is in the default catalog now, so the note about adding it as a custom repository is gone. The theme file is unchanged, so updating changes nothing on your dashboards.

## [1.0.1] - 2026-11-22

### Fixed
- Logbook card: the sticky date row showed the date twice and let entries shine through while scrolling, because it took the translucent card colour. It now gets an almost opaque row colour (`glass-date-row`, light and dark). Needs card-mod, like the other glass extras.

## [1.0.0] - 2026-11-22

### Added
- First release: one theme with light and dark mode.
- Translucent cards on a sky gradient, calm background for settings and editors.
- Optional card-mod rules: blur behind cards, floating sidebar, bright plate for active tiles.
- Optional variables for Bubble Card and navbar-card.
