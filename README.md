# AnimatedWebs for Claude Code

Build bold, cinematic websites with [AnimatedWebs](https://animatedwebs.com) right inside Claude Code: animated templates, cinematic video backgrounds, UI components, design styles and Design Studio.

## Install

```
/plugin marketplace add iboss21/animatedwebs-claude
/plugin install animatedwebs@animatedwebs
```

The first time a tool runs, Claude Code opens your browser to sign in to AnimatedWebs (a free account works). Free templates are open straight away; Pro unlocks everything. See [pricing](https://animatedwebs.com/pricing).

## Commands

| Command | What it does |
|---|---|
| `/animatedwebs:site <business>` | Picks the best template and builds the whole site |
| `/animatedwebs:browse <style>` | Shows matching templates with live demos |
| `/animatedwebs:hero <idea>` | Gives your current site a cinematic hero |
| `/animatedwebs:background <mood>` | Adds a cinematic video background to your hero |
| `/animatedwebs:component <idea>` | Adds an animated UI component |
| `/animatedwebs:style <mood>` | Applies a design style as tokens |
| `/animatedwebs:design` | Connects AnimatedWebs Design Studio |

Or just ask: *"build me a premium landing page for my bakery"* and the right skill takes it from there.

## What's inside

- **MCP server** `https://mcp.animatedwebs.com` (browser sign-in) with 22 tools:
  - Templates: `search_templates`, `get_template`, `get_template_prompt`, `list_categories`, `open_in_builder`, `request_template`
  - UI Library: `search_components`, `list_component_categories`, `get_component`, `get_component_source`, `generate_component`, `refine_component`
  - Cinematic Backgrounds: `search_backgrounds`, `get_background`
  - Styles: `search_styles`, `get_style_reference`
  - Design: `get_design_workspace`
  - Account and community: `search_everything`, `get_account`, `get_pricing`, `search_creators`, `get_creator`
- **Skills:** `animatedwebs-site`, `animatedwebs-hero`, `animatedwebs-backgrounds`, `animatedwebs-components`, `animatedwebs-style`, `animatedwebs-design`
- **Commands:** listed above

Full documentation: [animatedwebs.com/mcp](https://animatedwebs.com/mcp)

AnimatedWebs content is licensed under the [Terms](https://animatedwebs.com/terms). [Privacy](https://animatedwebs.com/privacy)
