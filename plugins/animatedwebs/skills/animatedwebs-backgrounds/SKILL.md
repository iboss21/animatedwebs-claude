---
name: animatedwebs-backgrounds
description: Add a cinematic video background (a seamless looping film) to a hero or section using AnimatedWebs Cinematic Backgrounds. Use when the user asks for a video background, a looping hero video, a cinematic or film-like hero, or "make the hero move".
---

# Cinematic video backgrounds from AnimatedWebs

1. **Find candidates.** Call `search_backgrounds` with the mood or subject the user wants (e.g. "nature", "abstract", "dark", "fashion"). Show the best 3 with their preview links and the template each one powers.
2. **Get the file.** Call `get_background` for the chosen slug. On Pro it returns the clean MP4 link and a ready `<video>` snippet; otherwise it returns the watermarked preview and says which plan includes the clean file. Tell the user plainly; don't ship the watermarked preview as a final asset.
3. **Integrate well.** Put the video behind the hero as a muted, looping, inline, autoplaying, object-fit: cover layer with a poster image. Add a gradient or scrim so the headline stays readable (WCAG contrast), and pause or swap to the poster when the user prefers reduced motion.
4. **Check it** in the browser at desktop and 390px width: it plays, it loops without a jump, text is readable and nothing scrolls sideways.
