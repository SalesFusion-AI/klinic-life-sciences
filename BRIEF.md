# Klinic Life Sciences Landing Page — Build Brief

## What We're Building
A standalone HTML/CSS/JS landing page for Klinic's Life Sciences / Pharma partnership offering. This replaces their current DatoCMS page (which looks bad and is limited). The output should be a single `index.html` with inline or embedded CSS — ready to host anywhere.

## Brand Guidelines (extracted from klinic.com)

### Colors
- **Primary dark (headings, nav):** `#153B50` (rgb 21, 59, 80)
- **Accent green (buttons, highlights):** `#CAFFB9` (rgb 202, 255, 185)
- **Background:** `#FBFFFA` (rgb 251, 255, 250)
- **Body text:** `rgba(0, 0, 0, 0.87)`
- **Button style:** Dark bg (#153B50) + green text (#CAFFB9), border-radius: 12px

### Typography
- **Font:** Figtree (Google Fonts), fallback: Montserrat, sans-serif
- **Headings:** 700 weight, color #153B50
- **Body:** 400 weight

### Logo
- Use text "klinic" in the nav with the brand styling (lowercase, Figtree bold)
- Include a simple "K" icon placeholder if needed

## Page Structure (inspired by phil.us/solution/direct/)

### 1. Hero Section
- Headline: "Go Direct-to-Patient Without the Friction"
- Subhead: "Klinic connects life sciences brands to real patients through compliant digital experiences, licensed providers, and automated pharmacy workflows."
- Sub-subhead: "Activate high-intent patients, improve adherence, and capture real-world data — all in one platform."
- Primary CTA: "Schedule a Partnership Call" (large, prominent button)
- Secondary CTA: "See How It Works" (text link / ghost button)
- Right side: professional healthcare/pharma visual placeholder (use a gradient card or abstract illustration)

### 2. Three Pillars Row (icon + title + description cards)
Like Phil's "Ad → Landing Page → Telemedicine → DigitalHub → Engagement → Refills" flow but for Klinic's three pillars:

1. **Patient Activation** — "Reach motivated, therapy-seeking patients through compliant search, social, and branded landing flows."
2. **Provider & Access Integration** — "Instantly connect patients with licensed providers and automated coverage checks to accelerate time-to-therapy."
3. **Real-World Data Stream** — "Capture de-identified adherence and outcomes data to power RWE, HEOR, and commercial performance tracking."

Use clean icons (can use Lucide icons via CDN or simple SVG).

### 3. Feature Sections (alternating layout — image left/right)
Each section has: small caps label, bold headline, paragraph, optional stats/bullets.

**Section A — Patient Activation**
- Label: "PATIENT ACTIVATION"
- Headline: "Capture & Convert High-Intent Patients"
- Body: "Our SEO-optimized treatment pages and AI chat widgets meet patients at the moment of intent, routing them into branded landing flows and telehealth scheduling. Personalized reminders drive attendance and refill continuity."
- Visual: placeholder image/card on the right

**Section B — Pharma Hub Services**
- Label: "PHARMA HUB SERVICES"
- Headline: "Automate Benefit Verification, Prior Authorization & Copay"
- Body: "Real-time eligibility checks, AI-assisted Prior Auth submission, denial appeals, and instant copay/PAP enrollment slash average time-to-therapy by 40% compared to traditional hubs."
- Visual: placeholder on the left
- Stat callout: "40% faster time-to-therapy"

**Section C — Tele-Titration Network**
- Label: "TELE-TITRATION NETWORK"
- Headline: "Same-Day Provider Coverage Nationwide"
- Body: "Licensed MDs and NPs conduct virtual starts, REMS education, and follow-ups, sharing notes directly with your CRM and SmartHub workflows for an end-to-end closed loop."
- Visual: placeholder on the right

**Section D — Real-World Evidence Engine**
- Label: "REAL-WORLD EVIDENCE ENGINE"
- Headline: "Continuous Outcomes & PRO Data"
- Body: "De-identified adherence, vitals, and patient-reported outcomes stream into a HIPAA & SOC 2-compliant data lake — fueling HEOR studies, label expansion, and value-based contract negotiations."
- Visual: placeholder on the left

### 4. Results / Social Proof Section (like Phil's "The Results" block)
Big stat cards in a row:
- "40%" — Faster time-to-therapy
- "50 states" — Licensed provider coverage
- "HIPAA & SOC 2" — Compliant data infrastructure
- "24/7" — Patient support availability

### 5. Case Study / Success Story (like Phil's client success story)
Card with:
- Label: "CLIENT SUCCESS STORY"
- Title: "Accelerating Brand Launch with Klinic"
- Situation: "After FDA approval, an emerging biotech needed rapid nationwide provider coverage and patient activation for a specialty medication."
- Solution: "Partnered with Klinic to deploy telehealth titration, automated hub services, and SEO-driven patient acquisition."
- Results: "First patient on therapy within 14 days of launch. 3x faster than traditional hub timeline."

### 6. Partners Section
- Headline: "Life Sciences Partners Include"
- Three cards: Pharma, Emerging Biotech, Digital Therapeutics
- "Trusted by Healthcare Professionals with Backgrounds From:" + logo strip placeholder

### 7. CTA Section (full-width dark banner)
- Dark bg (#153B50), green accent text
- "Partner with Klinic"
- "Schedule a call to discover how Klinic delivers faster starts, higher persistence, and lower total hub cost — all while delighting patients."
- Button: "Book a Meeting Now"

### 8. Footer
- Simple footer matching klinic.com style
- Company info, links, phone: (216) 478-5990, email: support@klinic.com

## Design Notes
- Clean, modern, lots of whitespace (like Phil's page)
- Smooth scroll behavior
- Subtle animations on scroll (fade-in sections) — use IntersectionObserver
- Fully responsive (mobile-first)
- No framework dependencies — vanilla HTML/CSS/JS + Google Fonts
- Use placeholder gradient cards where images would go (labeled "Image Placeholder")
- Professional, enterprise-grade feel — this is B2B pharma

## Technical Requirements
- Single `index.html` file with embedded `<style>` and `<script>`
- Google Fonts loaded via `<link>`
- Lucide icons via CDN for iconography
- Semantic HTML5
- Mobile responsive with media queries
- Smooth scroll, scroll-triggered animations
- Clean, well-commented code
