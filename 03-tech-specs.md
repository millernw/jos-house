# 03 — Technical Specs
## Jo's House

> Paste this alongside 00-master-prompt.md at the start of any technical build session.

---

## Platform

- **Builder:** GoHighLevel (GHL) Studio AI
- **Hosting:** GoHighLevel — all pages hosted natively within GHL
- **CMS:** GHL native — content editable via the GHL dashboard
- **Domain:** joshouse.com (connect via GHL domain settings)

**Note:** This site is built entirely within GoHighLevel. All booking, forms, email automation, CRM pipelines, and contact management are handled natively by GHL. No external integrations are required. When GHL Studio AI asks about framework, output format, or external tools — the answer is always "native GHL."

---

## Integrations — All Native to GoHighLevel

| Function | GHL Tool | Notes |
|----------|----------|-------|
| Session booking | GHL Calendar / Booking widget | Embed booking widget on Book page and as CTA throughout site |
| Contact forms | GHL Forms builder | Contact page form, any inquiry forms |
| Free course delivery | GHL Email automation / Workflow | On form submit → deliver course via email sequence |
| Email list & follow-up | GHL Email marketing + Workflows | Capture leads from free course form; build nurture sequence |
| CRM | GHL CRM | All form submissions and bookings feed into GHL pipeline |
| Funnel/landing pages | GHL Funnels or Site builder | Free course landing page may be built as a GHL funnel |
| SMS follow-up | GHL SMS automation | Optional: post-booking confirmation and reminder texts |
| Reviews / testimonials | GHL Reputation management | Collect and display Google reviews over time |
| Analytics | GHL built-in analytics + Google Analytics 4 | Add GA4 tracking code via GHL site settings |
| Google Business | Google Business Profile (external) | Set up separately; links to joshouse.com |

---

## Forms & Data Collection

| Form | Fields | GHL Destination | Notes |
|------|--------|----------------|-------|
| Free course signup | First Name, Email | GHL contact + free course workflow trigger | Triggers email automation to deliver course |
| Contact / general inquiry | First Name, Last Name, Email, Phone (optional), Message | GHL contact + notification to Bryan | Bryan should receive email or SMS notification on submit |
| Booking | Handled by GHL Calendar widget | GHL calendar + confirmation workflow | Confirmation + reminder emails automated via GHL |

---

## Email Automation (GHL Workflows)

**Free Course workflow:**
1. Visitor submits first name + email on Free Course landing page
2. GHL creates contact, tags "free-course-lead"
3. Immediate: deliver free course via email (link or PDF)
4. Day 3: follow-up email — "Did you get a chance to look through it? Here's what one person said after their first session."
5. Day 7: Bryan personal-voice email — "Still have questions? Here's my number."
6. Day 14: soft booking CTA — "When you're ready, sessions are easy to book."

**Booking confirmation workflow:**
1. Guest books session via GHL calendar
2. Immediate: confirmation email with session details, what to expect, and farm address
3. 24 hours before: reminder email with directions and prep notes
4. Post-session (Day 1): thank-you email with a note from Bryan; invite to leave a review

---

## Authentication & Member Areas

- **Auth needed:** No — public-facing site only at launch
- **Future consideration:** If Bryan creates a paid course or member content, GHL Memberships can handle this natively without a separate tool

---

## SEO & Performance

- **SEO priority:** Important — local SEO is a primary discovery channel for this audience
- **Local SEO:** Ensure Google Business Profile is set up and linked; use Whitley County / northeast Indiana location language throughout copy
- **Schema markup:** Add LocalBusiness and Service schema via GHL or custom code injection (business name, address, service type, geo coordinates)
- **Sitemap:** Generate via GHL site settings — submit to Google Search Console
- **Page speed:** Optimize all images before upload — compress to WebP where possible; avoid large uncompressed HEIC files
- **OG/social meta:** Set title, description, and OG image for each page in GHL page settings

---

## Known Constraints

- **501(c)(3) language:** Footer and About page must clearly state nonprofit status — "Jo's House is a registered 501(c)(3) nonprofit organization."
- **No HIPAA requirements:** Jo's House is a wellness center, not a healthcare provider. Standard GHL forms are appropriate.
- **Testimonials:** Currently placeholder — do not fabricate or publish fake testimonials. Launch with a "Coming soon" or omit testimonial cards until real ones are collected via GHL Reputation management.
- **Image formats:** Assets are currently a mix of HEIC, JPG, PNG. Convert all HEIC files to JPG or WebP before uploading to GHL — HEIC is not reliably supported in web browsers.
- **Mobile-first:** The primary visitor is discovering this site on a phone. Every section must be designed and tested on mobile before desktop.
- **No paid npm packages, no external code dependencies** — all functionality should be native GHL or simple CSS/JS added via GHL custom code blocks.
