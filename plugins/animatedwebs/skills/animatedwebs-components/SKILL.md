---
name: animatedwebs-components
description: "Add polished animated UI components (buttons, text effects, backgrounds, cards, loaders, sections) from the AnimatedWebs UI Library, or generate a new one. Use when the user asks for an animated button, heading effect, background effect, hover interaction or loader, or wants a section to feel more premium."
---

# Animated UI components from AnimatedWebs

1. **Find candidates.** Call `search_components` with what the user wants, for example "magnetic button", "text scramble" or "aurora background". `list_component_categories` shows everything available. Show the best 3 with their live preview links.
2. **Get the code.** Call `get_component` for details and `get_component_source` for the code. If the source requires Pro, say so plainly and offer `generate_component` instead.
3. **Nothing fits?** Call `generate_component` with a clear description and the user's stack, then `refine_component` to iterate, for example "glassier", "slower hover" or "use brand colour #7d5bff".
4. **Integrate cleanly.** Match the project's framework, styling system and naming. Keep focus states, a reduced-motion fallback and readable contrast.
5. **Verify it** in a browser at desktop width and at 390px before finishing.
