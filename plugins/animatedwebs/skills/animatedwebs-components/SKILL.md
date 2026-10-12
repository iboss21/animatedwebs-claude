---
name: animatedwebs-components
description: Add polished animated UI components (buttons, text effects, backgrounds, cards, loaders, sections) from the AnimatedWebs UI Library, or generate a new one. Use when the user asks for a fancy button, animated heading, background effect, hover effect, loader or "make this section feel premium".
---

# Animated UI components from AnimatedWebs

1. **Find candidates.** Call `search_components` with what the user wants (e.g. "magnetic button", "text scramble", "aurora background"). `list_component_categories` shows what exists. Show the best 3 with their live preview links.
2. **Get the code.** Call `get_component_source` for the chosen id. If it says Pro is required, tell the user plainly and offer `generate_component` instead.
3. **Nothing fits?** Call `generate_component` with a clear description and the user's stack, then `refine_component` to iterate ("glassier", "slower hover", "match brand colour #...").
4. **Integrate cleanly.** Match the project's framework, styling system and naming. Keep accessibility: focus states, reduced-motion fallbacks, readable contrast.
5. **Check it** in the browser at desktop and 390px before saying done.
