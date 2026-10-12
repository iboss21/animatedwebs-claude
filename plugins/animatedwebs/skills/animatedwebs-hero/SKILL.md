---
name: animatedwebs-hero
description: "Give an existing website a cinematic hero section (looping video, WebGL or shader background, oversized type, refined navigation) using AnimatedWebs templates. Use when the user wants a more impressive first screen, an animated or video background, or a hero that stops visitors scrolling."
---

# Upgrade a hero with AnimatedWebs

1. **Read the current site.** Open the home page and hero, and note the stack, fonts and brand colours.
2. **Find directions.** Call `search_templates` with the brand mood plus "hero", for example "dark particle hero" or "calm water video hero". For a video hero, `search_backgrounds` lists ready-made cinematic loops. Show the top 3 with their live-demo or preview links.
3. **Apply only the hero.** Call `get_template_prompt` (or `get_background` for a loop) and implement the hero part:
   - **Video hero:** full-bleed, muted, looping, inline video with a poster image and a gradient scrim for legible text.
   - **WebGL or shader hero:** implement it in code exactly as the prompt describes; no video file is needed.
   - **Type and navigation:** oversized headline, refined navigation and one clear primary action, with an entrance animation.
4. **Respect the rest of the site.** Keep the user's copy, brand and other sections unchanged.
5. **Verify in a browser.** No console errors, fast first paint (lazy-load anything below the fold), no horizontal scroll at 390px, and a calm fallback for `prefers-reduced-motion`.
