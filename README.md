# PoserTryHard Website — Project Brief

## Purpose
Website build for PoserTryHard (PTH), Dylan's multimedia business spanning content creation, social media presence, and brand development. Based in Toronto.

## Current status
An extensive build has been completed. What remains is primarily hosting/deployment and swapping placeholder links for real ones.

## What's built

**Animated preloader**
- Uses Higgsfield-generated video clips of a pictogram logo figure cycling through 10 activities.

**Interactive "lair" page**
- Platform logo overlays (YouTube, Shopify, Spotify, Twitch, Kick, and other socials) mapped to clickable zones in HTML.
- Image manipulation done in Python/Pillow with perspective transforms.
- Workflow: Claude marks candidate positions with red outlines, Dylan directs adjustments from there.

**Branding**
- PTH monogram logo: uppercase P, lowercase t, lowercase h sharing a central vertical stem.
- Design work consistently needs faithful reproduction of the reference image rather than creative reinterpretation.

**Voice**
- AI voice clone trained via Higgsfield's Create Voice tool for the PTH brand, using a custom script covering varied phonemes and brand-specific delivery.

## Open items
- Placeholder URLs remain in the final HTML — need Dylan's real links to platforms/socials before launch.
- Hosting and deployment — Dylan wants step-by-step guidance here (not highly technical, needs implementation walked through).
- Backend (exploratory, not committed): considered a VPS, SQLite, and a CRM for a potential PTH backend.
- Tooling for future dev work: looked at Emergent AI and Claude Code as options.

## Notes for whoever picks this up
- Dylan prefers direct, faithful execution over creative liberties on visual assets.
- Step-by-step guidance is needed for anything hosting/deployment-related — don't assume familiarity with servers, DNS, etc.
