# Action Plan — AI Speed-to-Lead Voice/SMS Agent for Local Service Businesses

Target: first paying client. Plan created 2026-06-27.

## Step 1 (Days 1–2): Pick one beachhead vertical and build the demo agent
Choose ONE vertical to start (recommend: residential HVAC or plumbing — high ticket per job, owners feel missed-call pain acutely, easy to find via Google Maps/Yelp). Build a working voice agent on Retell AI or Vapi (both have free/low-cost dev tiers) that can: answer a simulated inbound call, ask qualifying questions (service needed, urgency, address, callback number), and confirm a booked time slot. This is the proof artifact for every subsequent sales conversation — do not skip building a real, callable demo.

## Step 2 (Days 2–3): Build a 1-page ROI calculator/landing page
A single page showing: "You're paying ~$X/mo for after-hours/overflow coverage (or losing $Y/mo in missed calls) — here's what a 24/7 AI agent costs instead." Use the sourced cost comparisons ($0.40/AI call vs $7–12/human call; 5.4 FTEs ≈ $330k/yr for full coverage) as the anchor numbers. Include a link/number to call the live demo agent so prospects can experience it firsthand, not just read about it.

## Step 3 (Days 3–5): Identify and contact 30 target businesses
Pull a list of 30 local HVAC/plumbing companies (Google Maps scrape or manual list) in a metro area, prioritizing ones that: (a) have visible after-hours/emergency service claims, (b) have noticeably slow Google review response times or complaints about missed calls/callbacks in reviews — this is a direct pain signal. Send the first outreach batch (see `outreach_scripts.md`) via email/SMS/cold call, leading with "call this number and see what your customers would experience" rather than a pitch deck.

## Step 4 (Days 5–10): Run 5–10 discovery calls, close first 1–3 clients on a pilot offer
Offer a low-friction pilot: first 30 days at a reduced rate (e.g. $300–500/mo instead of full $1,000+) or free, in exchange for a case study/testimonial and the right to use their results in future sales. Goal is speed-to-first-revenue and a real reference, not maximizing the first invoice.

## Step 5 (Days 10–14): Deliver, measure, and convert pilot to standard pricing
Track and report concrete numbers back to the pilot client weekly: calls answered, leads qualified, appointments booked, estimated revenue captured that would have been missed. Use these numbers to (a) convert the pilot to standard $500–1,500/mo pricing, and (b) generate the first real case study to use in step 3 outreach for the next 30 prospects.

## Compliance note (added 2026-06-29 — read before scaling past pilot)
A dedicated risk pass found that TCPA litigation exposure for outbound AI voice calling has escalated sharply in 2025–2026: the FCC has confirmed TCPA applies to AI-generated voices, settlements have run $5M–$20M, a Feb 2026 case established that the AI-calling *vendor/platform* can be held liable (not just the business using it), and statutory damages run $500–$1,500/call, uncapped. This pick is lower-risk than most of the category because it's responding to inbound leads rather than cold-calling, but before scaling past 1-3 pilot clients: (1) document consent capture for every number contacted (the lead's own form submission is your consent record — keep it), (2) build a clean opt-out flow into the agent script, (3) check call-recording disclosure requirements in any two-party-consent state a client operates in, and (4) consider a TCPA-aware contract clause limiting your liability if a client gives you a bad/non-consented number to call. This is a real budget line (a few hours of legal review), not a blocker — but skipping it is the kind of thing that ends an agency, not just costs a client.

## After first paying customer
Repeat steps 3–5 to reach 5–10 paying clients (~$3k–10k/mo), then begin layering in a second vertical to diversify and push toward the $50k/mo ceiling. **Update 2026-06-28: independent insurance agencies are now the recommended second vertical** (ahead of dental/legal) — sourced research shows 98% of insurance agencies are already planning AI investment in 2026 and can deploy first-ring AI pickup in under 30 days, the strongest adjacent-vertical urgency signal found to date. Dental/solo legal intake remain valid third/fourth verticals. **Update 2026-07-01: veterinary practices added as a fourth/fifth vertical option** — same recall/retention AI playbook as dental (proven via Arini/YC), but vet has been largely ignored by AI-native managed services (lower competition signal) and 25–35% of every vet practice's client base is classified as lapsed. Vet practices are familiar with per-appointment economics and make quick decisions. See opportunities.md #33 for scoring and evidence detail.
