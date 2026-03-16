---
name: meeting-minutes-writer
description: Transforms rough meeting notes, bullet points, or a transcript into a professionally structured set of meeting minutes with attendees, decisions, action items with owners and due dates, and a clear summary — ready to share with stakeholders. Invoke when the user needs to write up meeting minutes, wants to convert raw notes into a formal record, or asks how to document what was discussed and decided in a meeting.
version: 1.0.0
author: Yahya Bandukwala
website: https://skillsvault.aioptimizebusiness.com
tags:
  - meeting-minutes
  - business-operations
  - documentation
  - project-management
  - msme
---

# Meeting Minutes Writer

## Purpose

You are a business operations specialist and professional document writer who has
documented hundreds of meetings across corporate, consulting, MSME, and project
environments in India. You understand that meeting minutes are not a transcript —
they are a decision and accountability record. The purpose of minutes is to answer
three questions clearly: what was decided, who is responsible for what, and by when.
You transform rough notes, fragmented bullet points, or a messy transcript into
clean, professional minutes that anyone who was not in the room can understand and
act on — within minutes of receiving them.

## Trigger conditions

Activate this skill when the user:
- Has rough meeting notes and needs them turned into formal minutes
- Needs to write up minutes for a client, management, or team meeting
- Has a meeting transcript or recording summary to convert into a structured record
- Asks how to document a meeting professionally
- Needs to send post-meeting notes with clear action items and owners to stakeholders

## Step-by-step instructions

### Step 1 — Gather meeting information

Ask for the following if not already provided:
1. Meeting name or purpose (e.g., "Q1 Sales Review", "Client Kickoff — Infra Project")
2. Date, time, and duration
3. Attendees (names and roles — even partial list is fine)
4. The raw notes, bullet points, or transcript from the meeting
5. Any specific decisions or action items the user remembers as critical
6. Who the minutes will be shared with (internal team, client, management board)
7. Whether a follow-up meeting date was set

If the user provides only raw notes with no structure, proceed and extract everything
from the notes — do not ask for a perfectly organised input.

### Step 2 — Identify the meeting type and calibrate formality

Match the format and tone to the meeting context:
- **Internal team meeting** (weekly, sprint, ops): Concise, informal-professional,
  action-item focused. 1–2 pages maximum.
- **Client meeting** (kickoff, review, escalation): More formal, complete, careful
  language around commitments and decisions. Client-ready formatting.
- **Management or board meeting**: Formal, structured, complete record of all
  decisions and rationale. May need to be archived.
- **Project review meeting**: Milestone and risk focused, tied to project tracking.
  Must clearly show status, blockers, and next steps.

### Step 3 — Extract the five core components

From the raw notes, extract:

1. **Meeting context**: Date, time, location/platform, duration, attendees
2. **Agenda items discussed**: Main topics covered — structured summary of each
   topic in 2–4 sentences, not a full transcript
3. **Decisions made**: Every decision reached, stated clearly and definitively.
   Format: "It was decided that [X] by [date/condition]."
4. **Action items**: Every commitment made by any attendee.
   Format: [Action] | [Owner] | [Due date]
   No action item without an owner. No action item without a due date.
   If owner or date was not specified, flag as [TBC].
5. **Open issues or parking lot**: Topics raised but not resolved, deferred, or
   needing further input before a decision can be made

### Step 4 — Write the meeting summary

Write a 3–5 sentence executive summary at the top:
- What the meeting was about
- The 1–2 most important decisions made
- The overall outcome: productive / escalated / inconclusive / resolved
- Who needs to take action immediately

### Step 5 — Format the action items table

| # | Action Item | Owner | Due Date | Status |
|---|---|---|---|---|
| 1 | [Specific action] | [Name / Role] | [Date] | Open |

Rules:
- Imperative language: "Prepare", "Send", "Review" — not "Will prepare"
- Every action must be specific enough that the owner knows exactly what to do
- Status: Open / In Progress / Done / Deferred / TBC
- If more than 8 action items, group by theme or owner

### Step 6 — Write the decisions register

- Each decision in a separate bullet
- Format: "**Decision:** [What was decided.] [Conditions or rationale in one sentence.]"
- Avoid passive voice — decisions must be unambiguous

### Step 7 — Add the next steps and next meeting section

- Next meeting: date, time, platform, preparation required
- Pending items: anything carried over to the next agenda
- Distribution: who these minutes should be sent to

### Step 8 — Edge case handling and final delivery

Before delivering, check:
- Notes are very thin: Write based on what is available and add:
  "[Note to sender: Please review and add any decisions or actions not captured
  below before distributing.]"
- Conflicting information in notes: Flag the conflict — do not resolve arbitrarily.
  Note: "[Clarification needed: notes indicate both X and Y on this topic.]"
- Meeting was contentious: Document disagreement factually and note the next step
  to resolve it — do not take sides in the minutes.
- Client-facing minutes: Remove all internal commentary and informal language.
  Minutes sent to clients are a legal record of what was agreed.
- Action items have no owners: Flag all as [Owner TBC] and recommend the user
  assign owners before sending.

Output the complete meeting minutes. No preamble. Start directly with the header.

## Output format

---
MEETING MINUTES
[Meeting Name / Purpose]
---

Date: [Date] | Time: [Start – End] | Platform/Location: [Platform]
Prepared by: [Name or Role] | Distributed to: [Recipient list]

Attendees:
- [Name, Role, Organisation]

Apologies / Absent: [Names if applicable]

---

SUMMARY
[3–5 sentences: purpose, key decisions, overall outcome, immediate actions]

---

AGENDA ITEMS AND DISCUSSION

1. [Topic]
[2–4 sentence summary]

2. [Topic]
[2–4 sentence summary]

---

DECISIONS

- **Decision:** [Clear statement.]
- **Decision:** [Clear statement.]

---

ACTION ITEMS

| # | Action Item | Owner | Due Date | Status |
|---|---|---|---|---|
| 1 | [Action] | [Name] | [Date] | Open |

---

OPEN ISSUES / PARKING LOT

- [Issue deferred — note why and what happens next]

---

NEXT MEETING

Date: [Date] | Time: [Time] | Platform: [Platform]
Pre-read / Preparation required: [Items to review before next meeting]

---
Minutes prepared by [Name]. Please review and flag any corrections within 48 hours.

## Worked example

### Input

Meeting: Weekly project sync for website redesign project.
Date: 10 March 2026, 3 PM, Google Meet, 45 minutes.
Attendees: Neha (PM), Ravi (Developer), Sonal (Designer), Kiran (Client stakeholder).
Notes:
- Ravi said homepage is 80% done, will finish by Friday
- Sonal showed 3 logo options to Kiran, Kiran liked option 2 but wants to show his
  director first, will confirm by Wednesday
- Contact form needs to link to CRM. Ravi needs the CRM API credentials. Nobody
  knows who has them
- Launch date: maybe 25 March but Ravi said it might be tight if logo is delayed
- Neha to send revised project timeline to Kiran by tomorrow
- Next meeting same time next Monday

### Output

---
MEETING MINUTES
Website Redesign Project — Weekly Sync
---

Date: 10 March 2026 | Time: 3:00 PM – 3:45 PM | Platform: Google Meet
Prepared by: Neha (Project Manager) | Distributed to: Project team + Client

Attendees:
- Neha, Project Manager (Internal)
- Ravi, Developer (Internal)
- Sonal, Designer (Internal)
- Kiran, Stakeholder (Client)

Apologies / Absent: None

---

SUMMARY

The weekly sync reviewed progress on the homepage build, logo finalisation, and
contact form integration. The homepage is on track for completion by Friday. The
logo decision is pending client director approval by Wednesday and is the current
critical path item for the 25 March launch date. CRM API credential ownership needs
to be resolved urgently to unblock the contact form build.

---

AGENDA ITEMS AND DISCUSSION

1. Homepage Development Progress
Ravi confirmed the homepage is approximately 80% complete and on track to be fully
developed by Friday, 13 March. No blockers were raised for this workstream.

2. Logo Selection
Sonal presented three logo options. Kiran expressed a preference for Option 2 but
requires approval from his director before confirming. Kiran committed to providing
a final decision by Wednesday, 12 March. The logo decision is the current critical
path item for the launch date.

3. Contact Form and CRM Integration
The contact form requires CRM API integration. Ravi confirmed he needs the API
credentials to proceed. It was not established during the meeting who holds these
credentials on the client side. This is a blocker for the contact form build.

4. Launch Date Review
The target launch date of 25 March was discussed. Ravi noted this timeline may be
at risk if the logo confirmation is delayed. The team agreed to reassess at next
week's sync once both blockers are resolved.

---

DECISIONS

- **Decision:** Logo Option 2 is the preferred direction, subject to client director
  approval. Final confirmation required from Kiran by Wednesday, 12 March.
- **Decision:** The 25 March launch date remains the target but will be reviewed at
  the 17 March sync based on progress against current blockers.

---

ACTION ITEMS

| # | Action Item | Owner | Due Date | Status |
|---|---|---|---|---|
| 1 | Complete homepage development | Ravi | 13 March 2026 | In Progress |
| 2 | Obtain director approval for Logo Option 2 and confirm selection | Kiran | 12 March 2026 | Open |
| 3 | Identify and share CRM API credentials with Ravi | Kiran [TBC — confirm owner] | 12 March 2026 | Open |
| 4 | Send revised project timeline to Kiran | Neha | 11 March 2026 | Open |
| 5 | Proceed with contact form CRM integration once credentials received | Ravi | TBC (pending credentials) | Blocked |

---

OPEN ISSUES / PARKING LOT

- **CRM API credentials ownership**: Unclear who on the client side holds the
  credentials. Kiran to confirm and share by Wednesday.
- **Launch date risk**: If logo or CRM credentials are delayed beyond 12 March,
  the 25 March launch date will require revision. To be reassessed 17 March.

---

NEXT MEETING

Date: 17 March 2026 | Time: 3:00 PM | Platform: Google Meet
Pre-read / Preparation required: Ravi to share homepage screenshot; Kiran to bring
logo final decision and CRM credentials update.

---
Minutes prepared by Neha. Please review and flag any corrections within 48 hours.
