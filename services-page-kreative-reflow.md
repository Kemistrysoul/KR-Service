# Kreative Reflow — Premium Services Page (Dark Mode)

## Design System

### Color Tokens
- `--bg-base: #1a1a1a` (Main page background)
- `--bg-surface: #242424` (Section blocks)
- `--bg-card: #2a2a2a` (Service and feature cards)
- `--text-primary: #f5f5f5` (Primary text)
- `--text-secondary: #c9c9c9` (Body/supporting text)
- `--text-muted: #9a9a9a` (Meta labels, helper text)
- `--border-subtle: #3a3a3a` (Dividers and neutral borders)
- `--border-accent: #d4af37` (Premium highlight borders/dividers)
- `--accent-gold: #d4af37` (Tag accents, section highlights)
- `--cta-primary: #ff6b35` (Primary conversion button; use intentionally)
- `--cta-primary-hover: #ff7e52`
- `--cta-text-dark: #111111` (Text on orange CTA)

### Typography Scale
- **H1**: Playfair Display, 64/1.05, 700, -0.02em
- **H2**: Playfair Display, 48/1.1, 700
- **H3**: Playfair Display, 32/1.15, 700
- **H4/Card Title**: Playfair Display, 30/1.15, 700
- **Body Large**: Inter, 22/1.5, 400
- **Body**: Inter, 18/1.65, 400
- **Small**: Inter, 14/1.5, 500

### Spacing Scale (8pt)
- `8, 16, 24, 32, 40, 48, 64, 80, 96, 120`
- Section vertical rhythm: `96–120px` desktop, `72–88px` tablet, `56–72px` mobile
- Card padding: `32px` desktop, `24px` tablet/mobile

### Button Styles
- **Primary CTA**
  - Fill: `--cta-primary`
  - Text: `--cta-text-dark`
  - Radius: `999px`
  - Padding: `14px 24px`
  - Hover: +2px lift + soft glow (`0 10px 24px rgba(255,107,53,.25)`)
- **Secondary CTA**
  - Fill: transparent
  - Border: `1px solid --border-accent`
  - Text: `--text-primary`
  - Hover: subtle gold tint background `rgba(212,175,55,.08)`
- **Ghost**
  - No border
  - Text: `--text-secondary`
  - Hover text: `--text-primary`

### Card Style
- Background: `--bg-card`
- Border: `1px solid rgba(212,175,55,.35)`
- Radius: `20px`
- Shadow: `0 6px 24px rgba(0,0,0,.28)`
- Hover: `translateY(-4px)`, border to `rgba(212,175,55,.65)`, gentle gold glow (`0 0 0 1px rgba(212,175,55,.25), 0 12px 30px rgba(0,0,0,.35)`)
- Icon style: consistent **outline icon set** (24px strokes, rounded corners)

---

## Sticky Mini-Nav (Desktop)
Anchored to top after hero, with section links:
- Services
- Process
- Why Us
- Pricing
- FAQ

**Layout**
- **Desktop**: full-width slim bar, centered container, left logo text “Kreative Reflow”, right anchor links.
- **Tablet**: condensed horizontal scroll nav.
- **Mobile**: non-sticky inline jump links directly under hero.

**Component specs**
- Height: `56px`
- Background: `rgba(26,26,26,.92)` with blur
- Bottom border: `1px solid --border-subtle`
- Active anchor: gold underline (`2px`)

**Microcopy/UX notes**
- Keeps users oriented on long-form service content.
- Reduces scroll fatigue and supports quick intent-based navigation.

---

## Hero

### Content
**Heading**
Services That Drive Results

**Subheading**
From stunning websites to strategic marketing, we deliver digital solutions that help your business grow. Transparent pricing, expert execution, measurable outcomes.

**CTA Button**
Get a Free Consultation →

**Trust line (below CTA)**
Transparent pricing, fast turnaround, and post-launch support—built into every project.

### Layout description
- **Desktop**: Left-heavy composition. H1 and subheading on left (max-width 760px), CTA cluster below, subtle right-side supporting panel with short credibility line and thin gold divider.
- **Tablet**: Single-column with slightly reduced H1; CTA remains above fold.
- **Mobile**: Vertical stack; H1 40px, comfortable line-height, button full-width up to 320px.

### Component specs
- Eyebrow optional: “Kreative Reflow Services” in gold small caps.
- CTA uses **Primary** style.
- Optional divider motif: 1px gold rule under subheading.

### Microcopy/UX notes
- Clear value proposition + specific outcome language (“grow”, “measurable outcomes”).
- Primary CTA appears immediately for high-intent visitors.
- Trust line lowers friction without adding clutter.

---

## Services

### Section Header + Filter Row
**Heading**: Our Services

**Visual filter row (non-functional but realistic):**
All / Websites / Social / Ads / SEO / Branding / Development

### Layout description
- **Desktop**: 3-column equal-height card grid.
- **Tablet**: 2-column equal-height card grid.
- **Mobile**: 1-column stack with full-width cards.

### Component specs
- Card sections in order:
  1. Category tag
  2. Outline icon
  3. Title
  4. Description
  5. “What’s Included” bullets
  6. “Ideal For” bullets
  7. Pricing
  8. Timeline (or package/timeline where applicable)
  9. CTA button (secondary style)
- Equal-height enforcement: `display:flex; flex-direction:column;` with CTA pinned to bottom via `margin-top:auto`.
- Tags: pill with subtle gold border + muted text.

### Service Cards (Final Copy)

#### 1) WEBSITES — WordPress Website Design
**Description**
Custom, mobile-responsive websites built to convert visitors into leads. Fast turnaround, transparent pricing, and ongoing support included. Perfect for businesses ready to establish a professional online presence.

**What’s Included**
- Custom Divi design tailored to your brand
- Mobile-responsive (works on all devices)
- SEO-optimized structure
- Contact forms and lead capture
- Google Analytics integration
- Speed optimization
- Security setup (SSL, backups)
- 30 days post-launch support
- Training and documentation

**Ideal For**
- Small businesses
- Medical professionals
- Service providers
- Professional firms
- Local businesses

**Pricing**
South Africa: R8,000 - R25,000  
Overseas: $800 - $2,500

**Timeline**
2-4 weeks

**CTA**
View Website Packages →

---

#### 2) SOCIAL MEDIA — Social Media Management
**Description**
Strategic content that builds your brand and drives engagement. We handle the planning, creation, and posting so you can focus on running your business. Consistent, professional, results-driven.

**What’s Included**
- Content strategy and calendar
- Custom graphics and visuals (Canva Pro)
- Copywriting for all posts
- Platform management (Instagram, Facebook, LinkedIn)
- Scheduling and posting
- Community engagement
- Monthly analytics reports
- Hashtag research and optimization
- Story and reel creation

**Ideal For**
- Small businesses building brand awareness
- Medical professionals establishing authority
- Service providers attracting local clients
- B2B companies generating leads

**Pricing**
South Africa: R3,000 - R8,000/month  
Overseas: $400 - $1,200/month

**Packages**
- Starter: 8-12 posts/month (2-3 per week)
- Growth: 16-20 posts/month (4-5 per week)
- Premium: 24-30 posts/month (daily posting)

**CTA**
View Social Media Packages →

---

#### 3) ADVERTISING — Paid Ads Management
**Description**
Data-driven Google and Facebook ad campaigns that deliver measurable ROI. We handle strategy, setup, optimization, and monthly reporting. Turn ad spend into revenue.

**What’s Included**
- Campaign strategy and planning
- Audience research and targeting
- Ad copywriting and creative
- Landing page optimization
- Conversion tracking setup
- A/B testing and optimization
- Budget management
- Monthly performance reports
- Ongoing optimization and scaling

**Platforms**
- Google Ads (Search, Display, YouTube)
- Facebook & Instagram Ads
- LinkedIn Ads (B2B)

**Ideal For**
- Businesses ready to scale quickly
- Service providers needing leads
- E-commerce stores
- Medical practices attracting new patients
- B2B companies generating qualified leads

**Pricing**
South Africa: R4,000 - R10,000/month + ad spend  
Overseas: $500 - $1,500/month + ad spend

**Minimum Ad Spend**
R5,000/month (SA) | $500/month (Overseas)

**CTA**
Get Your Ad Strategy →

---

#### 4) LOCAL SEO — Local SEO
**Description**
Dominate local search and attract more customers with optimized Google Business Profile, local citations, and review management. Get found when it matters most.

**What’s Included**
- Google Business Profile optimization
- Local citation building (top directories)
- Review generation and management
- Local keyword optimization
- Location-specific landing pages
- Google Maps optimization
- Competitor analysis
- Monthly ranking reports
- Ongoing optimization

**Ideal For**
- Local service businesses (plumbers, electricians, contractors)
- Medical professionals (dentists, doctors, specialists)
- Restaurants and retail stores
- Professional services (lawyers, accountants)
- Any business serving a specific geographic area

**Pricing**
South Africa: R3,000 - R8,000/month  
Overseas: $400 - $1,000/month

**Timeline**
Results in 2-4 months

**CTA**
Boost Your Local Presence →

---

#### 5) SEO & CONTENT — SEO & Content Marketing
**Description**
Rank higher on Google and attract organic traffic with strategic SEO and high-quality content. From technical audits to blog posts, we help you get found online and establish authority in your industry.

**What’s Included**
- Technical SEO audit
- Keyword research and strategy
- On-page optimization
- Content creation (blog posts, guides, articles)
- Link building and outreach
- Competitor analysis
- Google Search Console setup
- Monthly traffic and ranking reports
- Ongoing optimization

**Content Deliverables**
- 2-4 blog posts per month (800-1,500 words)
- SEO optimization for existing pages
- Meta descriptions and title tags
- Internal linking strategy

**Ideal For**
- Businesses wanting national/international reach
- E-commerce sites
- B2B companies with longer sales cycles
- Professional services building authority
- Content-heavy businesses (blogs, resources)

**Pricing**
South Africa: R5,000 - R15,000/month  
Overseas: $600 - $1,800/month

**Timeline**
Results in 3-6 months

**CTA**
Start Ranking Higher →

---

#### 6) BRANDING — Branding & Design
**Description**
Build a memorable brand that stands out. From logo design to complete visual identity systems, we create cohesive branding that reflects your values and resonates with your audience.

**What’s Included**
- Brand strategy and positioning
- Logo design (3-5 concepts, unlimited revisions)
- Color palette and typography
- Brand guidelines document
- Business card design
- Letterhead and email signature
- Social media templates
- Brand assets (icons, patterns, graphics)

**Deliverables**
- Logo files (AI, PNG, SVG, PDF)
- Brand guidelines (PDF)
- Print-ready files
- Digital assets

**Ideal For**
- New businesses launching
- Established businesses rebranding
- Companies with inconsistent branding
- Businesses ready to scale professionally

**Pricing**
South Africa: R8,000 - R25,000  
Overseas: $800 - $2,500

**Timeline**
3-5 weeks

**CTA**
Build Your Brand →

---

#### 7) DEVELOPMENT — Web Applications
**Description**
Custom-built business tools, portals, and interactive solutions that automate processes and solve specific business challenges. From patient portals to dealer management systems, we build applications tailored to your needs.

**What’s Included**
- Discovery and requirements gathering
- UI/UX design and prototyping
- Custom development (frontend + backend)
- Database design and setup
- API integrations
- User authentication and roles
- Testing and quality assurance
- Deployment and hosting setup
- Training and documentation
- Post-launch support

**Types of Applications**
- Patient portals (booking, records, payments)
- Dealer/distributor portals (ordering, inventory, reporting)
- Custom CRM systems
- Booking and scheduling systems
- Inventory management tools
- Business dashboards and analytics
- Interactive calculators and tools

**Ideal For**
- Medical practices needing patient portals
- Medical device companies needing dealer portals
- Businesses with unique workflow requirements
- Companies wanting to automate processes
- Growing businesses needing custom tools

**Pricing**
South Africa:  
- Simple: R25,000 - R50,000
- Medium: R50,000 - R150,000
- Complex: R150,000 - R500,000+

Overseas:  
- Simple: $2,500 - $5,000
- Medium: $5,000 - $15,000
- Complex: $15,000 - $50,000+

**Timeline**
4-24 weeks (depending on complexity)

**CTA**
Discuss Your Project →

### Microcopy/UX notes
- Category tags and icons improve scan speed.
- Clear “What’s Included” + “Ideal For” structure reduces ambiguity and improves conversion confidence.
- Pricing and timeline on-card pre-qualify leads before inquiry.

---

## Our Process

### Content
**Heading**
Our Process

**Subheading**
Simple, transparent, and results-focused. Here's how we bring your project to life.

**Step 1 — 1. Discovery Call**
We start with a free consultation to understand your business, goals, and challenges. No pressure, just honest conversation about what you need.

**Step 2 — 2. Strategy & Proposal**
We create a custom strategy and detailed proposal with clear pricing, timelines, and deliverables. You'll know exactly what to expect.

**Step 3 — 3. Execution & Launch**
We get to work, keeping you updated every step of the way. Once complete, we launch your project and provide training and support.

### Layout description
- **Desktop**: 3 horizontal step cards with connectors/dividers.
- **Tablet**: 3 cards in 2+1 arrangement.
- **Mobile**: Fully stacked cards.

### Component specs
- Outline icons (message, clipboard, rocket).
- Number badge in gold outline circle.
- Consistent card height and aligned titles.

### Microcopy/UX notes
- Three-step framing makes engagement feel simple and low-risk.
- “No pressure” and “you’ll know exactly what to expect” build trust.

---

## Why Choose Us

### Content
**Heading**
Why Work With Kreative Reflow?

1. **Transparent Pricing**  
No hidden fees or surprise charges. You'll know exactly what you're paying for upfront.

2. **Fast Turnaround**  
We respect your time. Most projects are completed in 2-6 weeks, not months.

3. **Results-Driven**  
We focus on outcomes that matter: more leads, more traffic, more revenue.

4. **Ongoing Support**  
We don't disappear after launch. Every project includes post-launch support and training.

5. **Medical Industry Expertise**  
With a background in medical sales, we understand the unique needs of healthcare professionals and medical device companies.

6. **Global Experience, Local Understanding**  
We serve clients in South Africa and internationally, bringing global best practices with local market knowledge.

### Layout description
- **Desktop**: 2-column icon list (3 items left, 3 items right).
- **Tablet**: 2 columns with tighter spacing.
- **Mobile**: Single-column stacked list.

### Component specs
- Each reason as compact row-card with outline icon left, title + description right.
- Dividers between rows in subtle border color.

### Microcopy/UX notes
- This section handles objections: trust, speed, outcomes, support, specialization.
- Healthcare credibility creates differentiation for a niche segment.

---

## Investment

### Content
**Heading**
Transparent, Custom Pricing

**Subheading**
No cookie-cutter packages. No hidden fees. Just honest pricing based on what you actually need.

Here's how our pricing works:

1️⃣ **Free Consultation**  
We discuss your goals, challenges, and budget. No pressure, just honest conversation.

2️⃣ **Custom Proposal**  
You receive a detailed proposal with clear pricing, timeline, and deliverables. Everything is transparent—no surprises.

3️⃣ **Flexible Payment**  
For larger projects, we offer milestone-based payments or payment plans to make it manageable.

4️⃣ **Ongoing Support**  
Every project includes post-launch support. We don't disappear after delivery.

**What you'll never get from us:**
- ❌ Hidden fees or surprise charges
- ❌ Vague timelines or scope creep
- ❌ Cookie-cutter solutions
- ❌ Pressure to buy services you don't need

**What you will get:**
- ✅ Honest assessment of what you need
- ✅ Clear, detailed pricing
- ✅ Quality work that drives results
- ✅ Transparent communication every step

**CTA**
Get a Free Consultation →

### Layout description
- **Desktop**: Split layout. Left = pricing philosophy steps; Right = “Never/Get” reassurance panel with subtle gold vertical divider.
- **Tablet**: Stacked with reassurance panel directly after steps.
- **Mobile**: Single-column; check/cross lists in separate cards for readability.

### Component specs
- Step list uses numbered chips (gold outline).
- Cross/check lists use tinted rows (`rgba(255,107,53,.06)` for ❌, `rgba(212,175,55,.08)` for ✅).
- CTA uses **Primary** style (second intentional repeat).

### Microcopy/UX notes
- Reframes pricing as transparent process rather than quote shock.
- “Never/Get” contrast strongly de-risks purchase decisions.

---

## FAQ

### Content
**Heading**
Frequently Asked Questions

1. **Do you offer payment plans?**  
Yes. For projects over R25,000 (or $2,500), we offer flexible payment plans with milestone-based payments. Most projects are split 50/50 (upfront and on completion) or into 3-4 milestone payments.

2. **How long does a typical project take?**  
Timelines vary by service:
- Websites: 2-4 weeks
- Branding: 3-5 weeks
- Web Applications: 4-24 weeks (depending on complexity)
- Monthly services (SEO, Social Media, Ads) are ongoing with results typically visible in 2-3 months.

3. **Do you work with clients outside South Africa?**  
Absolutely. We serve clients globally, with a focus on the US, UK, Australia, and Canada. All communication is done via email, video calls, and project management tools.

4. **What if I need changes after my website launches?**  
All website projects include 30 days of post-launch support for minor tweaks and bug fixes. After that, we offer affordable maintenance packages or hourly rates for updates.

5. **Do you provide hosting and domain services?**  
We can set up hosting and domains for you, or work with your existing providers. We recommend reliable hosting partners and handle all technical setup.

6. **Can you help with an existing website?**  
Yes. We offer website redesigns, updates, and optimization for existing sites. We can also migrate your site to a new platform if needed.

7. **What makes you different from other agencies?**  
We combine technical expertise with industry-specific knowledge (especially in medical/healthcare). We're transparent with pricing, fast with delivery, and focused on results that matter to your business.

8. **Do you offer custom packages?**  
Absolutely. Every business is unique. We create custom packages tailored to your specific needs, goals, and budget. Contact us for a personalized proposal.

### Layout description
- **Desktop**: Two-column FAQ block: left intro/title, right accordion list.
- **Tablet**: 35/65 split.
- **Mobile**: Single-column accordion stack.

### Component specs
- Accordion row: question, plus/minus icon, bottom divider.
- Expanded state: answer panel with `16px` top padding and muted body text.
- Touch target minimum: `48px` height.

### Microcopy/UX notes
- FAQ addresses payment, timeline, global delivery, support, and differentiation.
- Accordion keeps the section scannable despite long answers.

---

## Final CTA

### Content
**Heading**
Ready to Grow Your Business?

**Subheading**
Let's discuss your project. Book a free consultation and get a custom proposal with transparent pricing and clear timelines.

**CTA Button**
Get a Free Consultation →

**Secondary Text**
Or email us at: hello@kreativereflow.com

### Layout description
- **Desktop**: Centered content with max-width 900px in high-contrast surface block.
- **Tablet**: Same structure with reduced padding.
- **Mobile**: Stacked with full-width CTA and tappable email link.

### Component specs
- CTA uses **Primary** style (third intentional repeat).
- Section top divider in gold for closure.

### Microcopy/UX notes
- Strong closing question nudges commitment.
- Secondary email option captures users not ready to book.

---

## Build Notes (WordPress/Elementor)
- Use anchor IDs exactly: `#services`, `#process`, `#why-us`, `#pricing`, `#faq` for sticky mini-nav.
- Set global section spacing: desktop `112px`, tablet `80px`, mobile `64px`.
- Service cards: equal height via flex column; keep CTA button pinned to bottom.
- Keep icon family consistent (outline only) across services, process, and why-us.
- Add subtle hover only (lift + border glow); avoid heavy animations and random gradients.
- FAQ widget: accordion behavior with one item open at a time on mobile for scroll efficiency.
- Maintain contrast ratios: body text on cards should use `#c9c9c9` or brighter against `#2a2a2a`.
- Smooth scroll enabled for anchor links; sticky nav active on desktop only.
