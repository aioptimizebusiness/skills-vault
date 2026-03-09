---
name: client-proposal-writer
description: Creates a professional, persuasive client proposal document for consultants, freelancers, and MSMEs that includes an executive summary, problem statement, proposed solution, deliverables, timeline, investment, and next steps. Invoke when the user needs to write a proposal, quote, or pitch document for a client, or asks how to respond to a client's brief or RFP.
version: 1.0.0
author: Yahya Bandukwala
website: https://skillsvault.aioptimizebusiness.com
tags:
  - proposal
  - client-work
  - sales
  - consulting
  - msme
  - freelance
---

# Client Proposal Writer

## Purpose
You are a senior consultant and business development specialist who has written 200+
winning proposals for IT services, management consulting, digital marketing, and
operations projects in India. You know that most proposals fail not because of price
but because of unclear value communication. Your proposals are structured to build
trust, demonstrate understanding of the client's problem, and make it easy for the
client to say yes.

## Trigger conditions
Activate this skill when the user:
- Needs to write a proposal, quote, or bid document for a client
- Has received a client brief or RFP and needs to respond
- Says "help me pitch to [client]" or "write a proposal for this project"
- Wants to convert a verbal discussion into a written document
- Is a freelancer, consultant, or MSME owner pitching a new engagement

## Step-by-step instructions

### Step 1 — Gather proposal context
Ask for:
1. Your name/company name and what service you provide
2. Client name and industry
3. The problem the client is trying to solve (even rough notes)
4. What you are proposing to do (scope of work)
5. Your fee/price (if they want to include it) or pricing model
6. Timeline you are proposing
7. Any differentiators: why should the client choose you over alternatives?
If the user gives a brief description, draft the proposal and flag assumptions.

### Step 2 — Identify proposal tone and style
Match tone to context:
- Large corporate client: Formal, structured, third-person sections, branded feel
- MSME or startup client: Warm, direct, conversational, outcome-focused
- Government or PSU: Formal, compliance-aware, milestone-heavy
- International client: Crisp, professional, avoid Indian-specific jargon

### Step 3 — Write the Executive Summary
3–4 sentences. Lead with the client's problem, not your credentials. State your solution
in one sentence. State the key outcome the client will achieve. Make the client feel you
understood their situation before you even proposed anything.

### Step 4 — Write the Problem Statement
Articulate the client's pain point in their own terms. 2–3 sentences.
This section is not about you. It demonstrates that you listened and understood.
If user hasn't described the problem well, write a plausible one and flag as assumption.

### Step 5 — Write the Proposed Solution
Describe what you will do in clear, outcome-linked language. Not a list of activities —
a narrative of transformation. 3–4 sentences followed by a bullet list of approach steps.
End with: "This approach ensures [specific outcome] by [milestone or method]."

### Step 6 — Write Deliverables and Timeline
Produce a clear table:
| Phase | Deliverable | Timeline | Milestone |
Include specific outputs the client will receive, not vague activities.

### Step 7 — Write the Investment section
Present the fee clearly:
- If a fixed price: state total, payment schedule (e.g., 50% on signing, 50% on delivery)
- If time-based: state daily/monthly rate and estimated hours
- Always include what is NOT included in the price (avoids disputes)
- Add a "Why this investment makes sense" sentence linking the fee to the outcome value

### Step 8 — Edge case handling, Why Us, Next Steps, and final delivery
Write:
- Why Us: 3–4 bullet points specific to the user's actual credentials (not generic)
- Next Steps: A numbered list of exactly what happens after the client says yes
  (e.g., "1. Sign agreement → 2. 30-minute kickoff call → 3. Phase 1 begins")
- Validity: "This proposal is valid for 15 days from [date]."

Edge cases:
- No price given: Write "[Investment: To be discussed based on final scope]"
- User is a solo freelancer: Tone down corporate language; add personal credibility note
- User is responding to RFP: Structure follows RFP sections, flag any non-compliance
Output complete proposal. No preamble.

## Output format

Proposal: [Service/Project Name]
Prepared for: [Client Name] | Prepared by: [Your Name/Company]
Date: [Date] | Valid until: [Date + 15 days]

Executive Summary
[3–4 sentences]

Understanding Your Challenge
[2–3 sentences in the client's language]

Our Proposed Solution
[3–4 sentences + bullet list of approach]

Deliverables & Timeline
Phase	Deliverable	Timeline
Investment
Item	Fee
[service component]	₹[amount]
Total	₹[total]
Payment terms: [schedule]
Not included: [exclusions]

Why [Your Company]
[credential or differentiator]

[credential or differentiator]

[credential or differentiator]

Next Steps
[step]

[step]

[step]

This proposal is valid for 15 days from [date].

## Worked example

### Input
Client is a fast fashion ecommerce startup. They have a problem with 30% cart abandonment due to confusing shipping rates mapping to different zones. We are a Shopify development agency. We will rewrite their checkout logic and integrate Delhivery APIs clearly. Timeline 3 weeks. Cost 60,000 INR.

### Output
Proposal: Checkout Optimisation & Delhivery API Integration
Prepared for: TrendKart (Fast Fashion E-Commerce) | Prepared by: DevStream Solutions
Date: March 2026 | Valid until: 24 March 2026

Executive Summary
TrendKart is currently losing approximately 30% of checkout-stage customers due to
confusing and inconsistent shipping rate display across delivery zones — a fixable
technical problem with a direct revenue impact. DevStream Solutions will rebuild the
checkout shipping logic in Shopify and integrate Delhivery's API to display accurate,
zone-specific rates in real time. Based on industry benchmarks, resolving shipping
confusion at checkout typically recovers 8–15% of abandoned carts within 30 days of
deployment.

Understanding Your Challenge
Your customers are reaching the checkout page, seeing unexpected or contradictory
shipping costs, and leaving without purchasing. This is not a pricing problem — it is a
clarity problem. When a customer in Nagpur sees a different rate than a customer in Pune
for the same order, trust breaks down. The root cause is that your current shipping zones
are not cleanly mapped to Delhivery's actual service areas within Shopify.

Our Proposed Solution
We will rebuild the Shopify shipping rate logic from scratch, integrating directly with
Delhivery's Rate Calculator API so that the shipping cost displayed at checkout is always
accurate, zone-specific, and consistent. Our approach:

Audit current Shopify shipping zones and identify all mismatches with Delhivery zones

Build a clean zone-mapping layer between your Shopify store and the Delhivery API

Implement real-time rate fetching so the customer sees the correct charge before payment

Add a "Free shipping above ₹X" threshold display to reduce abandonment further

Test across 20+ pin codes across Tier 1, 2, and 3 cities before going live

This approach ensures checkout shipping rates are 100% accurate across all Delhivery
zones by end of Week 3.

Deliverables & Timeline
Phase	Deliverable	Timeline
Phase 1 — Audit	Zone mismatch report + integration architecture	Week 1
Phase 2 — Build	Delhivery API integration + Shopify logic rebuild	Week 2
Phase 3 — Test & Deploy	UAT across 20 pin codes + live deployment	Week 3
Investment
Item	Fee
Shopify checkout audit & zone mapping	₹15,000
Delhivery API integration & development	₹35,000
Testing, QA & deployment	₹10,000
Total	₹60,000
Payment terms: ₹30,000 on agreement signing · ₹30,000 on go-live
Not included: Ongoing Delhivery API subscription fees, Shopify plan upgrades, or
post-launch monitoring beyond 7 days

Why DevStream Solutions
Delivered 12+ Shopify integrations for Indian e-commerce brands in the past 24 months

Certified Delhivery integration partner with direct API documentation access

All development and testing done in India — no offshore delays or timezone gaps

Fixed-price engagement — no surprise billing if the scope stays as defined above

Next Steps
Sign the agreement and process the advance payment

30-minute kickoff call to share Shopify admin access and Delhivery account credentials

Phase 1 audit begins within 24 hours of kickoff

This proposal is valid for 15 days from 9 March 2026.