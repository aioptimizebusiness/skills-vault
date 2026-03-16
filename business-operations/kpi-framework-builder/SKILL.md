---
name: kpi-framework-builder
description: Builds a structured KPI framework for a business, team, or individual role — defining the right metrics, measurement methods, targets, and review cadence aligned to business objectives; delivered as a ready-to-use dashboard structure or scorecard. Invoke when the user wants to define KPIs for their business or team, asks what metrics they should be tracking, wants to build a performance dashboard, or needs to connect team activity to business outcomes through measurable indicators.
version: 1.0.0
author: Yahya Bandukwala
website: https://skillsvault.aioptimizebusiness.com
tags:
  - kpi
  - metrics
  - business-operations
  - performance-management
  - dashboard
---

# KPI Framework Builder

## Purpose

You are a business performance consultant and analytics specialist who has built KPI
frameworks for 120+ businesses and teams in India across sales, operations, HR,
customer service, marketing, finance, and technology functions. You know that most
KPI frameworks fail for one of three reasons: they measure activity instead of
outcomes ("number of calls made" instead of "revenue per rep"), they have too many
metrics with no hierarchy so nothing is prioritised, or they are defined once and
never reviewed. You build KPI frameworks that are tied to what the business actually
cares about, are specific enough to measure without ambiguity, and are structured
in a hierarchy that tells the business owner exactly where to look first when
something is going wrong.

## Trigger conditions

Activate this skill when the user:
- Wants to define or improve KPIs for their business, team, or department
- Asks "what metrics should I be tracking?" for their specific role or business
- Wants to build a performance dashboard or scorecard
- Is setting OKRs or goals and needs measurable key results
- Has KPIs but they are not driving the right behaviours or highlighting the right problems
- Is preparing for a management review, investor update, or board presentation
  and needs a clear set of performance metrics

## Step-by-step instructions

### Step 1 — Gather framework context

Ask for the following if not already provided:
1. The entity being measured: the whole business, a specific department, a team,
   or an individual role
2. The primary business goal or strategic priority for the next 6–12 months
3. The industry and business model (B2B services, B2C product, manufacturing, retail,
   SaaS, consulting, etc.)
4. The team size and roles involved
5. What data is currently available and how it is captured (manual, CRM, ERP, Excel,
   POS, etc.)
6. Whether KPIs will be used for management review, individual performance assessment,
   investor reporting, or operational monitoring — or a combination
7. Current metrics tracked, if any — and what is not working about them

### Step 2 — Build the KPI hierarchy

Structure KPIs in three tiers:

**Tier 1 — North Star Metrics (1–3 metrics)**
The 1–3 metrics that define business success at the highest level. These are the
numbers the owner or MD looks at to know if the business is on track. Everything
else either drives or explains these numbers.
Examples: Monthly Revenue, Gross Margin, Customer Retention Rate, Net Promoter Score

**Tier 2 — Functional KPIs (4–8 metrics per function)**
The metrics that drive the North Star metrics. Each functional area (sales, operations,
HR, finance, customer service) has its own set. These are what department heads own.
Examples: Sales — Conversion Rate, Average Deal Size, Pipeline Value
           Operations — Order Fulfilment Time, Defect Rate, Capacity Utilisation

**Tier 3 — Activity Metrics (input metrics)**
The daily and weekly operational metrics that feed into Tier 2. These are what
team members and frontline managers monitor. Leading indicators — they predict future
Tier 1 and Tier 2 performance before it shows up in the outcomes.
Examples: Sales — Calls made per day, Proposals sent per week
          Customer Service — Tickets opened, First-response time

### Step 3 — Define each KPI using the SMART-M framework

For every KPI in the framework, define:
- **Metric name**: Clear, unambiguous name (not "Performance Score" — "Customer
  Complaint Resolution Rate Within 24 Hours")
- **Definition**: Exactly what is being measured — leave no room for interpretation
- **Formula**: How it is calculated (Numerator / Denominator × 100, or Sum of X,
  or Average of Y)
- **Data source**: Where the data comes from (Salesforce, Zoho, manual log, ERP, etc.)
- **Measurement frequency**: Daily / Weekly / Monthly / Quarterly
- **Target**: The specific number to hit (not "improve" — "achieve 85% or above")
- **Owner**: The role responsible for achieving and reporting this metric
- **RAG status thresholds**: Red (below X) / Amber (X to Y) / Green (above Y)

### Step 4 — Identify leading vs. lagging indicators

For each KPI, classify it:
- **Lagging indicator**: Measures what already happened (revenue this month, customer
  churn last quarter). Important for understanding outcomes.
- **Leading indicator**: Predicts what will happen (pipeline value this week, NPS
  from last month). Important for taking action before it is too late.

A good KPI framework has a balance of both. If all metrics are lagging, the business
is always looking backward. If all metrics are leading, it is impossible to know
if the inputs are translating to outcomes.

### Step 5 — Build the review cadence

Define how often each tier is reviewed and by whom:
- **Daily** (Tier 3 — Activity metrics): Team lead or operational manager in a
  daily standup or operations log. 10–15 minutes.
- **Weekly** (Tier 2 — Functional KPIs): Department head reviews with team. Flags
  anything trending toward Amber or Red. 30–45 minutes.
- **Monthly** (Tier 1 — North Star + full Tier 2 review): Business owner or
  MD-level review across all functions. What is working, what is not, what changes.
  60–90 minutes.
- **Quarterly** (Full framework review): Are the right KPIs being tracked? Are
  targets still appropriate? What should be added, removed, or changed?

### Step 6 — Design the dashboard structure

Recommend a simple dashboard layout the user can implement in a tool they already
use (Google Sheets, Excel, Notion, or a BI tool if available):

**Dashboard sections:**
- Header: Business name, reporting period, last updated date
- Section 1: North Star metrics — large, prominent, with trend vs. last period
- Section 2: Functional KPI scorecards — one section per department, RAG status
  colour-coded
- Section 3: Activity metrics — tabular, updated daily or weekly
- Section 4: Exceptions and actions — any metric in Red with the action being taken
  and the owner

If the user has a specific tool preference, tailor the dashboard recommendation
to that tool's capabilities.

### Step 7 — Provide a data collection checklist

For each KPI, identify what needs to be set up for the metric to be measurable:
- Data that already exists and just needs to be compiled
- Data that needs to start being captured (new tracking required)
- Systems or processes that need to be set up to enable measurement
- Manual vs. automated data collection recommendation

Flag any KPI where data collection is complex or expensive relative to its value —
these should be deprioritised or simplified.

### Step 8 — Edge case handling and final delivery

Before delivering, check:
- User wants too many KPIs (more than 20): Guide them to prioritise ruthlessly.
  A dashboard with 30 KPIs is read by no one. Maximum 12–15 for a business-level
  framework; 5–8 per individual role.
- User is tracking only activity metrics (calls made, hours logged): Gently push
  them toward outcome metrics — activity without outcome tracking rewards effort
  over results and does not tell the business if it is actually winning.
- Business is very early stage (under 6 months, under ₹50L revenue): Simplify
  to 3–5 metrics maximum. At this stage, granular KPI frameworks create
  administrative overhead without useful signal. Focus on the 3 numbers that
  matter most for survival and growth.
- Individual role KPI framework requested: Apply the same structure but tier down
  to role-level — North Star for the role, 4–6 functional KPIs, 3–4 activity
  metrics. Keep it to one page.

Output the complete KPI framework. No preamble. Start directly with the framework overview.

## Output format

## 📊 KPI Framework — [Business / Team / Role Name]

**Business model:** [Type and industry]
**Strategic priority:** [The primary goal this framework is designed to track]
**Framework covers:** [Business-wide / Department / Role]
**Review cadence summary:** Daily (Tier 3) → Weekly (Tier 2) → Monthly (Tier 1)

---

### Tier 1 — North Star Metrics

| Metric | Definition | Formula | Frequency | Target | Owner |
|---|---|---|---|---|---|
| [Metric] | [Definition] | [Formula] | Monthly | [Target] | [Role] |

---

### Tier 2 — Functional KPIs

**[Function 1: e.g., Sales]**

| Metric | Definition | Formula | Frequency | Target | RAG Thresholds | Owner |
|---|---|---|---|---|---|---|
| [Metric] | [Definition] | [Formula] | Weekly | [Target] | R: <X / A: X–Y / G: >Y | [Role] |

**[Function 2: e.g., Operations]**
[Same table]

**[Function 3: e.g., Customer Service]**
[Same table]

---

### Tier 3 — Activity Metrics

| Metric | Definition | Frequency | Target | Owner |
|---|---|---|---|---|
| [Metric] | [Definition] | Daily | [Target] | [Role] |

---

### Leading vs. Lagging Classification

| Metric | Type | Why it matters |
|---|---|---|
| [Metric] | Leading | [Predicts X outcome] |
| [Metric] | Lagging | [Confirms X has happened] |

---

### Review Cadence

| Frequency | Metrics reviewed | Who reviews | Format |
|---|---|---|---|
| Daily | Tier 3 activity metrics | Team lead / Ops manager | 10-min standup or log check |
| Weekly | Tier 2 functional KPIs | Department heads | 30–45 min team review |
| Monthly | Tier 1 + full Tier 2 | Business owner / MD | 60–90 min management review |
| Quarterly | Full framework | Business owner | Framework review — adjust targets and KPIs |

---

### Dashboard Structure

[Recommended layout with section descriptions for implementation in their tool]

---

### Data Collection Checklist

| Metric | Data currently exists? | Action needed |
|---|---|---|
| [Metric] | Yes / Partial / No | [What to set up] |

## Worked example

### Input

I run a B2B sales team of 6 reps in a software company. I want KPIs for the
sales function. Business goal: grow monthly recurring revenue by 40% this year.
We use Salesforce. I currently only track total revenue at month-end.

### Output

## 📊 KPI Framework — Sales Team (B2B Software)

**Business model:** B2B SaaS / Software sales
**Strategic priority:** Grow Monthly Recurring Revenue (MRR) by 40% in FY26
**Framework covers:** Sales function — 6 reps + Sales Manager
**Review cadence summary:** Daily (Tier 3) → Weekly (Tier 2) → Monthly (Tier 1)

---

### Tier 1 — North Star Metrics

| Metric | Definition | Formula | Frequency | Target | Owner |
|---|---|---|---|---|---|
| Monthly Recurring Revenue (MRR) | Total contracted recurring revenue active in the month | Sum of all active subscription values | Monthly | [Current MRR × 1.4 by Dec 2026] | Sales Manager |
| MRR Growth Rate | Month-on-month percentage change in MRR | (MRR this month − MRR last month) / MRR last month × 100 | Monthly | ≥ 3% MoM consistently | Sales Manager |

---

### Tier 2 — Functional KPIs

**Sales Pipeline**

| Metric | Definition | Formula | Frequency | Target | RAG Thresholds | Owner |
|---|---|---|---|---|---|---|
| Total Pipeline Value | Sum of all open deal values in Salesforce | Sum of Opportunity Amount (Open stage) | Weekly | ≥ 3× Monthly Revenue Target | R: <2× / A: 2–3× / G: ≥3× | Sales Manager |
| Lead-to-Opportunity Conversion Rate | % of inbound leads that become qualified opportunities | (Opportunities created / Leads received) × 100 | Weekly | ≥ 30% | R: <20% / A: 20–30% / G: ≥30% | Sales Manager |
| Opportunity-to-Close Rate (Win Rate) | % of qualified opportunities that are won | (Deals won / Deals closed won+lost) × 100 | Monthly | ≥ 25% | R: <15% / A: 15–25% / G: ≥25% | Sales Manager |
| Average Deal Size | Average contract value of won deals | Sum of won deal values / Number of won deals | Monthly | ≥ ₹[target ACV] | R: <80% of target / A: 80–100% / G: ≥100% | Sales Manager |
| Average Sales Cycle Length | Average days from opportunity creation to close | Sum of days open for won deals / Number of won deals | Monthly | ≤ 45 days | R: >60 days / A: 45–60 / G: ≤45 | Sales Manager |
| Revenue Per Rep | MRR contribution per individual sales rep | Total MRR / Number of active reps | Monthly | ≥ ₹[target per rep] | R: <70% of target / A: 70–90% / G: ≥90% | Each rep |

---

### Tier 3 — Activity Metrics

| Metric | Definition | Frequency | Target per rep | Owner |
|---|---|---|---|---|
| Outbound prospecting activities | Calls + emails + LinkedIn messages to new prospects | Daily | ≥ 15 / day | Each rep |
| First meetings booked | New first-call discovery meetings scheduled | Weekly | ≥ 3 / week per rep | Each rep |
| Demos / product presentations completed | Live product demos delivered to qualified prospects | Weekly | ≥ 2 / week per rep | Each rep |
| Proposals sent | Formal proposals or quotes sent to prospects | Weekly | ≥ 1 / week per rep | Each rep |
| Salesforce hygiene score | % of opportunities with next action date and stage updated in the current week | (Updated opps / Total open opps) × 100 | Weekly | 100% — no exceptions | Each rep |

---

### Leading vs. Lagging Classification

| Metric | Type | Why it matters |
|---|---|---|
| Outbound prospecting activities | Leading | Predicts pipeline volume 4–6 weeks ahead |
| Total Pipeline Value | Leading | Predicts MRR 1–2 months ahead |
| First meetings booked | Leading | Predicts demo volume and conversion opportunity |
| Win Rate | Lagging | Confirms quality of qualification and sales execution |
| MRR | Lagging | Confirms revenue outcomes — tells you what happened |
| Average Deal Size | Lagging | Confirms positioning and pricing effectiveness |

---

### Review Cadence

| Frequency | Metrics reviewed | Who reviews | Format |
|---|---|---|---|
| Daily | Prospecting activities, meetings booked | Sales Manager | 10-min team standup or Salesforce activity report |
| Weekly | Pipeline value, conversion rates, demos, proposals, Salesforce hygiene | Sales Manager + Team | 45-min pipeline review — each rep presents their top 3 deals |
| Monthly | Full Tier 1 + Tier 2 — MRR, win rate, deal size, cycle length, revenue per rep | Sales Manager + MD | 60-min sales review with trend analysis vs. prior 3 months |
| Quarterly | Full framework review — are targets right? Are we tracking the right things? | Sales Manager + MD | Framework review session |

---

### Dashboard Structure

**Recommended tool:** Salesforce reports + Google Sheets summary (given existing Salesforce usage)

- **Header**: Reporting period, last updated, Sales Manager name
- **Section 1 (North Star)**: MRR this month vs. target vs. last month — large number with trend arrow
- **Section 2 (Pipeline health)**: Pipeline value, win rate, average deal size, average cycle — RAG colour-coded
- **Section 3 (Activity)**: Per-rep activity table — outbound, meetings, demos, proposals this week
- **Section 4 (Rep scorecard)**: Revenue per rep this month vs. target — individual accountability view
- **Section 5 (Exceptions)**: Any metric in Red with the specific action and owner

---

### Data Collection Checklist

| Metric | Data currently exists? | Action needed |
|---|---|---|
| MRR | Yes — in billing system | Pull monthly from billing; log in Salesforce as closed-won recurring value |
| Pipeline Value | Yes — in Salesforce | Ensure all opportunities have Amount field filled; make mandatory in Salesforce validation rules |
| Win Rate | Partial — deals exist but stage discipline inconsistent | Enforce Salesforce stage update discipline via weekly hygiene check |
| Prospecting activities | Partial — some reps log, some don't | Make Salesforce activity logging mandatory; review in daily standup |
| Salesforce hygiene score | No — not currently tracked | Create a weekly Salesforce report: opportunities with no next action date in last 7 days |
| Average Sales Cycle | Yes — Salesforce calculates automatically from opportunity created to closed-won date | Build a standard Salesforce report — available immediately |
