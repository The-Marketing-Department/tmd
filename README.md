# TMD Operations Hub

The Marketing Department (TMD), tmdvi.com. Operations, planning and task tracking for TMD's own work and its client projects.

**Maintained by:** Trixie (Marketing and Operations Manager)
**Last updated:** Wednesday 14 October 2026

---

## How We Use GitHub

GitHub replaces Asana (and WhatsApp task lists) for task tracking. It costs less and connects to Claude for workflow automation.

| Where | What lives there |
|---|---|
| `the-marketing-dept/tmd` (this repo) | TMD's own operations: website, LinkedIn, SEO/GEO, internal systems, team process |
| `the-marketing-dept/hotvi` | Everything for the HOT (Honoring Our Truth) menopause clinic project, with its own Kanban board |
| One repo per client | New client projects get their own repo and board, set up the same way as `hotvi` |

### The Rules

1. **Every task is an issue.** If it isn't an issue, it isn't on the plan.
2. **One owner per issue.** We use an `owner:` label (for example `owner: gella`). Support people are named in the issue body.
3. **Every issue has a due date** in the title or body, plus the done criteria.
4. **Move the card when the status changes.** Don't wait for the meeting.
5. **Blocked? Label it `status: blocked`** and comment who or what you're waiting on. A blocker raised at hour one costs nothing. The same blocker at end of day costs the deadline.
6. **Approvals before publishing.** Nothing goes live or to a client without the approval gate on the issue being ticked.

### Labels

| Group | Labels |
|---|---|
| Status (board columns) | `status: backlog`, `status: this week`, `status: in progress`, `status: blocked`, `status: review`, then close the issue when done |
| Owner | `owner: trixie`, `owner: gella`, `owner: greth`, `owner: quiana`, `owner: tamesh`, `owner: client` |
| Phase (client projects) | `phase: 0 discovery`, `phase: 1 build`, `phase: 2 production`, `phase: 3 pre-launch`, `phase: 4 launch`, `phase: 5 optimize` |
| Type | `type: deliverable`, `type: decision`, `type: access`, `type: recurring`, `type: dependency` |

### Setting Up a Kanban Board (one time per repo)

1. On GitHub, go to the organization **the-marketing-dept**, open **Projects**, and click **New project**.
2. Choose the **Board** template. Name it after the repo (for example "HOTVI Project").
3. In the project's **Settings**, find **Status** and set the columns: Backlog, This Week, In Progress, Blocked, In Review, Done.
4. Under **Workflows**, turn on **Auto-add to project** for the repo (filter `is:issue`), and **Item closed → Done**.
5. Click **Add item** and add the existing issues from the repo, then drag each one to the column that matches its `status:` label.

---

## Team and Capacity

| Person | Role | Weekly hours | Reports to |
|---|---|---|---|
| Quiana Adams | Founder. Strategy, client relationships, final approvals | | |
| Trixie | Marketing and Operations Manager. Planning, coordination, funnel and systems, QC and brand review | ~20 | Quiana |
| Gella | Marketing assistant. Access, inventories, weekly website QA, audit support | ~30 | Trixie |
| Greth | Social media, content, LinkedIn outreach (replacing Vaibhav) | ~40 | Quiana |
| Tamesh | Web and graphic design | As needed | Quiana |

### Meeting Cadence

| Meeting | When | Purpose |
|---|---|---|
| All-hands team meeting | Wednesdays, 9:30 AM | What we finished, what we're finishing, what to pivot |
| Trixie and Quiana 1:1 | Fridays | Decisions, approvals, priorities for next week |

Zoom transcripts go in the Zoom transcripts folder on the access@tmdvi.com Drive.

---

## Current Priorities (week of 12 October 2026)

1. **HOT clinic proposal** (see `the-marketing-dept/hotvi`). Final signed proposal by **Wednesday 18 November**. Clinic launch is **February 2027**.
2. **TMD client acquisition.** SEO/GEO with the outside specialist, LinkedIn outreach run in-house by Greth, and a website that stays error-free.
3. **Team systems.** Move to GitHub, the access@tmdvi.com Drive and the "hot" Slack channel.

### Paused (don't spend hours here until Quiana reopens them)

- **Dwellr.** Fully paused. The September social strategy and the seven open decisions are on hold.
- **Upwork proposal templates and LinkedIn company page optimization.** Not needed right now. Upwork is on the free plan and connects are bought as needed.
- **Blotato vetting.** Parked so we can focus on HOTVI.
- **Client presentation template** (the walkthrough-style pitch deck Quiana liked). For later.

### Done

- Blog migration to the new Showit site, and the site is live (Gella)
- Website error fixes, including the duplicate "3" in the services numbering (Trixie)
- Decision to replace Vaibhav with Greth for LinkedIn outreach. Greth has the LinkedIn Outreach SOP (v2, 13 Oct), which tracks daily activity. Outcome KPIs are still to be added (issue #4).

---

## TMD Task Board

Every item below is an issue in this repo.

| Task | Owner | Due | Status |
|---|---|---|---|
| Create the "hot" Slack channel and add the team | Trixie | Wed 14 Oct | This week |
| Check access to Zoom meeting notes and tell Quiana | Trixie | Wed 14 Oct | This week |
| Add the Claude upgrade note to the working document | Trixie | Fri 16 Oct | This week |
| Add outcome KPIs and a pivot rule to the LinkedIn Outreach SOP (it tracks activity only) | Trixie | Fri 16 Oct | This week |
| Copy Vaibhav-owned outreach docs into the TMD Drive before his access ends | Trixie | Fri 16 Oct | This week |
| Set up the GitHub workflow and demo it at the all-hands meeting | Trixie | Wed 21 Oct | In progress |
| Weekly website QA (links, forms, errors, desktop and mobile) | Gella | Every Friday | Recurring |
| Update Greth's photo on the website | Trixie | When the photo arrives | Blocked on Quiana |
| Social post bank review and posting timeline | Trixie | After Quiana's review | Blocked on Quiana |
| SEO/GEO 90-day scope. Trixie is on standby for blog writing | Quiana | Pending | Blocked on the specialist |
| Transfer shared-drive files to the access@tmdvi.com Drive and create the Zoom transcripts folder | Greth | This week | This week |
| November and December content plans for Dr. Bailey and Danielle | Greth | Before the December break | This week |

---

## Working Principles

- **Flag, don't bodge.** If something can't be done properly, log it on the issue and raise it.
- **Nothing publishes without approval.** Having access isn't the same as having the go-ahead.
- **Copy traces to an approved source.** No brand language invented on the fly.
- **Title case** in headings, applied consistently.
- **Check desktop and mobile separately.** Every time.
- **No em dashes** in written deliverables.
- **Track hours per task.** If a task heads more than 20% over its estimate, stop and tell Trixie.
