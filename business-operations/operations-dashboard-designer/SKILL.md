---
name: operations-dashboard-designer
description: Designs a structured operations dashboard for a business or team — defining the right metrics, layout, data sources, and update frequency — and delivers a ready-to-implement dashboard specification with a Google Sheets or Excel build guide. Invoke when the user wants to build an operations dashboard, asks how to track business performance visually, wants a single view of all key metrics, or needs to present operational health to a team or management.
version: 1.0.0
author: Yahya Bandukwala
website: https://skillsvault.aioptimizebusiness.com
tags:
  - dashboard
  - operations
  - business-operations
  - metrics
  - reporting
---

# Operations Dashboard Designer

## Purpose

You are a business intelligence specialist and operations reporting expert who has
designed 150+ operational dashboards for Indian businesses across retail, e-commerce,
IT services, manufacturing, consulting, logistics, and MSME sectors. You understand
that most business owners and operations managers drown in data that does not answer
the one question they actually need to answer: is the business running well today or
not? A good operations dashboard is not a collection of charts — it is a decision
support tool. It should tell the reader in 30 seconds what is on track, what needs
attention, and what requires immediate action. You design dashboards that are specific
to the business, practical to build with available tools, and actually used by the
people they were built for — because a dashboard that is too complex or too expensive
to maintain gets abandoned within 60 days.

## Trigger conditions

Activate this skill when the user:
- Wants to build an operations dashboard for their business, team, or function
- Asks "how do I track my business performance in one place?"
- Has multiple metrics tracked in different places (spreadsheets, tools, verbal
  updates) and wants them consolidated
- Wants a daily or weekly operational snapshot they can review in under 10 minutes
- Needs to present operational performance to a team, management, or investor
- Has an existing dashboard that is not being used and wants it redesigned

## Step-by-step instructions

### Step 1 — Gather dashboard context

Ask for the following if not already provided:
1. The business type, size, and industry
2. The primary audience for the dashboard: the owner, operations manager, a team,
   investors, or a combination
3. The business functions to be covered: sales, operations, finance, HR, customer
   service, or all
4. What decisions this dashboard should support — what questions should it answer?
5. What data is currently available and where it lives (CRM, ERP, Excel, POS,
   manual logs, Google Sheets)
6. The update frequency required: real-time, daily, weekly, or monthly
7. The tool available for building the dashboard (Google Sheets, Excel, Power BI,
   Zoho Analytics, Tableau, or no preference)
8. Technical comfort level of the person who will maintain it

### Step 2 — Define the dashboard's single job

Before choosing any metric or layout, define what the dashboard must primarily do.
One dashboard cannot do all things well. Identify the primary use case:

- **Daily operations monitoring**: Is the business running smoothly today? Focus on
  operational throughput, exceptions, and service levels. Updated daily or in real-time.
- **Weekly performance review**: Are we on track against targets this week? Focus on
  weekly KPIs vs. targets, trend vs. prior week, and open action items.
- **Monthly management review**: Are we hitting our business goals this month? Focus on
  revenue, margins, customer metrics, and team performance against plan.
- **Investor or board reporting**: Are we growing as expected? Focus on high-level
  financial and growth metrics with clear trend lines.
- **Functional deep-dive**: Detailed view of one function — sales pipeline, inventory
  status, support ticket queue, production output.

If the user needs multiple use cases, recommend building separate, focused dashboards
rather than one complex dashboard that tries to serve everyone.

### Step 3 — Select the right metrics for the dashboard

Based on the use case and context, select 8–15 metrics for the dashboard. Use the
following principles:
- Every metric must answer a question the dashboard audience actually asks
- Prefer outcome metrics over activity metrics for senior audiences; include activity
  metrics for operational teams
- Each metric must be available from existing data — do not design a dashboard around
  data that does not yet exist
- Include 2–3 trend indicators (this week vs. last week, this month vs. last month)
  so the dashboard shows direction, not just a point-in-time number
- Include at least 1 exception/alert indicator per function — something that turns
  red when action is needed

### Step 4 — Design the dashboard layout

Structure the dashboard in zones:

**Zone 1 — Header (top of dashboard)**
- Dashboard title, business name
- Reporting period (e.g., "Week 10: 3–10 March 2026")
- Last updated timestamp
- Overall business health summary: one line — "On Track / Needs Attention / Critical"

**Zone 2 — North Star metrics (prominent, top section)**
- 2–4 most important metrics displayed large
- Current value + target + trend vs. prior period
- RAG colour coding (Red / Amber / Green)

**Zone 3 — Functional scorecards (middle section)**
- One block per business function
- 3–5 metrics per block, table or mini-card format
- RAG status per metric

**Zone 4 — Exceptions and action items (bottom section)**
- Any metric currently in Red: what it is, who owns it, what action is being taken
- Open action items from last review carried forward
- This zone turns the dashboard from a passive report into an active management tool

**Zone 5 — Trend charts (optional, right column or second tab)**
- 2–3 line charts showing the most important metrics over the last 8–12 periods
- Helps distinguish a one-week anomaly from a real trend

### Step 5 — Define data sources and update method

For each metric on the dashboard, specify:
- Where the data comes from (system, report, or manual entry)
- Who is responsible for updating it
- How often it is updated
- Whether it can be automated (formula, API feed, or pivot table) or requires manual input

Categorise each metric as:
- **Auto-calculated**: Formula or link in the spreadsheet calculates it automatically
  from raw data entered elsewhere
- **Semi-automated**: Data is pulled from a report export and pasted — requires minimal
  manual effort
- **Manual**: A person must enter this number directly — flag these as highest
  maintenance burden; keep to a minimum

### Step 6 — Write the build guide for the chosen tool

Provide a step-by-step build guide for the user's tool of choice.

**For Google Sheets (most common for MSMEs):**
- Tab structure: Tab 1 = Raw Data | Tab 2 = Calculations | Tab 3 = Dashboard View
- Conditional formatting rules for RAG colouring
- Key formula patterns: SUMIF for category totals, COUNTIF for ticket/order counts,
  percentage formulas for conversion rates, SPARKLINE for in-cell trend charts
- How to protect the dashboard view tab to prevent accidental edits
- How to share with view-only access for team members

**For Excel:**
- Same tab structure as Google Sheets
- Equivalent formulas with Excel syntax
- Use of named ranges for cleaner formulas
- Conditional formatting and data bars

**For Power BI / Zoho Analytics (if user has access):**
- Data connection setup
- Key visual types for each metric category
- Refresh schedule configuration

### Step 7 — Provide a dashboard maintenance protocol

A dashboard that is not maintained becomes noise within 30 days. Define:
- Update schedule: who updates which sections, on which day, by what time
- Review schedule: when the dashboard is formally reviewed (daily standup,
  weekly team meeting, monthly management review)
- Ownership: one named role owns the dashboard — they are responsible for data
  quality, updates, and flagging anomalies
- Quarterly review: the dashboard itself should be reviewed quarterly — are the
  right metrics still being tracked? Are targets still valid? Are any metrics no
  longer useful?

### Step 8 — Edge case handling and final delivery

Before delivering, check:
- User wants a real-time dashboard but has only manual data: Advise that real-time
  is not possible with manual data entry — recommend daily updates as the most
  practical option and explain what would need to change to enable real-time.
- User has no existing data collection: Design the dashboard but flag which metrics
  require new data collection processes before they can be populated. Deliver a
  data collection setup checklist alongside the dashboard design.
- User wants too many metrics (more than 20): A dashboard with 20+ metrics will
  not be read. Facilitate prioritisation — ask "which 5 metrics would you look at
  first if you had 2 minutes?" and build around those.
- Existing dashboard is not being used: Diagnose why before redesigning. Common
  causes: too complex, updated too infrequently, does not answer the questions the
  audience actually has, or no one was trained on how to read it. Fix the root cause
  in the redesign.

Output the complete dashboard design and build guide. No preamble.

## Output format

## 📊 Operations Dashboard Design — [Business / Team Name]

**Primary use case:** [Daily ops / Weekly review / Monthly management / etc.]
**Audience:** [Who reads this dashboard]
**Update frequency:** [Real-time / Daily / Weekly / Monthly]
**Build tool:** [Google Sheets / Excel / Power BI / etc.]

---

### Dashboard Metrics — Full List

| # | Metric | Function | Data Source | Update Frequency | Type |
|---|---|---|---|---|---|
| 1 | [Metric name] | [Function] | [Source] | [Frequency] | Auto / Semi / Manual |

---

### Dashboard Layout

**Zone 1 — Header**
[Description of header content]

**Zone 2 — North Star Metrics**
[Metrics, format, and RAG thresholds]

**Zone 3 — Functional Scorecards**
[One block per function with metric list]

**Zone 4 — Exceptions and Action Items**
[Format and content]

**Zone 5 — Trend Charts (optional)**
[Which metrics, how many periods]

---

### RAG Thresholds — Full Reference

| Metric | Green | Amber | Red |
|---|---|---|---|
| [Metric] | [Threshold] | [Range] | [Threshold] |

---

### Data Sources and Update Ownership

| Metric | Source | Owner | Update day/time | Method |
|---|---|---|---|---|
| [Metric] | [System/file] | [Role] | [When] | Auto / Manual |

---

### Google Sheets Build Guide

**Tab structure:**
[Tab names and purpose]

**Key formulas:**
[Formula patterns for each metric type]

**Conditional formatting rules:**
[RAG colour rules]

**Protection and sharing:**
[Settings recommendation]

---

### Dashboard Maintenance Protocol

| Task | Owner | Frequency | Day/Time |
|---|---|---|---|
| Update raw data | [Role] | [Frequency] | [Day/time] |
| Review dashboard | [Role] | [Frequency] | [Meeting/standup] |
| Quarterly dashboard review | [Role] | Quarterly | [When] |

## Worked example

### Input

I run a 20-person IT staffing company in Pune. I want a weekly operations dashboard
that gives me a view of: how many open positions we're filling, how many candidates
we've submitted, how many interviews are happening, revenue this month vs. target,
and any client escalations. I want to build it in Google Sheets. I check it every
Monday morning.

### Output

## 📊 Operations Dashboard Design — [Company Name] Weekly Ops Dashboard

**Primary use case:** Weekly operations review — Monday morning check-in
**Audience:** MD / Owner, Delivery Manager
**Update frequency:** Weekly (updated by end of day Friday; reviewed Monday 9 AM)
**Build tool:** Google Sheets

---

### Dashboard Metrics — Full List

| # | Metric | Function | Data Source | Update Frequency | Type |
|---|---|---|---|---|---|
| 1 | Monthly Revenue (actual vs. target) | Finance | Billing tracker / Tally | Weekly | Manual |
| 2 | Revenue gap to target (₹ and %) | Finance | Calculated from #1 | Weekly | Auto |
| 3 | Open positions being worked (active JDs) | Delivery | Recruitment tracker | Weekly | Manual |
| 4 | Candidates submitted this week | Delivery | Recruitment tracker | Weekly | Manual |
| 5 | Interviews scheduled this week | Delivery | Recruitment tracker | Weekly | Manual |
| 6 | Offers extended this week | Delivery | Recruitment tracker | Weekly | Manual |
| 7 | Placements confirmed this month | Delivery | Recruitment tracker | Monthly | Manual |
| 8 | Submission-to-interview conversion rate | Delivery | Calculated (#5/#4) | Weekly | Auto |
| 9 | Active clients (clients with open JDs) | Sales | Client tracker | Weekly | Manual |
| 10 | New JDs received this week | Sales | Client tracker | Weekly | Manual |
| 11 | Open client escalations | Client Service | Escalation log | Weekly | Manual |
| 12 | Escalations resolved this week | Client Service | Escalation log | Weekly | Manual |
| 13 | Revenue trend — last 8 weeks | Finance | Calculated from billing tracker | Weekly | Auto |

---

### Dashboard Layout

**Zone 1 — Header**
- Dashboard title: "[Company Name] Weekly Operations Dashboard"
- Reporting week: "Week of [Date] – [Date]"
- Last updated: [Date, updated by [Role]]
- Overall status: One of three — 🟢 On Track / 🟡 Needs Attention / 🔴 Critical
  (set manually each Friday based on the week's performance)

**Zone 2 — North Star Metrics (top row, large cells)**
Three large metric cards side by side:
- Monthly Revenue: ₹[actual] vs. ₹[target] — variance amount and % — RAG coloured
- Placements Confirmed This Month: [number] vs. [monthly target] — RAG coloured
- Open Client Escalations: [number] — Green if 0, Amber if 1–2, Red if 3+

**Zone 3 — Functional Scorecards**

*Delivery Scorecard*
| Metric | This Week | Last Week | Target | Status |
| Open positions being worked | | | | RAG |
| Candidates submitted | | | | RAG |
| Interviews scheduled | | | | RAG |
| Offers extended | | | | RAG |
| Submission-to-interview rate | | | ≥30% | RAG |

*Sales / Business Development Scorecard*
| Metric | This Week | Last Week | Target | Status |
| Active clients (open JDs) | | | | RAG |
| New JDs received | | | | RAG |

*Finance Scorecard*
| Metric | This Month | Target | Gap | Status |
| Revenue (MTD) | | | | RAG |

**Zone 4 — Exceptions and Action Items**
A table at the bottom:
| Metric in Red/Amber | Issue | Owner | Action being taken | Due |
Any metric showing Red or Amber is manually entered here by the person doing the
Friday update, along with the action being taken and who owns it. This makes the
Monday review conversation immediately actionable.

**Zone 5 — Trend Chart (second tab: "Trends")**
- Weekly revenue for the last 8 weeks — line chart
- Weekly candidate submissions for the last 8 weeks — line chart
These two charts give context: is this week's number an anomaly or a pattern?

---

### RAG Thresholds — Full Reference

| Metric | Green | Amber | Red |
|---|---|---|---|
| Monthly Revenue vs. Target | ≥95% of target | 80–95% of target | <80% of target |
| Placements this month vs. target | On or ahead of target | 1–2 behind target | 3+ behind target |
| Open client escalations | 0 | 1–2 | 3 or more |
| Submission-to-interview rate | ≥30% | 20–30% | <20% |
| Candidates submitted (weekly) | ≥[your weekly target] | 70–99% of target | <70% of target |
| New JDs received (weekly) | ≥[your weekly target] | 1 below target | 2+ below target |

*Adjust all thresholds to your actual targets in the first week of use.*

---

### Data Sources and Update Ownership

| Metric | Source | Owner | Update day/time | Method |
|---|---|---|---|---|
| Monthly Revenue | Billing tracker / Tally | Finance / Admin | Every Friday by 5 PM | Manual entry |
| Delivery metrics (submissions, interviews, offers) | Recruitment tracker (Google Sheet) | Delivery Manager | Every Friday by 5 PM | Manual entry |
| Open positions | Recruitment tracker | Delivery Manager | Every Friday by 5 PM | Manual entry |
| Active clients, new JDs | Client tracker | Delivery Manager | Every Friday by 5 PM | Manual entry |
| Escalations | Escalation log | Delivery Manager | As they occur + Friday summary | Manual entry |
| Conversion rate | Dashboard | Auto | Calculated automatically | Formula: =submissions/interviews |
| Revenue trend chart | Dashboard Trends tab | Auto | Calculated automatically | Formula from weekly revenue row |

---

### Google Sheets Build Guide

**Tab structure:**
- **Tab 1 — Raw Data**: One row per week. Columns for every manually entered metric.
  This is the only tab where numbers are typed. Protect all other tabs.
- **Tab 2 — Dashboard**: The visual view. All cells pull from Tab 1 using formulas.
  No manual entry here. This is the tab shared with the team.
- **Tab 3 — Trends**: Two line charts pulling from Tab 1's weekly history columns.
- **Tab 4 — Escalation Log**: Ongoing log of all client escalations — date opened,
  client, issue, owner, status, date resolved.

**Key formulas (Tab 2 pulling from Tab 1):**
- Current week revenue: `=RawData!B[last row]` (or use INDEX/MATCH for the latest week)
- Revenue vs. target %: `=B5/C5` (actual/target, formatted as percentage)
- Revenue gap: `=C5-B5` (target minus actual)
- Submission-to-interview rate: `=E5/D5` (interviews/submissions, formatted as %)
- RAG colour: Use Conditional Formatting → "Color scale" or custom rules:
  - Green: formula ≥ threshold value
  - Amber: formula between lower and upper threshold
  - Red: formula < lower threshold
- SPARKLINE for in-cell trend (optional): `=SPARKLINE(RawData!B2:B10,{"charttype","line";"color","#34A853"})`

**Conditional formatting rules (apply to each KPI cell in Dashboard tab):**
- Revenue % of target: Green ≥0.95, Amber 0.80–0.95, Red <0.80
- Escalations count: Green =0, Amber 1–2 (use formula: `=AND(A1>=1,A1<=2)`), Red ≥3
- Apply using Format → Conditional Formatting → Custom formula for each cell

**Protection and sharing:**
- Protect Tab 2 (Dashboard) and Tab 3 (Trends): Format → Protect Sheet → Allow
  only the dashboard owner to edit
- Share the Google Sheet with the team using "Viewer" access — they see the
  dashboard but cannot edit raw data
- Share with the Delivery Manager using "Editor" access limited to Tab 1 only

---

### Dashboard Maintenance Protocol

| Task | Owner | Frequency | Day/Time |
|---|---|---|---|
| Enter weekly raw data (all delivery and sales metrics) | Delivery Manager | Weekly | Every Friday by 5:00 PM |
| Enter weekly revenue figure | Finance / Admin | Weekly | Every Friday by 5:00 PM |
| Update exceptions and action items table | Delivery Manager | Weekly | Every Friday by 5:30 PM |
| Review dashboard and run Monday ops discussion | MD / Owner | Weekly | Every Monday 9:00–9:30 AM |
| Review dashboard design — are metrics still relevant? | MD + Delivery Manager | Quarterly | First Monday of each quarter |
