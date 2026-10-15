# DFW Total Remodeling — Brand Package v1

Built with the repo skills: `ux-design-systems` (tokens), `web-accessibility` (contrast, checked at AA), `mobile-responsiveness` (mobile-first web rules), `image-master` (photo prompts), `meta-ads` (ad angles). I did **not** use `yuv-design-system`; it is Yuval Avidani's personal brand and would contaminate this one.

## 0. Read this first: what I assumed and where I disagree

I know only that it is a **remodeling and paint company in Dallas–Fort Worth**. Everything below assumes **residential**: kitchens, baths, additions, whole-home, plus interior/exterior painting and cabinet refinishing, sold to **homeowners**. If you do commercial, flips, or one trade, the positioning changes. Tell me and I'll redo section 1.

1. **The name is weak as a brand, strong as a search term.** "Total Remodeling" is generic; dozens of companies use it, and "DFW" is a region, not an identity. It will rank for local intent but it won't be remembered. Before you spend on signage or a logo: check the Texas SOS entity search, the domain, and a trademark search. Don't print trucks until that's done.
2. **"Total" is a promise.** It implies one team handles everything. If you subcontract plumbing/electrical (most do), say "we manage every trade" rather than "we do everything". Overclaiming is the fastest way to a bad review.
3. **Don't claim what you can't prove.** No years in business, license numbers, review counts, or "insured" badges are invented here. Texas has no statewide general-contractor license, so your trust signals are insurance, trade licenses (TDLR for electrical/HVAC, TSBPE for plumbing), city registrations/permits, and real reviews. Verify the current rules for your cities.
4. **The positioning only works if operations back it.** The promise below ("start to finish, one point of contact") fails if you ghost clients for two weeks mid-job. Pick promises you can keep.

## 1. Positioning

**For** DFW homeowners tired of contractor horror stories, **DFW Total Remodeling** is the remodeler that **runs the whole job: design, permits, every trade, one point of contact**, so the project finishes when you were told and costs what you were quoted.

- **Pillars:** One point of contact · Written scope and price · Clean, on-schedule jobsites
- **Enemy (never named):** the contractor who disappears, pads change orders, and leaves the site a mess.
- **Personality:** steady, plainspoken, precise. A foreman who explains things, not a salesman.

### Tagline options (pick one; I recommend #1)
1. **Built right. Start to finish.** — safe, true to "Total", works on a truck.
2. One crew. One contact. Done.
3. Your whole home, handled.
4. Plumb, level, and on time. — more character, riskier: you must hit schedule.

## 2. Voice

| Do | Don't |
|---|---|
| "Your kitchen: 6 weeks, $48,200, in writing." (only with real numbers) | "Transform your dream space!" |
| Short sentences, specifics, dates, ranges | Superlatives ("best", "premier", "top-rated") unless earned and sourced |
| "Here's what the permit takes in Plano." | Jargon without explanation |
| Admit tradeoffs ("Quartz costs more; here's why it's worth it for you.") | Pressure language, fake urgency |

**Bio (Instagram/Google, ≤150 chars):** `Kitchen, bath & whole-home remodeling across DFW. One contact, written scope, clean jobsites. Free estimates 👇`

## 3. Visual identity

### Color (tokens in `tokens.css`; all text pairs ≥ 4.5:1)
| Role | Name | Hex | Use |
|---|---|---|---|
| Primary | Foundation | `#1C2B27` | Text, nav, dark sections |
| Background | Limestone | `#F3EFE6` | Page background (Texas limestone, warmer than white) |
| Accent (on dark) | Brass | `#B8893B` | Highlights on Foundation only (4.69:1) |
| Accent (on light) | Deep Brass | `#8A5F1C` | Accent text on Limestone (4.9:1) |
| CTA | Clay | `#9A3E21` | Buttons with white text (6.81:1) |
| Secondary | Slate | `#2F4B5C` | Links, badges, info |
| Muted text | Muted | `#5A6560` | Captions (5.28:1) |

Why: it avoids the blue-and-orange look of most contractor logos, and earthy tones photograph well next to wood, stone, and tile. Rule: **Clay is for CTAs only.** If everything is orange, nothing is.

### Type
- **Display:** Archivo 800 / 600 (Google Fonts) — sturdy, condensed feel, uppercase tracking for labels
- **Body:** Inter 400/500/700
- Min body 16px; line-height 1.5; never light-weight type over photos.

### Logo (`logo/`)
- `mark.svg` — roofline over a level with its bubble centered: "plumb and true". Works at favicon, social avatar, hard hat, tool-box size.
- `primary.svg` / `primary-reversed.svg` — mark + wordmark. **Wordmark is live text**; convert to outlines in Illustrator/Figma before print, signs, or vendors.
- Clear space = half the mark's width. Min size: mark 24px, lockup 120px wide. Don't recolor, stretch, or put on busy photos.
- **This is a concept mark, not a trademark-cleared logo.** If you want a final one, a designer should refine it; I'd budget for that.

### Photography (this is where remodelers win or lose)
- Real before/after from your own jobs beats any stock or AI image. Shoot same angle, same height, daylight, lights on, surfaces cleared, 3:4 portrait for Reels/carousels.
- **Do not post AI-generated images as your completed work.** It's deceptive to clients and risks FTC/Texas DTPA trouble. Use AI only for clearly-labeled concept/inspiration visuals or backgrounds.
- Shot list: wide room, detail (tile edge, cabinet reveal), crew at work (hard hat, branded shirt), jobsite protection (floor covering shows professionalism), final walk-through with the homeowner (with permission).

## 4. Applications
- **Truck/vehicle:** reversed lockup, phone number ≥ 4" tall, "Licensed & insured" only if true, no tagline clutter.
- **Yard sign (with homeowner permission):** Foundation background, Limestone type, mark top-left, URL + phone only.
- **Estimate/proposal:** Limestone page, Foundation headings, scope table, payment schedule, change-order policy in plain English.
- **Crew:** Foundation tee or polo with chest mark; clean, consistent crews are free advertising.

## 5. Website (mobile-first, per `mobile-responsiveness` + `web-accessibility`)
- Hero: one outcome headline, one CTA ("Get a written estimate"), tap-to-call button, sticky on mobile.
- Section order: proof (reviews, real photos) → services → process (4 steps) → gallery → service areas → FAQ → estimate form.
- 44px minimum touch targets, visible focus states, alt text on every project photo, form labels not placeholders.
- Local SEO: separate pages per service × top cities (Plano, Frisco, Irving, Arlington, Fort Worth, etc.); Google Business Profile with real photos; NAP identical everywhere.

## 6. Social (Instagram/Meta) — content pillars
1. **Before/after Reels** (3:4, 7–12 s, text overlay of timeline + scope; never invent prices)
2. **Process:** "Day 1 vs day 14" jobsite diaries
3. **Education:** permits, cost drivers, "what a written scope includes"
4. **Crew & trust:** who's on your job, how we protect your home
5. **Client stories:** only real, with consent

**Hooks to test:** "What your bathroom remodel actually costs in DFW (and what changes it)." · "3 things a contractor should put in writing before they touch your house." · "Day 1 to done: a 6-week kitchen." (use only real timelines)

## 7. Paid (Meta Ads, via `meta-ads` skill, once real assets exist)
- Start with one Lead Form / Click-to-Message campaign, radius targeting around your actual service area, 3 creatives (before/after, process video, educational), run ≥ 2 weeks before judging.
- Track cost per **qualified lead** and cost per booked estimate, not just CPM/CTR. Remodel leads are slow and expensive; low CPL can mean junk.
- Housing is a Meta **special ad category**: no targeting by age/ZIP-exclusion tricks; expect limited audience options.

## 8. What I need from you to finish v2
1. Services and price tier (budget, mid, premium)? 2. Cities you actually serve. 3. How many years, crew size, licensed trades in-house vs subbed. 4. Existing logo/colors/website? 5. Real project photos. 6. Who is the owner/face of the brand (people trust faces).

---

## 9. v1.1 — Remodeling **and** Painting

### The name decision (you need to make this)
You said "remodeling and paint company". The legal/brand name matters more now:
- **Keep "DFW Total Remodeling" as the brand; say "& Painting" as the descriptor.** Recommended. Painters rarely get hired to remodel, but remodelers can win painting, so the bigger word leads. Lockups are in `logo/lockup-remodeling-painting*.svg`.
- **Don't name it "...Remodeling & Paint" in the legal name** unless you want it on every invoice, truck and Google listing forever. Descriptors are cheaper to change than names.
- **Risk:** if painting is most of your revenue, "Total Remodeling" will attract the wrong leads and the wrong price expectations. Tell me the revenue split and I'll flip the hierarchy if needed.

### Offer architecture
| Tier | Service | Role in the business |
|---|---|---|
| Entry | Interior painting, exterior painting, cabinet refinishing, color consult | Fast, lower ticket, high volume, earns trust and reviews |
| Core | Kitchen & bath remodels | Highest margin per client relationship |
| Anchor | Whole-home / additions | Rare, big, comes from referrals |

**The funnel:** paint jobs are your cheapest way to get inside a home and prove you're clean, on time, and honest. Every painting client should leave knowing you remodel (a "while we're here" review at walkthrough, never a hard sell).

### Positioning line, updated
"The DFW remodeler that also paints, so one crew, one contact, and one finished look from rough-in to final coat."
Short version for ads: **"Remodeling & painting, handled start to finish."**

### Paint-specific proof points (verify each before using)
- **Lead-safe work:** homes built before 1978 fall under the EPA Renovation, Repair and Painting (RRP) rule. If you work on pre-1978 homes you need EPA-certified firm and renovator status. This is both a legal requirement and a trust signal, but only claim it if you hold it.
- **Texas conditions:** UV and heat chew exterior paint; humidity and foundation movement crack trim and caulk lines. Educational content on prep (pressure wash, scrape, prime, caulk) is believable and differentiating.
- **Specs in writing:** paint brand and line, number of coats, prep scope, color name/code, sheen, and what's included (trim, ceilings, closets). Vague paint quotes are why homeowners distrust painters.
- **Warranty:** only state one you will honor, in plain language.

### Visual additions
- **Swatch strip device:** a row of 4 to 6 small squares in the brand palette (see `brand-sheet.html`), used as a divider, on estimates, and as the Reel end-card. Says "paint" without a clichéd roller icon.
- **Before/after for paint:** same wall, same light, color name overlaid as a chip (e.g. "Walls: [real color name]").
- Truck/crew: painting crew in the same Foundation workwear; tarps and floor protection photographed as a feature.

### Content pillars, updated for paint
1. **Color transformations** (one-room Reels, 7–10 s, color name and sheen on screen)
2. **Prep is the job** (the 70% nobody sees: patching, sanding, priming)
3. **Cabinet refinishing vs replacing** (honest cost/durability tradeoff)
4. **Exterior in Texas heat** (what fails first and why)
5. **Remodel timelines** (carry over from section 6)

**Hooks to test:** "Why your exterior paint is peeling in 3 years (and it isn't the paint)." · "Refinish or replace your kitchen cabinets? Here's the honest math." · "What a painter should put in writing before they open a can."

### Paid, adjusted
Run painting as the lead-gen offer ("free color consult and written estimate") and remodel as the retargeting/nurture offer. Painting leads convert faster and cost less, which gives you data sooner. Same Meta housing-category limits apply.

### Still needed
Revenue split paint vs remodel, in-house painters vs subs, residential only or also commercial/HOA, service cities, and whether you already hold RRP certification.
