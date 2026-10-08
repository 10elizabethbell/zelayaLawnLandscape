---
name: Zelaya Lawn & Landscape
description: Seasonal property-care one-pager on striped lawn green, with grass and leaves you can blow around and a one-tap text for a free estimate.
colors:
  ground: "#12301e"
  ground-2: "#0f2819"
  ground-3: "#0c2215"
  stripe: "#15361f"
  cream: "#f2eee1"
  ink: "#0f2819"
  ink-soft: "#3c5544"
  text: "#eef3ea"
  text-soft: "#b9cbb9"
  lime: "#7cc242"
  lime-bright: "#8fd352"
  lime-deep: "#5c9f2c"
  chrome: "#d9dee2"
  leaf-gold: "#e6b33c"
  leaf-orange: "#e07a2c"
  leaf-red: "#c6452c"
  gold-ink: "#2a1a05"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.35rem, 10.4vw, 5.6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8.6vw, 4rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.18rem"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.005em"
  season:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "0.06em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  pitch:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.0625rem, 4.4vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.4
  label-button:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.01em"
  wordmark:
    fontFamily: "\"Iowan Old Style\", \"Palatino Linotype\", Palatino, \"Book Antiqua\", Georgia, serif"
    fontSize: "clamp(2.3rem, 11vw, 4.5rem)"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.08em"
  serif-statement:
    fontFamily: "\"Iowan Old Style\", \"Palatino Linotype\", Palatino, \"Book Antiqua\", Georgia, serif"
    fontSize: "clamp(1.25rem, 5.4vw, 1.75rem)"
    fontWeight: 700
    lineHeight: 1.25
  label-lockup:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.3em"
rounded:
  pill: "999px"
  circle: "50%"
  focus: "10px"
  chip-organic: "6px 14px 8px 16px"
  swatch-organic: "10px 26px 8px 30px"
spacing:
  gutter-phone: "16px"
  gutter-desktop: "40px"
  button-gap: "12px"
  chip-gap: "10px"
  season-gap: "40px"
  section-top-phone: "36px"
  section-bottom-phone: "84px"
  section-top-desktop: "56px"
  section-bottom-desktop: "120px"
  grass-pad-phone: "150px"
  grass-pad-desktop: "200px"
components:
  button-primary:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.ground-3}"
    typography: "{typography.label-button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.lime-bright}"
    textColor: "{colors.ground-3}"
  button-ghost:
    backgroundColor: "rgba(15,40,25,.55)"
    textColor: "{colors.text}"
    typography: "{typography.label-button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "58px"
  button-ghost-hover:
    backgroundColor: "rgba(124,194,66,.14)"
    textColor: "{colors.text}"
  service-row:
    textColor: "{colors.text}"
    typography: "{typography.title}"
    padding: "12px 2px"
    height: "64px"
  service-row-go:
    backgroundColor: "rgba(124,194,66,.14)"
    textColor: "{colors.lime}"
    rounded: "{rounded.circle}"
    size: "40px"
  service-row-go-hover:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.ground-3}"
  offer-chip:
    backgroundColor: "{colors.leaf-gold}"
    textColor: "{colors.gold-ink}"
    rounded: "{rounded.chip-organic}"
    padding: "9px 16px 9px 12px"
  deal-swatch:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.ground-3}"
    rounded: "{rounded.swatch-organic}"
    padding: "22px 30px"
  town-chip:
    backgroundColor: "rgba(124,194,66,.12)"
    textColor: "{colors.text}"
    rounded: "{rounded.pill}"
    padding: "10px 16px"
  town-chip-more:
    backgroundColor: "transparent"
    textColor: "{colors.text-soft}"
    rounded: "{rounded.pill}"
    padding: "10px 16px"
  step-leaf:
    size: "52px"
  sticky-bar:
    backgroundColor: "rgba(12,34,21,.94)"
    padding: "10px 12px"
  sticky-bar-button:
    height: "54px"
---

# Design System: Zelaya Lawn & Landscape

## Overview

**Creative North Star: "The Yard You Can Touch"**

The page is a fall lawn, not a website about one. The ground is deep lawn green cut into diagonal mowing stripes; grass grows along the bottom of the opening and closing bands, autumn leaves fall onto it, and a finger or cursor blows them away like a leaf blower. Sections meet at rolling turf seams rather than straight edges. Everything else stays out of the way of one action: text Zelaya for a free estimate.

The voice is the owner's flyer, promoted: heavy uppercase sans headlines that read like a yard sign, the chrome-serif ZELAYA wordmark from the logo, logo lime and chrome silver as trim, and maple orange, red and gold as the only warm notes. The type stack is the system's own sans and serif, no web fonts; this is the owner's house style and a deliberate choice, not a fallback. Density is phone-first and generous: big tap targets, short service rows, one pair of buttons repeated unchanged.

Confirmed rejections: black grounds (the flyer is black; the page is green), glow shadows, thin highlight rims, stock or AI photography shown as Zelaya's work, and any fact the owner has not stated.

**Key Characteristics:**
- Deep green ground in 115° mowing stripes, never black.
- Living turf: canvas grass and blowable leaves in the hero and the close; a few leaves drift down the page.
- Rolling turf seams between every section.
- Uppercase 900-weight system sans for display; chrome system serif for the wordmark and the promise line.
- One button pair (Text primary, Call ghost), pill-shaped, identical everywhere it appears.
- Warm leaf colors only on the offer and the step leaves; lime carries every action.

## Colors

A lawn at dusk: three steps of deep green ground, a cream clearing, logo lime and chrome for trim, and three autumn leaf colors as the only warmth.

### Primary
- **Logo Leaf Lime** (lime): every action. Primary button fill, focus ring, selection, service-row arrows, season heads, the "Yard ready for winter." half of the hero headline, the wordmark subline, footer links, the deal swatch, and the middle stroke of every turf seam.
- **Sunlit Lime** (lime-bright): primary button hover only.
- **Mown Lime** (lime-deep): link underline color on cream and the scrollbar thumb; the lime that survives on a light ground as a line, never as text.

### Secondary
- **Chrome Silver** (chrome): the ZELAYA wordmark in the top bar and the close, nothing else. The Z mark itself is a chrome gradient (#f6f8f9 to #7b858b) with a lime leaf; it is the logo, not a palette.

### Tertiary
- **Maple Gold** (leaf-gold): the 10%-off offer chip and step leaf 1. Text on it is **Bark Ink** (gold-ink).
- **Maple Orange** (leaf-orange): step leaf 2.
- **Maple Red** (leaf-red): step leaf 3.
- The canvas leaves use their own five radial-gradient pairs in the same family (orange, red, gold, rust, amber); they are sprite pigment, not UI color.

### Neutral
- **Lawn Green** (ground): page ground, hero and area (striped with **Mowing Stripe**, stripe), browser theme color.
- **Shade Green** (ground-2): services and close sections.
- **Night Green** (ground-3): footer, text on lime, sticky bar base.
- **Clearing Cream** (cream): the one light section ("Getting on the schedule").
- **Field Ink** (ink, same value as ground-2) and **Moss Ink** (ink-soft): headline and body text on cream.
- **Frost** (text) and **Sage** (text-soft): headline and supporting text on green.
- Hairline dividers between service rows are Sage at 18% alpha (1px).

### Named Rules
**The Green Ground Rule.** The darkest surface is Night Green. No section, bar, overlay or card is black or neutral grey; translucent layers are green-tinted (rgba(12,34,21,.94), rgba(15,40,25,.55)).

**The Lime Means Act Rule.** Lime is the color of action, the offer and the living turf (buttons, arrows, focus, the deal, seams, season heads, the headline's second clause). Warm leaf colors never sit on a button, and no button is any color but lime or the green ghost.

## Typography

**Display Font:** System sans (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same system sans
**Wordmark Font:** System serif (Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia)

**Character:** A yard sign and a brass nameplate. The sans shouts in heavy uppercase like the flyer's "FALL CLEANUPS NOW BOOKING"; the serif is reserved for the name and the owner's own promise, set wide and chrome. No web fonts: the page loads on cellular in a Facebook in-app browser, and the system stack is the owner's chosen house style.

### Hierarchy
- **Display** (900, clamp 2.35rem to 5.6rem, line-height 0.95, uppercase, -0.02em, balanced wrap): the hero headline only. Its second clause turns lime.
- **Headline** (900, clamp 2rem to 4rem, 0.95, uppercase): section heads. The close's headline is a smaller step (clamp 1.6rem to 2.8rem, max 18ch) because it sits under the wordmark.
- **Season** (900, 1.05rem, uppercase, +0.06em, lime): season group heads, paired with a 30px line icon.
- **Title** (800, 1.18rem, 1.15, uppercase): service row names. Step titles use the same uppercase sans at 1.25rem/1.1.
- **Body** (400, 1.0625rem, 1.55): all running text, Sage on green or Moss Ink on cream; measure 34 to 46ch.
- **Pitch** (400, clamp 1.0625rem to 1.25rem, 1.4): the hero sentence, with town names in bold Frost.
- **Button label** (800, 1.0625rem, +0.01em, sentence case).
- **Wordmark** (serif 700, +0.08em, uppercase, chrome): ZELAYA at 1.3rem (1.6rem desktop) in the top bar, clamp 2.3rem to 4.5rem in the close.
- **Serif statement** (serif 700, clamp 1.25rem to 1.75rem, 1.25, max 28ch): the owner's promise line on cream.
- **Lockup label** (sans 600 to 700, 0.66rem to 0.8rem, +0.2em to +0.3em, uppercase, lime): "LAWN & LANDSCAPE" under the wordmark only, as part of the logo lockup.

### Named Rules
**The Shout and Sign Rule.** Headings are uppercase 900 sans; sentences are sentence case 400. Nothing in between gets uppercase except the logo lockup.

**The Serif Is the Name Rule.** The serif appears only for the ZELAYA wordmark and the owner's own promise line. It never sets a heading, button or body text.

## Layout

Phone-first single column at a 16px gutter, widening to a 40px gutter and a 1200px max container at 760px (the only breakpoint; scripts treat ≤759px as phone and scale every motion constant down). Rhythm on phones is about 28 to 44px above a section and 80 to 84px below; on desktop 48 to 72px above and 120px below. The hero and the close add a 150px (200px desktop) bottom band for the grass to live in.

- **First phone screen:** logo bar, display headline, pitch with towns, offer chip, then full-width stacked Text and Call buttons, with grass and leaves underneath.
- **Desktop:** the hero splits 1.35fr / 0.65fr with the large Z mark on the right; buttons sit side by side at their natural width; services become two columns (Fall and Winter plus the deal swatch on the left, the lawn-and-landscape list spanning the right); steps go three across; area splits heading and town chips 1fr / 1fr.
- **Sticky bar (phones only):** appears once both the hero and close button pairs are out of view, and pads the body by 78px while shown.

**The Thumb Rule.** Every tap target is at least 44px; buttons are 58px tall on phones (54px in the sticky bar, 62px desktop) and service rows are 64px.

## Elevation & Depth

Depth is physical, not interface chrome: grass blades drawn back to front, leaves resting in front of or behind blades by depth, and turf seams overlapping the section below. Shadows are few, dark, downward, and spread-negative so they read as something sitting on the lawn.

### Shadow Vocabulary
- **Button lift** (`box-shadow: 0 8px 20px -8px rgba(4,18,9,.6)`): primary button only.
- **Chip set-down** (`box-shadow: 0 6px 18px -8px rgba(0,0,0,.5)`): the tilted offer chip.
- **Swatch set-down** (`box-shadow: 0 14px 30px -14px rgba(4,18,9,.7)`): the desktop deal swatch.
- **Bar cast** (`box-shadow: 0 -10px 30px -12px rgba(0,0,0,.6)`): the sticky bar casting upward onto the page.
- **Mark drop** (`filter: drop-shadow(0 22px 30px rgba(5,20,10,.55))`): the desktop hero Z mark.

### Named Rules
**The Lying-on-Grass Rule.** A shadow is always dark, offset away from the light, and tighter than its blur (negative spread). No colored glows, no zero-offset halos, no inner highlights.

## Shapes

Two families. Controls are fully round: pill buttons, pill town chips, circular arrow wells and the circular phone button. Promotional pieces are hand-cut: the offer chip (6px 14px 8px 16px, tilted -1.5°) and the deal swatch (10px 26px 8px 30px, tilted -2°) have unequal corners and a slight rotation, like a tag stapled to a flyer. Section edges are never straight; they are the rolling turf seams. Focus rings are a 3px lime outline with a 3px offset and 10px corners.

**The Cut Tag Rule.** Only the offer and the deal get asymmetric corners and a tilt. Everything you tap is perfectly round.

## Components

### Buttons
Big, round and identical everywhere; the Text action always comes first.
- **Shape:** full pill (999px), 2px lime border on both variants.
- **Primary (Text for a free estimate):** lime fill, Night Green label with a message line icon, button-lift shadow. Opens SMS with a pre-filled message naming the service.
- **Ghost (Call):** green-tinted translucent fill, Frost label, phone icon, number shown inline.
- **Hover (hover-capable devices only):** primary lightens to Sunlit Lime, ghost takes a 14% lime wash; both rise 2px. Press scales to 0.97. Transform eases on cubic-bezier(.16,1,.3,1) over 0.25s.
- **Layout:** stacked full width on phones, side by side at natural width from 760px.

### Service Rows
A list, not cards: each service is one tappable row that texts Zelaya with that service filled in.
- Uppercase 800 title, optional Sage subline, 1px Sage-18% hairline above each row and below the last.
- Right-aligned 40px circular arrow well, 14% lime wash with a lime arrow; on hover it fills lime and slides 4px right; on press it scales to 0.9.

### Season Heads
A 30px lime line icon (leaf, snowflake, sprout), the season name in the Season style, and an optional right-aligned Sage note ("booking now", "next up"). Groups are Fall, Winter, and Lawn, beds & landscape.

### Offer Chip and Deal Swatch
- **Offer chip:** inline Maple Gold tag with a tag icon, 800 sans at 0.95rem in Bark Ink, cut-tag corners, -1.5° tilt, chip set-down shadow. Appears in the hero and the close.
- **Deal swatch (desktop only):** lime block in the services grid, 900 uppercase sans at 2.4rem with an 800 subline, cut-tag corners, -2° tilt, swatch set-down shadow.

### Town Chips
Pills with a 12% lime wash and a 1px 35% lime border, 700 weight at 1.0625rem (1.25rem desktop). The trailing "+ surrounding areas" chip drops the fill, switches to a dashed border and Sage 500 text.

### Step Leaves
Each step is marked by a 52px leaf (Maple Gold, Maple Orange, Maple Red in order) with a darker stem stroke and a 900-weight numeral in a matching dark (or cream on red). Leaf left, title and text right on a 52px / 1fr grid; three across on desktop.

### Sticky Phone Bar
Phones only. Night Green at 94% over the page, bar-cast shadow, safe-area bottom padding. Text button fills the row; Call collapses to an icon-only ghost. Slides up from translateY(110%) over 0.35s on cubic-bezier(.2,.8,.2,1) once neither in-page button pair is visible.

### Top Bar
Z mark (44px, 54px desktop) beside the stacked chrome-serif wordmark and lime lockup label; a 46px circular call button with a 50% lime border on the right, which becomes a pill showing the number on desktop.

### Living Turf (signature)
Canvas grass and leaves in the hero and the close; the motion is the brand.
- **Grass:** blades as filled tapered quadratic curves in eight greens (#163f22 to #86cc52), sorted back to front, with a soil gradient underneath. They sway on a shared three-sine wind and part around the pointer on a spring (stiffness 38, damping 6.5) with a wobble back.
- **Leaves:** maple and ovate sprites, flipping and spinning, settling into the grass at their depth. The pointer acts as a leaf blower; a gust band sweeps left to right every 6 to 10 seconds and lifts resting leaves.
- **Tunable constants (phone / desktop):** blade density 0.95 / 0.85 per px, grass band 118 / 172px, leaves 30 / 54, leaf size 18-32 / 20-40px, blow radius 110 / 150px, blow strength 2600, velocity carry 0.55, grass parting radius 70 / 90px. These live as named constants at the top of the turf function and are the intended tuning surface.
- **Page drift:** a fixed full-viewport canvas with 5 / 11 leaves (14-22 / 16-28px) drifting below the hero, also blowable (radius 100 / 130px).
- **Turf seams:** 80-unit SVG bands between sections. Three rolling stroked lines (back line in the section green or a straw tone under cream, a 3.5px lime middle line, a front line in mid-green or pale straw on cream) over a fill in the next section's ground that follows the middle line. Lines roll with two swells and a ripple; point step 20, speed 1.0.
- **Performance:** one shared requestAnimationFrame loop; each canvas or seam set pauses when off screen; device pixel ratio capped at 2.
- **Reduced motion:** grass and leaves draw once, still; page drift is off; seams freeze at their first frame; button and bar transitions are removed. A static CSS grass gradient covers the hero before scripts run.

## Do's and Don'ts

### Do:
- **Do** keep every ground green (Night Green is the floor) and use the 115° mowing stripe (64px bands of ground and stripe) on the hero and the area band.
- **Do** repeat the same Text-primary / Call-ghost button pair, in that order, wherever contact is offered.
- **Do** make every service a row that texts Zelaya with the service pre-filled.
- **Do** join sections with rolling turf seams whose fill matches the next section.
- **Do** tune motion through the named turf and drift constants, scaling them down on phones, and keep the reduced-motion still frame.
- **Do** keep tap targets at 44px or more, and buttons at 54 to 62px tall.
- **Do** use the system sans and serif stacks; no web fonts.

### Don't:
- **Don't** use a black or neutral-grey ground anywhere, including bars and overlays.
- **Don't** use glow shadows: no colored blur, no lime halo, no zero-offset glow. Shadows are dark, downward and spread-negative.
- **Don't** add thin highlight lines: no 1px light rims, inner top highlights or glassy borders on buttons, chips or panels. The turf seam strokes and the faint row hairlines are the only lines.
- **Don't** state facts the owner hasn't given: no review stars, testimonials, rating badges, years-in-business ribbons, prices, hours or owner name, and no stock or AI-generated photos presented as Zelaya's work.
- **Don't** put warm leaf colors on buttons; buttons are lime or the green ghost.
- **Don't** set headings in the serif or buttons in uppercase.
- **Don't** turn services into a card grid.
