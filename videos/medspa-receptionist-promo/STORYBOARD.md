---
format: 1080x1920
duration: 35s
message: "Never miss another booking — an AI receptionist that answers every WhatsApp message and phone call, and books the appointment automatically."
arc: PAS (Pain → Agitation → Solution → Proof → CTA)
audience: Dubai med spa and aesthetic clinic owners considering hiring an automation consultant
mode: autonomous
music: none
---

## Video direction

- **Palette** (from `frame.md`, editorial-forest remixed onto this brand): ink `#2B1E24` for text/dark surfaces, canvas `#FFFFFF` and cream `#FBF6F4`/`#F4E9E8` for grounds, `#7A1F3D` (rose-deep) as the one saturated accent for CTAs/highlights/dark cards, `#C24868` (rose) as a secondary warm tint. Display type by role "display" (Lora); body/support type by role "body" (Raleway).
- **Motion grammar + reveal model**: long-tail `power3` eases throughout, never bouncy. This video is **silent** (no narration was available — see BRIEF.md) — every frame's reveal is paced to its own on-screen text/UI beats in place of spoken cues: at t=0 only the first cue is on screen, each further line or element reveals in its own window across the frame, nothing dumps at once. Once content resolves it holds and reads; at most a subtle 1–2px idle drift, never lazy breathing.
- **Rhythm / held-frame allocation**: Frame 3 (the turn) and Frame 7 (close) are the deliberate held/breather beats — near-still title cards giving the eye rest between the kinetic stat/pain beats and the two live-demo beats. Frames 4–5 (WhatsApp, call) are the busiest — real conversational proof, paced bubble by bubble.
- **Negative list**: no purple/blue "AI" gradients, no bokeh, no browser chrome/cursors/scrollbars, no pure black or pure white fields, no front-load-then-freeze, no aimless screensaver drift — every moving element ties to its own cue.

## Frame 1 — The stat

- scene: Cold open on cream ground. One huge number counts up center-frame: "62%". Beneath it, a smaller line resolves: "of med spa calls go unanswered."
- voiceover:
- duration: 4s
- transition_in: cut
- status: animated
- src: compositions/frames/01-stat.html
- type: hook
- persuasion: Statistical proof
- beat: anxiety
- blueprint: dataviz-countup
- asset_candidates:

narrativeRole: Open on the sharpest real number to create immediate tension before naming the product.
keyMessage: Most med spa calls go unanswered.

blueprint: dataviz-countup (Adapt — drop the ring/chart, keep the count-up-to-hero-number signature; too short a frame for the full instrument traversal)
Scene 1 (0.0–2.0s): solid cream ground (#FBF6F4); centered template, ~55% of frame height. One huge Lora-display numeral counts up 0→62, trailing "%" settling last, ink #2B1E24, long-tail ease on the count.
Scene 2 (2.0–4.0s): as the number settles, a smaller Raleway label slides up beneath it — "of med spa calls go unanswered" — with a short rose-deep #7A1F3D underline drawing in on the same beat. Holds fully still to end.

## Frame 2 — The cost

- scene: Three short pain lines land solo in sequence on the same cream ground: "85% never call back." then "That's AED 475K+ lost every year." then "One missed call is one lost client."
- voiceover:
- duration: 5s
- transition_in: crossfade
- status: animated
- src: compositions/frames/02-cost.html
- type: pain_point
- persuasion: Pain agitation
- beat: frustration
- blueprint: kinetic-type-beats
- asset_candidates:

narrativeRole: Escalate the opening stat into a felt, specific cost.
keyMessage: Missed calls are a real, expensive, ongoing loss.

blueprint: kinetic-type-beats (Reproduce — staccato phrase reveal, one line at a time)
Scene 1 (0.0–1.6s): cream ground; centered template. "85% never call back." punches in (scale 0.9→1, long-tail ease), holds briefly, clears.
Scene 2 (1.6–3.3s): "That's AED 475K+ lost every year." punches in the same position; the "AED 475K+" portion set in rose-deep #7A1F3D for hierarchy. Holds, clears.
Scene 3 (3.3–5.0s): "One missed call is one lost client." punches in and holds to end — the frame's final held read, no clear.

## Frame 3 — The turn

- scene: Calm title card on rose-deep ground, cream serif type: "An AI receptionist that never misses a call." Holds still, low motion.
- voiceover:
- duration: 4s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-turn.html
- type: product_intro
- persuasion: Friction reduction
- beat: relief
- blueprint: titlecard-reveal
- asset_candidates:

narrativeRole: Pivot from pain to the promise — the section boundary of the video.
keyMessage: The fix is an AI receptionist that always answers.

blueprint: titlecard-reveal (Reproduce — near-still card, blur-snap into focus)
Scene 1 (0.0–1.5s): full-bleed rose-deep #7A1F3D ground; centered template. Title blur-snaps into focus: "An AI receptionist" in cream Lora-display, upper-middle third.
Scene 2 (1.5–4.0s): second line settles beneath on a soft crossfade-up: "that never misses a call." completing the sentence. Holds fully still to end — a deliberate breather beat.

## Frame 4 — WhatsApp, live

- scene: A recreated WhatsApp-style exchange, matching the real conversation on the demo site: a client (Layla Haddad) asks about a HydraFacial slot this Thursday; the reply offers two real times instantly; she confirms; a "booked, added to calendar automatically" chip lands.
- voiceover:
- duration: 6s
- transition_in: crossfade
- status: animated
- src: compositions/frames/04-whatsapp.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: curiosity + clarity
- blueprint: device-surface-showcase
- asset_candidates:

narrativeRole: Prove the WhatsApp channel works, using the real sample exchange from the live site rather than a generic mockup.
keyMessage: WhatsApp enquiries get answered and booked instantly, start to finish.

blueprint: device-surface-showcase (Reproduce — the product doing its real steps inside a real chat surface, cursorless, stepwise)
Scene 1 (0.0–1.2s): cream ground #FBF6F4; asymmetric 60/40 layout, a phone-frame chat surface seats right-of-center (~45% of frame width), empty at open, "Layla Haddad" name label at its head.
Scene 2 (1.2–2.6s): incoming bubble (white, left-aligned) settles in the surface: "Hi, do you have anything for a HydraFacial this Thursday afternoon?"
Scene 3 (2.6–4.2s): reply bubble (rose-deep #7A1F3D fill, right-aligned) settles beneath: "We have 3:30pm or 5pm open this Thursday. Which works better for you?"
Scene 4 (4.2–5.2s): confirm bubble settles: "3:30 works great" (white, left).
Scene 5 (5.2–6.0s): a green "Booked — added to calendar automatically" chip pops in beneath the thread on a long-tail scale-in and holds to end.

## Frame 5 — A call, answered

- scene: A recreated inbound call exchange, matching the site's real sample: a caller asks about lip filler pricing and weekend availability; a natural reply gives pricing and a real slot; the caller books it on the call.
- voiceover:
- duration: 6s
- transition_in: crossfade
- status: animated
- src: compositions/frames/05-call.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: curiosity + clarity
- blueprint: device-surface-showcase
- asset_candidates:

narrativeRole: Prove the phone channel works the same way, completing the two-channel promise from Frame 3.
keyMessage: Phone enquiries get the same instant, natural handling.

blueprint: device-surface-showcase (Reproduce — same shape as Frame 4, voice surface instead of chat, mirrored layout for variety)
Scene 1 (0.0–1.2s): cream ground; asymmetric 60/40 mirrored from Frame 4 (surface left-of-center this time), "Inbound call" label + a soft waveform glyph at its head.
Scene 2 (1.2–2.8s): caller line settles: "Do you have anything for lip filler this weekend, and what's the pricing?"
Scene 3 (2.8–4.4s): reply line settles beneath in rose-deep #7A1F3D: "Filler starts from AED 1,200. I have Saturday 1pm or Sunday 11am open."
Scene 4 (4.4–5.4s): caller line settles: "Saturday 1pm is perfect."
Scene 5 (5.4–6.0s): a "Booked — Saturday 1:00pm" chip pops in on the same treatment as Frame 4's confirm chip (the video's recurring "booked" signature) and holds to end.

## Frame 6 — What it does, every time

- scene: Short value lines land in rhythm over a soft, warm photograph of a real spa treatment tray: "Checks your calendar live." then "Books automatically." then "Every time."
- voiceover:
- duration: 4s
- transition_in: crossfade
- status: animated
- src: compositions/frames/06-benefit.html
- type: benefit_highlight
- persuasion: Value stacking
- beat: confidence
- blueprint: kinetic-type-beats
- asset_candidates: assets/spa-treatment-tray-with-a-lit-candle-rol.jpg — warm spa treatment tray with candle, on-brand ambiance texture

narrativeRole: Compress the mechanism into three plain, confident claims before the close.
keyMessage: It checks availability and books on its own, reliably.

blueprint: kinetic-type-beats (Adapt — staccato lines over a dimmed photo backdrop instead of flat color)
focal: assets/spa-treatment-tray-with-a-lit-candle-rol.jpg
roles: spa-treatment-tray = background (dim ~45%, cream-to-transparent gradient over it)
Scene 1 (0.0–1.3s): full-bleed background photo dimmed ~45% under the gradient; centered template. "Checks your calendar live." punches in, cream text with soft shadow for legibility.
Scene 2 (1.3–2.6s): line clears, "Books automatically." punches in the same position.
Scene 3 (2.6–4.0s): line clears, "Every time." punches in at heavier weight (800 vs 400) for the escalating close, holds to end.

## Frame 7 — Close

- scene: A warm, softly lit spa treatment room photograph dims under a gradient; cream serif type settles center: "Never miss another booking." Beneath it, a smaller line: "Get this built for your business."
- voiceover:
- duration: 4s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/07-close.html
- type: cta
- persuasion: Risk reversal
- beat: peace of mind
- blueprint: titlecard-reveal
- asset_candidates: assets/warm-softly-lit-spa-treatment-room-with-.jpg — warm softly lit spa treatment room, closing ambiance

narrativeRole: Land the thesis line already used as the site's own headline, then hand off to the CTA.
keyMessage: Never miss another booking — message to get started.

blueprint: titlecard-reveal (Reproduce — calm end-card, blur-snap, held to the very end)
focal: assets/warm-softly-lit-spa-treatment-room-with-.jpg
roles: warm-spa-room = background (dim ~50%, rose-deep-to-transparent gradient rising from the bottom)
Scene 1 (0.0–1.5s): full-bleed background photo dimmed under the gradient; centered template. Headline blur-snaps into focus: "Never miss another booking." in cream Lora-display, upper-middle third.
Scene 2 (1.5–4.0s): CTA line settles beneath on a soft crossfade-up: "Get this built for your business." in Raleway, smaller weight. Holds fully still to end — the video's final read.
