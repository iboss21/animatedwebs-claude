---
name: animatedwebs-hero
description: Add a bold cinematic hero (full-bleed looping video or WebGL/shader background, massive type, glass nav) to an existing website using AnimatedWebs prompts. Use when the user wants a "wow" hero, a video background, an animated background or a more premium first screen.
---

# Upgrade a hero with AnimatedWebs

1. Read the current hero/home page and the stack in the repo.
2. Call `search_templates` on the `animatedwebs` MCP with the brand mood plus "hero" or "background" (e.g. "space dark hero", "liquid chrome background"). Show the top 3 with live-demo links.
3. Call `get_template_prompt` for the chosen template and apply only its hero/background part:
   - video hero: full-bleed muted looping video (the user's own licensed clip), dark gradient scrim, poster until it plays;
   - shader/WebGL background: implement it in code as the prompt describes (no video file);
   - massive headline, small glass pill nav, one or two pill buttons, entrance animation.
4. Keep the user's copy, brand and existing sections; don't rewrite the rest of the site.
5. Verify in a browser: no console errors, loads fast (lazy-load below the fold), 390px mobile has no horizontal scroll, reduced motion respected.
