# 02 — Design Direction
## Jo's House

> Paste this alongside 00-master-prompt.md when starting any design-heavy build session in GHL Studio AI.

---

## Aesthetic Direction

- **Vibe keywords:** Refined pastoral warmth — serene, earthy, handcrafted, honest, healing
- **Overall tone:** Warm and deeply human — like a farmhouse that has been carefully, thoughtfully made beautiful. Not rustic-kitschy. Not clinical. Not corporate. Think: the quiet confidence of a place that doesn't need to try too hard.
- **Theme:** Light only
- **Density:** Open and airy — generous whitespace, unhurried pace. The site should feel like the experience it's selling: slow down, breathe, rest.
- **Reference synthesis:** Take the serene minimalism and atmospheric photography of Shibui Spa, the structured sophistication and earth-toned cleanliness of Parsley Health, and root it in warm pastoral textures and the golden-brown color world of the Jo's House logo.

---

## Color Palette

| Role | Hex | Usage |
|------|-----|-------|
| Background | `#FAF7F0` | Main page background — warm cream, never pure white |
| Surface | `#F0EBE0` | Section alternates, cards, panels |
| Deep Brown | `#4A2C0A` | Primary headings, logo text color, footer background |
| Golden Amber | `#D4920A` | Primary CTA buttons, links, key accent elements |
| Meadow Green | `#4A7C3F` | Secondary accents, nature/farm elements, success states |
| Warm Caramel | `#8B5E3C` | Secondary text, subheadings, caption text |
| Sunflower Gold | `#F5C842` | Highlight details, decorative elements, dividers |
| Linen | `#E8DFD0` | Borders, dividers, card outlines |
| Dark Espresso | `#2C1A06` | Footer background, deep contrast surfaces |
| Soft White | `#FEFCF8` | Overlay surfaces, modal backgrounds |

**Button styles:**
- Primary: Golden Amber `#D4920A` background, white text, medium border radius
- Secondary / ghost: Transparent with Deep Brown `#4A2C0A` border and text
- Hover: Darken primary by 10%, subtle lift shadow

---

## Typography

**Display / Heading font:** Cormorant Garamond
- Source: Google Fonts
- Weights: 400 (italic for pull quotes), 600 (subheadings), 700 (main headings)
- Character: Elegant, warm, slightly editorial — refined without being stuffy. Pairs naturally with the script logo.
- H1: ~56–64px desktop / 36–42px mobile
- H2: ~40–48px desktop / 28–34px mobile
- H3: ~26–30px desktop / 22–24px mobile

**Script accent font:** Pinyon Script or Dancing Script
- Source: Google Fonts
- Use: Section labels only (e.g., "Sound familiar?" "Here's how it works.") — never for body copy or long strings
- Weight: Regular only
- Size: 18–22px — used sparingly, not on every section

**Body font:** Lato
- Source: Google Fonts
- Weights: 300 (light body), 400 (regular body), 700 (bold emphasis)
- Line height: 1.75 — generous, easy to read, unhurried
- Body size: 17–18px desktop, 16px mobile
- Note: Body copy must be highly readable. If any font choice reduces legibility, default to Lato regular at 17px with `#4A2C0A` or `#8B5E3C` on cream background.

**Type hierarchy summary:**
- Section labels: Script font, `#D4920A`, 20px
- H1/H2 headings: Cormorant Garamond Bold, `#4A2C0A`
- H3 subheadings: Cormorant Garamond SemiBold, `#4A2C0A`
- Body: Lato Regular, `#8B5E3C` or `#4A2C0A` depending on section
- Captions / fine print: Lato Light, `#8B5E3C`, 14px
- CTA button text: Lato Bold, uppercase, tracked slightly, white on amber

---

## Reference Sites

**Sites that capture the feel:**

1. **https://www.shibuispa.com/**
   What to take: Serene whitespace, atmospheric full-bleed photography, the sense of quiet luxury in every section. The unhurried pace of the scroll. The sense that every element has breathing room.

2. **https://www.parsleyhealth.com/**
   What to take: Clean structured sections with generous padding, earth-toned color world (bone/cream + muted greens), sans-serif body type that's highly readable. Medical credibility without clinical coldness.

3. **https://www.pressmodernmassage.com/**
   What to take: The modern, no-nonsense layout. Clear CTAs. Wellness positioning without being over-the-top.

4. **https://urban.co/en-gb**
   What to take: Sophisticated layout, clean navigation, confident use of photography.

5. **https://bbmassageandfloat.com/**
   What to take: Clear service explanations, trust-focused photography, approachable and therapeutic tone.

**Sites to NOT look like:**
- Generic WordPress wellness templates with purple gradients and lotus flower icons
- Clinical white medical sites with blue accents and stock photo doctors
- Over-designed "luxury spa" sites that feel cold and inaccessible
- Anything that feels like a chain or a franchise — Jo's House is one-of-a-kind and personal

---

## Layout & Spacing

- **Border radius:** Medium — 8–12px on cards and buttons. Pill-shaped on CTA buttons if it fits the overall feel.
- **Shadow style:** Subtle warm shadows — use `rgba(74, 44, 10, 0.08)` for card shadows. No dramatic drop shadows.
- **Grid:** 12-column, max content width 1200px centered
- **Section padding:** Generous — 100–120px vertical padding desktop, 60–80px mobile
- **Card internal padding:** 32px standard
- **Dividers:** Use `#F5C842` sunflower gold hairlines or organic botanical SVG dividers between sections — no harsh horizontal rules

---

## Animation & Motion

- **Level:** Moderate to expressive — this should feel alive and warm, not static
- **Preferred style:**
  - Fade-up on scroll for text blocks and cards (elements rise gently into view)
  - Parallax on hero and full-bleed photo sections — subtle depth, not dizzying
  - Scale-in on imagery (photos appear from slightly smaller)
  - Soft hover lift on cards and buttons (translateY -3px, subtle shadow increase)
- **Hover states:** Warm color shift on links (amber → deeper amber), gentle lift on cards and buttons
- **Page load:** Subtle fade-in on hero — no heavy splash screens
- **Transition speed:** Slow and deliberate — 350–450ms. This is a rest-focused brand. Nothing snaps or pops.
- **Scroll behavior:** Smooth scroll throughout

---

## Imagery & Media

**Photography approach:**
- Primary: Real photos from the Maley farm and bee sessions (provided in `/assets/Assets/`)
- Supplement with: Golden-hour pastoral photography — warm light, bee hives, wildflowers, meadows, barns, natural textures
- Photo treatment: Warm-toned, slightly desaturated in shadows. Think soft film grain, not Instagram filter. Images should feel honest, not over-edited.
- Avoid: Stock photography of smiling wellness professionals, white studio backgrounds, generic nature shots with no character

**Illustration:**
- Occasional botanical/bee SVG line illustrations as decorative accents — section dividers, background textures
- Style: Hand-drawn feel, warm ink color (`#8B5E3C`), delicate weight
- Never use as a substitute for real photography

**Icon set:** Lucide icons — clean, minimal, consistent. Use `#D4920A` amber for accent icons.

**Video:** If Bryan records a personal welcome video, embed it prominently on the About page or Hero section. No autoplay. Thumbnail should be a warm, candid farm photo.

---

## What to Absolutely Avoid

- NO purple, blue, or teal color schemes — the palette is warm amber-brown-green, full stop
- NO stock photos of smiling professionals, yoga poses, or generic wellness imagery
- NO clinical white backgrounds with blue accents
- NO Inter, Roboto, or Arial as primary fonts
- NO generic SaaS or corporate layout patterns
- NO busy, cluttered sections — every section has one job and one message
- NO small or hard-to-read text — legibility is non-negotiable for this audience
- NO religious imagery (crosses, doves, etc.) — Bryan's faith shows through warmth, not symbols
- NO fake urgency ("only 3 spots left!") — this brand is built on honesty and trust
- NO Lorem Ipsum anywhere on any page
