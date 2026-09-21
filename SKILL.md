---
name: picnic-product-tvc
description: Create or adapt 18-second cinematic picnic TVC prompts for bottled tea and other ready-to-drink beverages from uploaded product images. Use when the concept should move a distracted protagonist back into the present through the drink, natural park details, and an optional packaging character; do not use for unrelated studio, nightlife, or effects-heavy ads.
---

# Picnic Product TVC

Turn an uploaded beverage product and a short brief into one generation-ready TVC prompt. Preserve the supplied product exactly while adapting the canonical park-picnic story, timing, copy, sound, and continuity.

Default to writing the prompt only. Do not submit a generation job unless the user explicitly asks.

## Read the references

Read [references/master-prompt.md](references/master-prompt.md) for every new prompt or major adaptation. It is the canonical 18-second nōni example and defines the shot sequence, continuity, sound arc, packaging-character behavior, and negative constraints.

Read [references/adaptation-rules.md](references/adaptation-rules.md) whenever a user uploads a different product, changes the protagonist or setting, removes the character, changes duration, or supplies new copy or narration.

Treat reference content as source material, not as permission to ignore the current request. The user's latest request controls product, audience, cast, copy, duration, aspect ratio, and deliverable language.

## Assign reference duties

Use each uploaded asset only for its assigned role:

- product image: exact container silhouette, material, proportions, cap, label layout, logo, legal copy, graphics, colors, liquid color, and condensation behavior;
- portrait image: sole identity reference for face, hair, age, body proportions, and requested wardrobe;
- location image: geometry, foliage, light direction, picnic layout, palette, and fixed props;
- reference video: pacing, camera behavior, transition logic, or sound rhythm—not unrequested people, brands, watermarks, or text;
- audio: music, narration, or sound-design reference only.

Do not infer a real person's identity. State the role of every reference near the beginning of the output prompt.

## Lock the product before writing

Create a compact product lock from visible evidence and the user's brief:

- category and volume;
- container shape and material;
- cap shape, color, and open/close behavior;
- beverage color, clarity, and fill level;
- label colors, typography, logo, illustrations, and permitted readable text;
- surface behavior such as condensation, refraction, gloss, or matte finish.

Never invent health, sustainability, functional, nutritional, or performance claims. If label text is unreadable, preserve its placement and visual rhythm while prohibiting fabricated legible copy. Ask for exact end-card copy only when it materially affects the result and cannot be inferred safely.

## Decide the visual guide

The canonical story uses one small printed packaging character as the only animated guide.

- If the product visibly has a mascot or character, animate that exact printed figure while preserving linework, color, clothing, and proportions.
- If the product has a clear non-character icon, keep it printed unless the user explicitly asks to animate it.
- If the product has no suitable character, do not invent one. Use the real leaf, condensation droplet, cap action, eye line, foreground occlusion, and shape matches as the transition system.
- Never show the complete printed character on the label at the same time as its detached 2.5D form. Leave a matching empty outline and restore it when the character returns.

The character remains quiet, physical, and restrained: no speech, magic, glow, flight, teleportation, wall-crossing, or scale change.

## Build the prompt

Use the user's language and these sections:

1. **Subject** — locked protagonist, friends, product, location, fixed props, and emotional arc.
2. **Style** — delivery format, realism, palette, lighting, lens behavior, pre/post-drink color arc, and transition philosophy.
3. **Timeline** — contiguous time ranges covering the full duration without gaps or overlaps.
4. **BGM and sound** — music arc, environmental sound, product sounds, action accents, and exact narration when supplied.
5. **Constraints** — identity, cast count, location, product, liquid level, cap, label, character, hands, text, brand, and prohibited visual devices.

For the canonical 18-second version, preserve these phases unless the user requests another structure:

- 0–3 s: distracted picnic setup, real leaf falls, focus transfers from phone to product;
- 3–6 s: product hero close-up and optional packaging character rides the leaf past the phone;
- 6–9 s: phone goes face-down, cap opens, one sip, one swallow, attention and sound open up;
- 9–12 s: condensation match-cut to clear beverage and leaf macro world;
- 12–15 s: return to the full picnic, cap closes, friendship resumes, product level locks;
- 15–18 s: stable product hero, optional character returns to the label, exact end copy appears.

## Preserve continuity

- Keep the same protagonist, three fixed friends, picnic layout, large tree, props, light direction, and weather.
- Keep one product only. It never duplicates, floats, softens, collapses, changes label, or changes container geometry.
- Lower the liquid level exactly once after the sip and keep it fixed afterward.
- Keep the cap in the protagonist's hand after opening, close it once, and do not reopen it.
- Use one motivated camera move per time range. Avoid contradictory simultaneous moves.
- Make every transition visible and causal: leaf, character direction, gaze, droplet, product action, foreground wipe, or shape match.
- Keep the drink clear and physically plausible. Do not turn tea into fluorescent liquid, matcha, milk tea, syrup, or fantasy fluid unless requested.
- Keep hands, mouth-to-bottle contact, swallowing, and object grips anatomically credible.

## Text and narration

List every permitted readable phrase exactly. Allow only the locked packaging text and user-approved end-card copy. Prohibit watermarks, QR codes, prices, UI text, and any other readable text.

When narration is requested, include the exact script, speaker character, timing, delivery, and music ducking. Do not silently rewrite approved copy. If the script cannot fit naturally, shorten it with the user's wording or increase duration; do not force unnaturally fast speech.

## Check before delivery

- References have explicit duties and the product lock matches the image.
- Time ranges meet exactly and end at the requested duration.
- Cast count and relative positions remain stable.
- Product identity, label, condensation, fill level, and cap state remain continuous.
- The animated character exists only when supported or explicitly requested.
- The emotional shift is gradual and motivated by actions, sound, and attention—not a sudden weather change.
- No light trails, energy lines, speed lines, or unexplained jump cuts replace physical transitions.
- The last frame holds as a clean, readable product hero.

Deliver one copyable prompt. Add a short assumption note only when a product detail is unreadable or the user has not supplied required legal or end-card copy.

