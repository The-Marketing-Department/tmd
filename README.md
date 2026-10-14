# TMD Operations Hub

The Marketing Department (TMD), tmdvi.com. Operations, planning and task tracking for TMD's own work and its client projects.

**Maintained by:** Trixie (Marketing and Operations Manager)
**Last updated:** Wednesday 14 October 2026

Priorities, tasks, paused work and completed work are tracked on the GitHub projects (**TMD Marketing** and **HOTVI Marketing**), not in this README.

---

## How We Use GitHub

GitHub replaces Asana (and WhatsApp task lists) for task tracking. It costs less and connects to Claude for workflow automation.

| Where | What lives there |
|---|---|
| `The-Marketing-Department/tmd` (this repo) | TMD's own operations: website, LinkedIn, SEO/GEO, internal systems, team process. Tracked on the **TMD Marketing** project |
| `The-Marketing-Department/hotvi` | Everything for the HOT (Honoring Our Truth) menopause clinic project, tracked on the **HOTVI Marketing** project |
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
| Status (board columns) | `status: backlog`, `status: this week`, `status: in progress`, `status: blocked`, `status: review`, `status: paused`, then close the issue when done |
| Priority | `priority: 1`, `priority: 2`, `priority: 3` (the top-level goals each project is working toward) |
| Owner | `owner: trixie`, `owner: gella`, `owner: greth`, `owner: quiana`, `owner: tamesh`, `owner: client` |
| Phase (client projects) | `phase: 0 discovery`, `phase: 1 build`, `phase: 2 production`, `phase: 3 pre-launch`, `phase: 4 launch`, `phase: 5 optimize` |
| Type | `type: deliverable`, `type: decision`, `type: access`, `type: recurring`, `type: dependency` |

### Setting Up a Kanban Board (one time per repo)

1. On GitHub, go to the organization **The-Marketing-Department**, open **Projects**, and click **New project**.
2. Choose the **Board** template. Name it after the work it tracks (for example "HOTVI Marketing" or "TMD Marketing").
3. In the project's **Settings**, find **Status** and set the columns: Backlog, This Week, In Progress, Blocked, In Review, Paused, Done.
4. In the repo, open the **Projects** tab and click **Link a project** to link the board.
5. Under the board's **Workflows**, turn on **Item added to project → Backlog** and **Item closed → Done**.
6. Copy `.github/workflows/add-to-project.yml` from this repo into the new repo and change `PROJECT_TITLE` to the board's name. It adds every new issue to the board in Backlog. It needs the `PROJECTS_TOKEN` secret, either as an organization secret the new repo can use or as a secret on the repo itself.
7. Click **Add item** and add the existing issues from the repo, then drag each one to the column that matches its `status:` label.

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

## Working Principles

- **Flag, don't bodge.** If something can't be done properly, log it on the issue and raise it.
- **Nothing publishes without approval.** Having access isn't the same as having the go-ahead.
- **Copy traces to an approved source.** No brand language invented on the fly.
- **Title case** in headings, applied consistently.
- **Check desktop and mobile separately.** Every time.
- **No em dashes** in written deliverables.
- **Track hours per task.** If a task heads more than 20% over its estimate, stop and tell Trixie.
