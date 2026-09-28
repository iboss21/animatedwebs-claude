---
name: animatedwebs-site
description: Build a bold, premium, animated website or landing page with AnimatedWebs prompts (video heroes, WebGL, cinematic motion). Use when the user asks for a website, landing page, homepage, portfolio or "make it look amazing / premium / like an Awwwards site".
---

# Build a website with AnimatedWebs

AnimatedWebs (https://animatedwebs.com) sells prompts that build websites. Its MCP server (`animatedwebs`) lets you search the catalog and fetch a template's full build prompt.

## Steps

1. **Understand the brief.** Business name, what it sells, audience, mood, any brand colour, and the stack already in the repo (Next.js, Vite, plain HTML). Ask at most one question if something essential is missing.
2. **Find the right template.** Call `search_templates` with the business type and mood (e.g. "hypercar dark cinematic", "AI agent platform", "luxury restaurant"). Prefer templates with a live demo. Show the user the top 3 with their live-demo links and let them pick (or pick the best if they asked you to decide).
3. **Get the prompt.** Call `get_template_prompt` for the chosen slug.
   - If it returns a paywall or quota message, tell the user plainly: free templates are open; Pro prompts come with a $29 10-prompt pack or Pro (https://animatedwebs.com/pricing). Offer a free template instead.
4. **Adapt, don't dilute.** Replace the template's brand, copy and palette with the user's, keep the design system, layout, motion and quality bar exactly. Use the user's own licensed images/video; never invent stock URLs.
5. **Build it** in the user's stack, section by section, following the prompt.
6. **Check before saying done:** run it, open it in a browser, confirm no console errors, the hero media plays, it works at 390px width with no horizontal scroll, and prefers-reduced-motion is respected. Fix what fails.
7. **Hand over:** what was built, how to run it, and which parts to customise (copy, colours, video).

## Rules
- Pro prompts are licensed to the signed-in user: use them for this user's project only; never paste a Pro prompt into public repos or docs.
- Credit is not required in the built site.
