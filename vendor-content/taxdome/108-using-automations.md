<!-- Source: https://help.taxdome.com/article/108-using-automations (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Automations explained

## Automations in pipelines at a glance

An automation is a mechanism that makes your workflow operate automatically. TaxDome automations initiate actions for you, your team members, or your clients during different pipeline stages or custom job statuses:

- **Pipeline stage automations:** trigger actions as a job moves through the stages of a pipeline.
- **Custom job status automations:** trigger actions that move a job from a custom job status (e.g., Missing information) back to Active.
- **Jobs automove:** automatically moves a job to the next stage when all requirements for the current stage are met.

For example, your firm has a Personal Tax process. You may want to have an introductory email and a customized organizer to be automatically sent to the client. Then, when the client submits the organizer, the job for their account automatically moves to the next stage, e.g., Tax Prep. You may then want to initiate a task for a team member to complete, and so on.

Designing your own automations starts with the workflow itself. Map the stages of a process, identify the points that need a follow-up action — sending a document, creating a task, updating account access — and each of those follow-ups becomes a candidate automation.

## How automations work

A stage automation has two moving parts: a trigger that fires it, and an action it performs on the job. For any single job, the sequence is:

1. The job enters a stage of a pipeline, or is assigned a custom job status.
2. Every automation configured for that stage or status runs in order. Conditional automations run only when the client matches the condition.
3. Each automation produces its action item on the job: an organizer awaiting the client's submission, a task awaiting a team member's completion, an invoice awaiting payment, and so on.
4. If jobs automove is enabled, the job advances to the next stage (or a custom status returns to **Active**) as soon as all action items in the stage are resolved. If automove is off, the job stays in place until someone moves it manually.

## Automations vs. Job automove

Automations and job automove work together but solve different parts of the workflow. Automations set up _what_ happens inside a stage; automove decides _when_ the job advances to the next one.

- **Automations** trigger actions as soon as a job enters a stage or a custom job status: send an organizer to the client, create a task for a team member, send an invoice or proposal, apply a folder template, update account access, and more. They define the work that needs to be done in the stage.
- **Job automove** moves the job to the next stage automatically once all action items in the current stage are completed, or changes a custom job status to **Active** once the configured conditions are fulfilled. Automove can be toggled on or off per stage, except for the last stage of a pipeline.

The two features form a cause-and-effect chain. For example, the **Send organizer** automation delivers an organizer when the job enters the stage, and automove progresses the job to the next stage as soon as the client submits it. Not every automation triggers automove.

## Access and permissions

The firm owner and admins can add and manage automation in the pipeline by default. Other team members need the **Manage pipelines** access right.

**Note:** Granting **Manage pipelines** also grants edit rights to every pipeline the team member can access. Use the **Available to** dropdown to scope which pipelines that applies to.

## Client view

Automations run entirely on the firm side. Clients don't see pipelines, stages, or automation triggers, and they have no way of telling whether an organizer, invoice, proposal, or email was sent manually by a team member or generated automatically when a job moved to a new stage. From the client's perspective, every automated action looks like a regular notification in the client portal, mobile app, or inbox.

---
*Source: [Automations explained](https://help.taxdome.com/article/108-using-automations) — official TaxDome documentation.*
