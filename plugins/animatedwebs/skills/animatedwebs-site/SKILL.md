---
name: animatedwebs-site
description: "Build a complete, premium animated website or landing page from an AnimatedWebs template (cinematic video heroes, WebGL scenes, scroll storytelling). Use when the user asks for a website, landing page, homepage or portfolio, or wants a site that looks premium, cinematic or award-worthy."
---

# Build a website with AnimatedWebs

AnimatedWebs (https://animatedwebs.com) is a library of more than 1,400 animated website templates, each with a live demo and a complete build prompt. The `animatedwebs` MCP server searches the library, returns a template's full build prompt, and supplies backgrounds, components and design systems.

## Steps

1. **Understand the brief.** Business name, what it offers, audience, mood, brand colours and the stack already in the repository (Next.js, Vite, Astro, plain HTML). Ask at most one question, and only if something essential is missing.
2. **Find the right template.** Call `search_templates` with the business type and mood, for example "AI research platform, dark", "boutique hotel, calm" or "fintech, chrome". Prefer templates with a live demo. For a specific trade, the industry pages at https://animatedwebs.com/industries list the closest matches (dentist, restaurant, law firm, hair salon and over 130 more). Show the top 3 with their live-demo links and let the user choose, or choose the best match if they asked you to decide.
3. **Get the prompt.** Call `get_template_prompt` for the chosen slug. If it returns an access message, explain it plainly: Free templates are open to every account, and Pro templates come with Pro or a Prompt Pack (https://animatedwebs.com/pricing). Offer a Free template as an alternative.
4. **Adapt without diluting.** Replace the template's brand, copy and palette with the user's. Keep its layout, typography, motion and quality bar. Use the user's own licensed media, or a background from `search_backgrounds`; never invent stock URLs.
5. **Build it** in the user's stack, section by section, as the prompt describes.
6. **Verify before finishing.** Run it and open it in a browser. Confirm there are no console errors, hero media plays, the page works at 390px with no horizontal scroll, and `prefers-reduced-motion` is respected. Fix anything that fails.
7. **Hand over.** Summarise what was built, how to run it and which parts to customise (copy, colours, media).

## Licence

- Pro prompts are licensed to the signed-in user for their own and client projects. Never publish a Pro prompt in a public repository or document.
- No AnimatedWebs credit is required on the finished site.
