# Changelog

All notable changes to the AnimatedWebs plugin for Claude Code.

## 1.2.2 · 2026-10-19

### Changed
- The library now has more than 1,400 templates; descriptions, badge and README updated.
- The site skill points to the industry pages (https://animatedwebs.com/industries) when the brief names a trade.

## 1.2.1 · 2026-10-12

### Fixed
- The `animatedwebs-style` skill description contained an unquoted colon, which made its YAML frontmatter invalid. Every skill and command description is now quoted.

### Changed
- Rewrote all six skills and seven commands for clearer, more precise instructions.
- The hero skill now offers AnimatedWebs Cinematic Backgrounds for video heroes.
- The components skill uses `get_component` alongside `get_component_source`.
- Updated plugin and marketplace descriptions and keywords.

### Added
- Redesigned README with banner, live showcase, template gallery and full documentation.
- Changelog, security policy, licence notice and issue forms.

## 1.2.0 · 2026-10-12

### Added
- `animatedwebs-backgrounds` skill and `/animatedwebs:background` command.
- MCP tools `search_backgrounds` and `get_background`, bringing the server to 22 tools.

## 1.1.0 · 2026-10-12

### Added
- `animatedwebs-components`, `animatedwebs-style` and `animatedwebs-design` skills.
- `/animatedwebs:component`, `/animatedwebs:style` and `/animatedwebs:design` commands.
- MCP tools for the UI Library, Styles and Design Studio (20 tools).

## 1.0.0 · 2026-09-28

### Added
- First release: the AnimatedWebs MCP server with browser sign-in, the `animatedwebs-site` and `animatedwebs-hero` skills, and the `site`, `browse` and `hero` commands.
