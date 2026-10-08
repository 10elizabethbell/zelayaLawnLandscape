# Zelaya Lawn & Landscape — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/zelayaLawnLandscape · **Built:** 2026-10-08 from Muse brief (run 2026-10-08, FB group post 4158275421136960)

## What's built
- Single file, 42 KB, no images and no web fonts, so it loads instantly on cellular. Phone layout first, desktop added from 760px up.
- **World: autumn lawn.** Deep-green diagonal mowing stripes (no black), the logo's lime and chrome as trim, and leaf orange, red and gold as the only warm notes.
- **Signature:** a canvas grass band along the hero's bottom (about 370 blades on a phone, about 1,200 on desktop) that sways in three layered sine waves and parts under a finger or mouse, springing back with a wobble. Maple and ovate leaves fall, tumble and settle into the grass; the pointer works as a **leaf blower** that kicks settled leaves back up and carries them along. Gusts sweep across every 6–10s and lift the leaves again.
- **Carried down the page:** a few leaves drift over the sections below the hero and can be blown too. Every section break is a rolling turf seam (three moving lines, with the next section's color filling up to the middle line).
- **Sections:** hero ("Leaves gone. Yard ready for winter.", towns, 10%-off chip, Text and Call buttons) → Year-round care (services grouped Fall / Winter / Lawn, beds & landscape; each row texts Zelaya with that service pre-filled) → Getting on the schedule (3 steps on a cream ground, their "Reliable service. Quality work. Year-round care.") → Service area (town chips) → Close (Z mark, wordmark, their "Your property deserves professional care" and "don't wait" lines, buttons, offer) → footer with "Demo one-pager — free sample."
- **Contact:** `sms:+15515003832?&body=…` with a pre-filled message ("Hi Zelaya Lawn & Landscape! I'd like a free estimate for <service>. Town/address: / Best time to reach me:") plus `tel:`. On phones, a sticky Text + Call bar appears once the hero buttons scroll away and hides again at the closing buttons.
- Tunable constants are named at the top of each IIFE: blade density, grass height, leaf count and size, blower radius and strength, spring K/D, gust interval, seam speed.

## Assumptions I made
- **Logo is a hand-drawn SVG redraw** of the chrome "Z" with two green leaves, taken from the flyer (the flyer's logo sits on a photo, so a clean crop wasn't possible). The wordmark is set in a system serif to echo their chrome serif. Swap in the owner's original logo file when we have it.
- **The flyer's photos were not used.** They look AI-generated (generic estate homes, lit pavers), so showing them as Zelaya's work would be dishonest. The page has no photos at all.
- **Season grouping is inferred:** fall = cleanups and leaf removal, winter = snow removal, everything else under "Lawn, beds & landscape". The "booking now" and "reserve a spot" tags are inferred from their "now booking" and "secure your spot" copy.
- Duplicate flyer services were merged: "Shrub trimming" + "Shrub & hedge trimming", and "Mulch installation" kept separate from "Mulch & bed maintenance".
- **Oakland** was added to the area from the flyer; the post caption omitted it.
- The offer's year is assumed to be 2026 ("through Dec 31").
- The steps copy ("Say what you need and your town", "Zelaya gives you a free estimate") is my phrasing around their "Call or text for your FREE estimate".
- Headline "Leaves gone. Yard ready for winter." is mine, a benefit line in place of their "FALL CLEANUPS NOW BOOKING" (which survives as "Now booking" in the chip).
- Colors: ground #12301e, lime #7cc242 (from the logo leaf), chrome #d9dee2, gold chip #e6b33c.

## Placeholders and gaps
- No real work photos, before/afters, reviews, hours, owner name, email, or years in business. The page says nothing about any of them.
- No original logo file.
- After Dec 31 the offer copy goes stale and needs removing (3 places: hero chip, step 3, close chip).

## Questions for the owner
- Can you send 5–10 photos of real jobs (cleanups, mulch beds, hardscapes), ideally before/after pairs?
- Do you have the logo as a file (PNG/SVG/AI)?
- What are your hours, and should texts get a reply the same day?
- Who should the page name: your first name, and how long you've been in business?
- Snow removal: do you take seasonal contracts? It would be worth its own "reserve now" block.
- Which services do you most want more of (hardscapes and design are higher-ticket)?
- Any Google reviews or customer texts we could quote, with permission?

## Ideas not built (yours to pick)
- **Runner-up world: first snow.** Snowflakes that drift and swirl away from your finger over evergreen hedges, with snow settling on the seams. Could even swap in automatically on Dec 1 so the page sells snow removal all winter (season switch by date).
- Other candidates considered: fresh-cut mowing stripes as the full motif, mulch-bed and spade-edge textures, lantern-lit hardscape pavers (the flyer's look), sprinkler arcs and dew, drainage contour lines.
- A booking form page (`book.html`) that composes the same pre-filled text: name, phone, town, services (multi-select), property type (residential/commercial), notes.
- Before/after sliders once real pairs exist (put one in the empty right column on desktop beside the fall rows).
- Leaves could pile up against the bottom seam and get swept off by a slow "rake" pass.
- A small "Snow removal spots for 2026–27: text to reserve" banner from mid-November.
- Spanish-language toggle, if the owner wants it.

## Not verified
- Real-device touch feel and frame rate (tested only with simulated touch and mouse in headless Chrome).
- The SMS hand-off with a pre-filled body on real iOS and Android, especially inside Facebook's in-app browser.
- The sticky bar's behavior with the in-app browser's own bottom toolbar.
- How the system serif wordmark renders on Android (falls back to Georgia or a default serif).
