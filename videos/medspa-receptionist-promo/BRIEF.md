---
workflow: product-launch-video
flow: automation
storyboard: no
format: 1080x1920
length: 35s
style_preset: <chosen in Step 2>
---

## Intent

A short vertical promo/explainer for "AI Receptionist for Med Spas" — a sample portfolio build showing an AI receptionist that answers WhatsApp and phone enquiries for Dubai med spas, checks calendar availability, and books appointments automatically. This is a demo/portfolio piece used to win freelance clients, not a live SaaS product.

Site to capture: https://singhgenics.github.io/medspa-receptionist-demo/

## Brand

- Primary: rose #C24868
- Accent: deep rose/burgundy #7A1F3D
- Backgrounds: cream/blush #FBF6F4, #F4E9E8
- Ink: #2B1E24
- Display font: Lora (serif)
- Body font: Raleway (sans)
- Tone: calm, luxurious, boutique-wellness. Must not read as a tech dashboard or generic AI-agency template.

## Story content (all real, sourced — already live on the demo site)

- Problem: 62% of med spa calls go unanswered; 85% of those callers never call back; missed calls cost the average med spa AED 475K+/year; average client lifetime value AED 29K+.
- Solution: an AI receptionist answers every WhatsApp message and phone call instantly, holds a natural conversation, checks calendar availability live, and books the appointment automatically.
- Proof: WhatsApp exchange with a client (Layla Haddad) booking a HydraFacial slot, confirmed automatically. Voice call from a caller asking about lip filler pricing/availability, booked on the call.
- Close: "Never miss another booking." + call to action to get this built.

## Customizations

**Hard constraint — applies to narration, on-screen text, and every visual label:** never name a specific AI model, automation platform, calendar app, or messaging API/vendor (no "Claude", no "Make"/"Make.com", no "Vapi", no "Google Calendar", no "WhatsApp Business API"). Describe capabilities only. This mirrors a fix already applied to the live demo site and pitch deck for this same client — the tech stack stays undisclosed to prospects.

## Notes

- Routed via /hyperframes intent layer, priority-8 match (real product + real demo site → product-launch-video, not faceless-explainer).
- No BRIEF existed before this run; no recipes or remembered preferences were on file (checked, both empty) — this is the first HyperFrames project for this workspace.
- `flow: automation`, `storyboard: no` locked from the user's explicit "I'm running autonomously... proceed through gates with brief heads-up summaries rather than blocking questions" instruction — treated per brief-contract as the "just build it / don't ask" signal. Unanswered fields are decisions made here with receipts below, not open questions.
- Format locked to vertical 1080x1920 (portfolio/social share use) — inferred, not explicitly requested; flagged as a decision.
- Length locked to ~35s (mid-point of the requested 30-45s range) — inferred.
- Style preset: decided in Step 2 against the brand tokens above, favoring an editorial/clean preset over anything cartoonish or techy, to match the boutique-wellness tone.
- Audio: not signed into HeyGen; local offline engines (Kokoro, MusicGen) not installed. User chose **silent, captions-only** — no narration, no BGM. `music: none` and no SCRIPT.md in Step 3.
