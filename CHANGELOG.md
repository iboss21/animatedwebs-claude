# Changelog

All notable changes to the AnimatedWebs plugin for Claude Code.

## 1.4.0 · 2026-11-11

### Changed
- Skills and commands use the tool names the MCP server lists today: `search_catalog` replaces `search`, `get_template` with `include_prompt` replaces `get_template_prompt`, `get_component` with `include_source` replaces `get_component_source`, and `open_builder` replaces `open_in_builder`. `list_categories` takes `kind`. The old names still work when called.
- The site and hero skills use the `technique` and `templateKind` filters for 3D and WebGL briefs, and check the plan with `get_account` before a Pro prompt spends a Prompt Pack credit.
- The library now has more than 1,600 templates; descriptions, badge and README updated.
- README tool table matches the 15 tools the server lists and names its five MCP prompts.

### Added
- `/animatedwebs:save` saves a template, component or background to your favourites, or lists them, through `save_item`.
- `/animatedwebs:request` sends a template request with `request_template` and follows it up with `manage_request`.
- The site skill offers `open_builder` to start a template in Lovable, v0 or Bolt.

## 1.3.0 · 2026-11-02

### Changed
- The MCP server now lists 15 tools. One `search` tool (with `kind`, filters, an empty query to browse and a `cursor` for paging) replaces `search_templates`, `search_components`, `search_everything`, `search_backgrounds`, `search_styles` and `search_creators`. `list_categories` takes a `scope` and replaces `list_component_categories`. `get_account` replaces `get_design_workspace`. The old names still work when called.
- All skills and commands use the new tools.

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
