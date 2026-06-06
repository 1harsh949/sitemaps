<!-- Source: https://help.taxdome.com/article/1826-pipelines-overview (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Pipelines explained

Pipelines are a visual, stage-based representation of the work your firm does for clients — from start to finish. They let you track every client job at a glance, hand work off between team members, and automate repetitive steps so nothing falls through the cracks.

## Pipelines at a glance

A pipeline is a reusable, stage-based blueprint for a service your firm delivers — tax preparation, monthly bookkeeping, payroll, onboarding. Each pipeline is made up of ordered **stages**; each client engagement moves through it as a **job**; and each stage can fire **automations** that send emails, create tasks, issue invoices, send organizers, and more.

Here is what you can do with pipelines:

*   **Build a stage-based workflow** — design the steps any client engagement moves through, with optional stage time limits to flag overdue work.
*   **Automate work at every stage** — trigger emails, tasks, invoices, organizers, proposals, and more when a job enters a stage.
*   **Advance jobs automatically** — move a job to the next stage when all its action items are complete.
*   **Branch by client type** — run specific stages or automations only for certain clients based on account tags.
*   **Schedule recurring work** — for monthly bookkeeping or quarterly filings, set job recurrences so jobs are created on a cadence.
*   **Track exceptions with job statuses** — every job is **Active**, **Completed**, or **Archived** by default; create custom statuses like _On hold_ without adding stages.

## Pipelines vs jobs vs tasks

These three terms are often confused:

*   **Pipeline** — the template: ordered stages, the automations attached to each stage, and the rules (recurrences, conditional logic, time limits) that govern how work flows. A pipeline exists once and is reused across clients.
*   **Job** — one instance of work moving through a pipeline for one client account. A single pipeline can hold hundreds of jobs at different stages at once.
*   **Task** — a discrete to-do inside a job, assigned to a team member.

## How pipelines work

A pipeline becomes useful the moment you start pushing jobs through it. At a high level, the flow is:

1.  You create a pipeline, either from scratch or from a Marketplace template, and tailor its stages and automations to your firm's process.
2.  You add a job for a client account — manually, in bulk, or automatically via a recurrence schedule.
3.  When a job enters a stage, any automations attached to that stage run in order — for example, an engagement letter is sent, a task is created for the preparer, and a follow-up email is queued.
4.  The job moves to the next stage either manually, when your team clicks through, or automatically once all stage actions are complete.
5.  When the job reaches the final stage and the work is done, it's marked **Completed** and can be archived to keep the kanban view clean while preserving the full record.

## Access and permissions

The firm owner and admins can see and manage every pipeline in the firm by default.

Other team members need two things:

*   The **Manage pipelines** access right, which lets them create and edit pipelines.
*   To be added to the **Available to** list in the pipeline's settings, which controls visibility for individual team members.

Job-level visibility inside a pipeline is governed separately by account access and job assignees — a team member can see a pipeline but only the jobs tied to accounts they have access to.

**Note:** Granting **Manage pipelines** also grants edit rights to every pipeline the team member can access. Use the **Available to** list to scope which pipelines that applies to.

## Automate processes with pipelines

Pipelines are where most firm-wide automation lives. Rather than sending the same emails, creating the same tasks, and generating the same organizers for each client manually, you attach those actions to a stage once, and they run every time a job enters that stage.

Common automation scenarios:

*   **Client onboarding** — when a new client's job enters the first stage, automatically send an engagement letter, create an intake organizer, and notify the account manager.
*   **Document collection** — when a job moves into the _Awaiting documents_ stage, send an organizer and schedule automatic reminders until the client responds.
*   **Invoicing and payment** — issue an invoice when work is complete, and use automation to advance the job once the client pays.
*   **Recurring services** — for monthly bookkeeping or quarterly filings, job recurrences create the job automatically, and stage automations handle the rest.

## Client view

Clients never see the pipeline, stages, or jobs — that's your back-office view. They only see what automations send out: notifications, organizers, proposals, invoices, documents, and e-signature requests. Job progress stays on your side unless you choose to surface it.

If you want clients to track where their work stands, assign a client-facing job status to the job. The status appears in the client portal and can be updated manually, in bulk, or automatically by pipeline automations.

---
*Source: [Pipelines explained](https://help.taxdome.com/article/1826-pipelines-overview) — official TaxDome documentation.*
