# 04 — Site Structure & Layout
## Jo's House

> Paste this alongside 00-master-prompt.md when building navigation, page layouts, or structural scaffolding.

---

## Site Map

| Page | Route | Priority | Goal |
|------|-------|----------|------|
| Home | `/` | P1 | Primary conversion page — full StoryBrand narrative, drives bookings and course signups |
| About / Bryan's Story | `/about` | P1 | Build trust through Bryan's personal story; the most important credibility page on the site |
| Bee Bed Therapy | `/bee-bed-therapy` | P1 | Educate visitors who don't know what bee bed therapy is before they'll consider booking |
| Book Your Session | `/book` | P1 | Dedicated booking page with GHL calendar widget embedded — no distractions |
| Free Course | `/free-course` | P1 | Lead generation landing page — captures email in exchange for free course delivery |
| Contact | `/contact` | P1 | Simple inquiry form; warm invitation from Bryan |
| Testimonials / Stories | `/stories` | P2 | Real guest testimonials once collected — supports trust and conversion |
| FAQ | `/faq` | P2 | Handles objections and reduces pre-booking anxiety |
| Blog / Learning | `/blog` | P3 | Educational content on bee therapy, stress, grief — builds local SEO over time |
| Farm & Homestead | `/farm` | P3 | Context and warmth; shows the full Jo's House experience |
| Honey & Products | `/honey` | P3 | Raw local honey sales — mentioned in About page; worth a dedicated page when ready |
| Privacy Policy | `/privacy` | P1 | Legal requirement — can be simple GHL-generated page |
| Terms of Service | `/terms` | P1 | Legal — simple |

---

## Navigation

**Header nav:**
- Style: Sticky top bar — transparent over hero, transitions to solid warm cream `#FAF7F0` with subtle shadow on scroll
- Logo: Left-aligned — Jo's House logo image
- Nav links (desktop): About | Bee Bed Therapy | Free Course | Contact
- Primary CTA button (right): Book Your Session — Golden Amber `#D4920A`, pill-shaped
- Mobile nav: Hamburger icon → full-screen overlay, cream background, centered links stacked vertically, large touch targets
- Active state: Amber underline on current page link

---

## Homepage Section Order

Every section has one job. Do not add copy or visual elements that don't serve that section's goal.

1. **Hero**
   - Layout: Full-bleed atmospheric farm/hive photo as background, dark warm overlay for text legibility. Headline and subheadline centered or left-aligned. Two CTA buttons below — primary (Book) and secondary (Free Course link).
   - Goal: Hook the exhausted visitor in the first 3 seconds. Name their pain before anything else.
   - Formula: PAS — Pain (headline), Agitate (subheadline names why nothing else has worked), Solution (bee bed therapy at Jo's House)

2. **Problem Section**
   - Layout: Centered text block on warm cream background. Wide, readable paragraph. No imagery needed — this section is all about words landing.
   - Goal: Validate the visitor's experience. Make her feel understood before making any claim.
   - Formula: PAS — name the villain (overstimulation culture + inadequate local options)

3. **Guide Section — Bryan**
   - Layout: Two-column on desktop (Bryan photo left, text right) / stacked on mobile. Warm surface background `#F0EBE0`. Photo should feel candid and warm — Bryan at the farm or with the hives, not a headshot.
   - Goal: Establish Bryan as someone who understands her situation from the inside, then establish authority.
   - Formula: StoryBrand Guide — empathy first, authority second. End with 3 placeholder testimonial cards.
   - Testimonial card layout: Quote text, name, and brief context. 3-column on desktop, single swipeable carousel on mobile.

4. **How It Works — 3 Steps**
   - Layout: Horizontal 3-step flow on desktop (numbered cards side by side), stacked vertically on mobile. Icon or small illustration for each step. CTA button below.
   - Goal: Reduce anxiety about the unknown. Make booking feel simple and clear.
   - Formula: StoryBrand 3-step Plan — Book, Learn, Rest

5. **Success Section**
   - Layout: Full-bleed warm photo background (farm, golden light, peaceful scene) with text overlay, or alternating image/text block. Let the copy breathe.
   - Goal: Paint the transformation — what life looks and feels like after a session.
   - Formula: BAB — Before acknowledged (carried tension), After painted (body exhaled, mind quiet, sleep comes easier)

6. **Failure / Stakes Section**
   - Layout: Simple centered text block on slightly deeper surface (`#F0EBE0`). No imagery. Short copy — this section should be brief and not dwell.
   - Goal: Name the cost of inaction without fear-mongering. One CTA button.
   - Formula: PAS reversed — the cost of doing nothing is accepting that this is just how life feels

7. **Transitional CTA — Free Course**
   - Layout: Two-column on desktop — left: copy and form / right: warm illustrative or photographic element. Full-width band with contrasting background (Deep Brown `#4A2C0A` or Deep Espresso `#2C1A06`), warm cream text.
   - Goal: Capture visitors who are curious but not ready to book. Warm on-ramp.
   - Formula: AIDA — Attention (not ready to book?), Interest (what's in the course), Desire (talk to Bryan personally), Action (download)

8. **Final CTA**
   - Layout: Full-width section, centered. Large Cormorant Garamond headline, single Book Your Session button. Minimal — no competing elements.
   - Goal: Last conversion push before the footer.
   - Formula: AIDA compressed — single desire statement, single action

9. **Footer**
   - See Footer section below

---

## Footer

**Background:** Dark Espresso `#2C1A06`
**Text:** Warm Cream `#FAF7F0` and Caramel `#8B5E3C`

**Structure: 3 columns + bottom bar**

- **Column 1 — Jo's House:**
  Logo (white/cream version)
  Tagline: Find Rest. Feel Like Yourself Again.
  Address: 10469 S. SR5, Whitley County, Indiana 46787

- **Column 2 — Visit:**
  Book Your Session
  Bee Bed Therapy
  Free Course
  About

- **Column 3 — Connect:**
  Contact
  [Facebook — if available]
  [Instagram — if available]

- **Bottom bar:**
  © 2026 Jo's House. All rights reserved.
  Jo's House is a registered 501(c)(3) nonprofit organization.
  Privacy Policy | Terms of Service

---

## Responsive Behavior

| Section | Mobile (< 768px) | Tablet (768–1024px) | Desktop (> 1024px) |
|---------|------------------|---------------------|---------------------|
| Nav | Hamburger → full-screen overlay | Hamburger or condensed links | Full nav with CTA button |
| Hero | Full-bleed photo, stacked text, both CTAs stacked | Same as mobile | Text left or centered, large type |
| Problem | Single column, generous padding | Single column, wider | Centered max-width 700px |
| Guide / Bryan | Photo top, text below | Side by side | Side by side, larger photo |
| Testimonials | Single card, swipe carousel | 2 cards | 3 cards side by side |
| How It Works | 3 cards stacked vertically | 3 cards horizontal | 3 cards horizontal, wider |
| Success | Full-bleed photo, text overlay | Same | Text + photo alternating or overlay |
| Free Course CTA | Stacked, form below copy | Side by side | Side by side |
| Footer | Single column, stacked | 2 columns | 3 columns + bottom bar |

---

## Interaction Patterns

- **Scroll behavior:** Smooth scroll throughout
- **Sticky elements:** Nav only — sticks to top on scroll, transparent over hero, solid on all other sections
- **Scroll animations:** Fade-up on all text blocks and cards (trigger at 80% viewport); parallax on full-bleed photo sections
- **Hover states:** Cards — subtle lift (translateY -3px) + shadow increase; Buttons — darken by 10%, shadow; Nav links — amber underline slides in
- **Carousel behavior:** Testimonials — manual only on desktop, swipe on mobile; no auto-play
- **Accordion behavior:** FAQ page — one open at a time; smooth expand/collapse animation
- **Modals:** None at launch
- **Back to top button:** Yes — appears after 600px scroll, amber circle with up arrow, fixed bottom-right
- **Form feedback:** Inline validation, success state with warm confirmation message ("You're all set — check your inbox.")

---

## Component Needs

- [ ] Sticky nav with transparent-to-solid scroll transition
- [ ] Hero with full-bleed photo + warm overlay + dual CTA layout
- [ ] 3-step plan cards (How It Works)
- [ ] Testimonial card (quote + name + context) — placeholder-ready
- [ ] Free course capture form (First Name + Email + CTA)
- [ ] Booking embed block (GHL Calendar widget)
- [ ] Full-screen mobile nav overlay
- [ ] Back to top button
- [ ] Section divider — botanical SVG or gold hairline

---

## Whitespace & Density

- **Section vertical padding:** Generous — 100–120px desktop, 64–80px mobile
- **Card internal padding:** 32px
- **Line height (body):** 1.75 — open and easy to read
- **Overall feel:** Open and airy — this site should feel as spacious as the farm it represents
- **Max content width:** 1200px centered; long-form text sections constrained to 720px for readability
