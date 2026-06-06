<!-- Source: https://help.taxdome.com/article/106-pipelines-create-setup (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Add & set up pipelines

## Start from a ready-made template

You can download ready-made pipeline templates created using best practices. They can be edited easily.

**Tip:** Installing a pipeline template also includes all templates inside it, such as for tasks, chats, emails, and so on.

To add a pipeline from the Marketplace:

1. Go to **Templates > Marketplace** from the left menu bar and select the **Pipelines** tab.
2. Click **Get free** on the template you want to add or click on its price and proceed with payment if it's a paid template.
3. Go to **Templates > Pipelines** and click on the template name to review and edit stages and automations.

You can also share your pipeline templates with other TaxDome users by selling them on the Marketplace.

## Create pipelines from scratch

A firm owner, admin, or team member with access rights to manage pipelines can create a pipeline. From **Templates** or **Workflow**, go to **Pipelines**, then click **Create Pipeline**.

The pipeline creation flow consists of three stages: Pipeline stages, Pipeline job statuses, and Pipeline settings.

### Pipeline stages

To set up pipeline stages, go to the **Stages** tab:

1. Enter a name for the pipeline (what you'll see in the **Workflow** section).
2. Enter the name for the first stage.
3. Link automations to stages as needed. Once a job moves to a new stage containing automations, those actions are triggered automatically one by one. For example, a task is created, an organizer is generated, and an email is sent.
4. Switch the **Automove** toggle to move a job automatically once linked actions are completed.
5. Set up a stage time limit indicating the maximum time spent in the stage before it becomes overdue.
6. Add as many stages as needed and link automations to them.
7. Save the pipeline.

### Pipeline job statuses

Job statuses help you track progress and handle blockers in your pipeline. By default, jobs can be:

- **Active** (work can continue)
- **Completed** (work is done)
- **Archived** (finished or canceled)

You can also create custom job statuses to manage exceptions without adding extra stages. For example, put a job on hold due to missing information, additional requests, or extended deadlines. Custom statuses keep your pipeline organized and provide visibility to your team, while automations can be triggered when a status changes.

### Pipeline settings

Go to the **Settings** tab and configure pipeline settings:

1. Select the team members who need access to the pipeline. The pipeline creator is added by default. The firm owner and admins see the pipeline regardless of this field value.
2. Decide how you want jobs sorted in the stages. By default, they're sorted by account name, but you can also sort by: time in a stage, start date, due date, creation date, stage time limit overdue, or priority.
3. Decide whether a template should be applied to jobs entering the pipeline and how (automatically or manually).
4. Decide what you want displayed on job cards.
5. Schedule jobs that repeat to be automatically created inside the pipeline.
6. Save the pipeline. Once done, you can click **Go to pipeline** and start adding jobs to it for your client accounts.

**Tip:** If you create a test client account, you can create a job for it to test how your pipeline works and check everything from the client's perspective.

## Edit pipelines

A firm owner, admin, or team member with access rights to manage pipelines can edit a pipeline.

**Tip:** When editing a pipeline, only the latest version is saved. To keep the original, duplicate the pipeline before making changes.

To edit a pipeline:

- **From the kanban view:** Click **Edit** at the top right of the page.
- **From the pipeline templates list:** Go to **Templates > Pipelines**, then click on the pipeline name.
- **From the pipeline list:** Go to **Workflow > Pipelines** from the left menu bar, click three dots to the far right of the pipeline name, then select **Edit**.

Once in the edit window, you can change pipeline settings from the **Settings** tab or make changes to stages from the **Stages** tab.

### Make changes to stages and automations

- To add a stage, click **Add stage** or the **+** button, then enter the stage name.
- To move a stage, point to the move icon to the left of the stage name, then drag-and-drop it.
- To delete a stage, click the trash can icon to the right of the stage name and confirm deletion.

**Warning:** When you delete a stage in a pipeline, all jobs at this stage will be deleted. Make sure all necessary information is saved to prevent data loss.

- To add automation to a stage, select the stage, then click **Add automations** button or on any existing automation.
- If you want additional emails sent to clients when they don't respond within a certain timeframe, locate **Reminders** below the automation template, then select **Enable** in the drop-down.

When done, click **Save**. Then you can click **Go to pipeline** to see your changes.

## Duplicate pipelines

To create new pipelines based on existing ones:

- Go to **Templates > Pipelines** from the sidebar menu, click three dots to the far right of the pipeline name, then click **Duplicate**.
- Go to **Workflow > Pipelines** from the sidebar menu, click three dots to the far right of the pipeline name, then click **Duplicate**.

A copy of the pipeline is saved with a suffix (e.g., 1040 Return (2)). Stages, automations, and other template settings are copied as well. However, you'll need to manually add jobs to a newly duplicated pipeline.

## Delete pipelines

A firm owner, admin, or team member with access rights to manage pipelines can delete a pipeline. Go to **Templates > Pipelines** from the sidebar menu, click three dots to the far right of the pipeline, select **Delete**, and confirm deletion.

**Note:** This deletes all jobs linked to the pipeline.

---
*Source: [Add & set up pipelines](https://help.taxdome.com/article/106-pipelines-create-setup) — official TaxDome documentation.*
