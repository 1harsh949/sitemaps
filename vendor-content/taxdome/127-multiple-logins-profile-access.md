<!-- Source: https://help.taxdome.com/article/127-multiple-logins-profile-access (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Contact settings (login, notify, email sync, signatory)

## Contact settings, explained

Contact settings control the basic permissions and notifications for your client interactions:

- **Login** defines if the client has portal access.
- **Notify** defines if the client will receive system notifications and which ones.
- **Email sync** defines if you will receive emails from clients inside TaxDome.
- **Signatory** defines whether the contact can sign proposals & ELs or recurring invoices.

Each client account can be linked to multiple contacts, but you can configure contact settings for each linked contact separately. This allows you to provide portal access and other settings to specific contacts linked to the client account without giving it to the other contacts. Contact settings are always linked to contact email, so if your contact has two or more emails, you can select different settings for each.

You can access contact settings:

- in the **Info** tab of a client account
- when creating a new client account
- during client list import
- in your account list

You can streamline client management and update contact settings in bulk.

## Login, explained: manage portal access

When **Login** in the **Info** tab of the client profile is checked, the contact can access the TaxDome client portal. Usually, when you check the **Login** box, you may want to send the invitation to the client. However, you can check **Login** but choose to invite the clients later. This way, the account will be active but marked as **Pending activation**.

You can configure your portal to allow certain actions—such as viewing, signing, uploading documents, paying invoices and completing client requests—without requiring portal access.

### Enable portal access

You can check **Login** in the **Info** tab of the client account page to give portal access to the person to whom this email address belongs.

What this does:

- The user gets an invitation to the TaxDome client portal by email.
- Once they accept the invitation, they can sign in to the client portal.

Once you've added portal access to a contact's email address, you are prompted to send an email invitation to that user. When you click **Send**, TaxDome sends the person an activation request by email. To activate the account, the person accepts the request and creates a password. The new user is then automatically linked to the account. Each user has their own login credentials for an account.

If you want to turn the Login on but send the invite later, consider updating contact settings from account list.

### Remove portal access

If someone no longer wants to have access to an account, go ahead and remove them. Under the **Info** tab of the account profile, uncheck the **Login** box to the right of the user's email address. The account will remain intact; however, the user will no longer be able to access it.

## Notify, explained

The **Notify** setting in the **Info** tab of the client profile helps manage the system notifications sent to the specific client. It also affects bulk email feature - contacts with **Notify** off are not selected by default when sending emails in bulk.

### Select which notifications clients will receive

Decide which notifications the user should get by clicking the three dots to the far right of the email address, then selecting **Notification preferences**.

Notification preferences are only accessible when **Login** and **Notify** are enabled for the contact.

What the toggles mean:

- **Documents: File upload**: Notifications about new firm-uploaded documents
- **Documents: Signature requests**: Requests for documents pending signature and reminders about documents pending signature
- **Documents: Approvals**: Requests for documents pending approval and reminders about documents pending approval
- **Messages and client tasks**: Notifications about new messages, including client tasks, and notifications about new replies in chat threads
- **Proposals**: Request for new proposals and reminders about pending proposals
- **Organizers**: Requests for new organizers and reminders about pending organizers
- **Invoices and payments**: Requests for new invoices, reminders about pending invoices, confirmations for invoice payments, and notifications about refunds issued
- **Client requests**: Requests for new client requests and reminders about pending requests
- **Transactions**: The user will receive a weekly reminder email every Monday at 9:00 AM (in their time zone) with unanswered transaction questions

## Email sync, explained

When this is enabled, you and your team can see and reply to the client's emails right from TaxDome.

What this does:

- If **Email sync** is enabled, the **Email** tab appears under the **Communication** tab in the client account.
- All team members see all emails received from that address in the **Inbox+** section and in the **Communication** tab of the account profile and be able to reply from TaxDome.
- All history between your synced emails and the contact's emails will automatically populate on TaxDome.
- If **Automatically save attachments** is enabled, all future emails with attachments will automatically save the documents to the **Docs** section of the account.

Check **Email sync** for future clients who don't yet have portal access (their **Login** is still unchecked), so you can receive emails from them, too.

## Signatory, explained

Signatory defines whether the contact has authority to sign proposals & ELs or recurring invoices. When enabled, contacts can sign proposals, enter payment details for invoices included in proposals, and sign recurring invoices with payment details.

This setting is useful when you have multiple contacts linked to an account but only want specific contacts (such as primary account holders) to have signing authority.

## Update contact settings in bulk

Updating contact settings in bulk streamlines client management and saves time. This way, you can modify settings for all contacts linked to your selected accounts. To update contact settings in bulk, go to **Clients > Accounts** from the left menu bar and follow these steps:

1. Choose the clients by selecting checkboxes to the left of them.
2. Click **More Actions** and then select **Edit login, notify, email sync**.
3. Select an action from the drop-down to the right of each setting:

- **Do nothing**: The setting will not be updated.
- **Enable for all contacts**: The setting will be enabled for all contacts linked to the accounts.
- **Login**: Enabling Login allows you to select the **Send invitations** checkbox and add a message for the invitation email (optional).
- **Notify**: Enabling Notify allows you to toggle on **Customize notification preferences** and select the system notification types your clients will receive (optional).
- **Disable for all contacts**: The setting will be disabled for all contacts linked to the accounts.

Once done, you will receive an Inbox+ notification with a brief report on the bulk update result and a list of errors (if any).

## Do my clients have access?

You can quickly check whether your clients have portal access and view their **Login**, **Notify**, and **Email sync** settings in the **Clients > Accounts** section of the left menu:

- **Login**: The **ID** column in your client list indicates whether at least one contact linked to the account has portal access. Statuses are color-coded so you can identify them at a glance in your accounts list:
  - **Green** means the client account is **Activated**. The account has at least one user that can log on.
  - **Yellow** means the client account is **Pending activation**. The invitation was sent, but the client hasn't activated their account yet.
  - **Gray** means the client account is **Not activated**. The account exists on TaxDome, but the invitation was not sent, and the account doesn't have users that can log in.

- **Notify** and **Email sync**: the **Notify** and **Email sync** columns indicate whether the setting is enabled for at least one contact linked to the client account.

If you don't see these columns, customize your client account list to display them.

## Add multiple email addresses

Because a contact is a person, it's natural that one contact might have several email addresses (personal, work, etc.). By default, each contact has one email address field, but you can manually create extra CRM fields or add ones while you're creating new contacts manually or importing them.

In the account profile, open the **Info** tab, then review the **Contacts** section. Here, you can view all email addresses and phone numbers for the contacts linked to the account. If you want to add email addresses that aren't listed, either add another linked contact or add another email address to the contact that is already linked.

Follow these steps:

- Create custom CRM email fields to store the additional email addresses.
- Update the existing contact to include an additional email address.
- Turn on the **Login, Notify** and/or **Email sync** settings for the email address if you need to.

## Notifications and emails for clients pending activation

If you've turned on contact settings for a contact linked to an account, but they haven't yet activated their account, they'll still receive TaxDome email and system notifications:

- All regular email you send from TaxDome will go out to the recipient regardless of whether their account is activated or not. You also can receive **Inbox+** notifications about new emails from that contact linked to the account (set this up in your Notification settings).
- All system notifications will go to the contact's email address and will include the **Account activation** banner at the top of the email until they have activated the account.

You can always resend an invitation.

## Change an email address for a client

When a client's email address changes, add their new email address as if they were an additional user.

Make sure not to immediately remove the obsolete email address.

Instead, follow these steps:

1. Update the client contact to include the new email address instead of the old one.
2. Check the **Login** box and wait for the user to accept the invitation sent to the new email address, so that they don't lose access to their account.
3. Once the client has accepted the invite, delete their previous email address from the **Unlinked Emails** section by toggling the **Login** off.

If you change the email address before the invited person clicks the invitation link, it'll be deactivated for security reasons. A new invitation email will be sent to the updated email address.

## How clients can switch between accounts in the client portal

They can switch to the other account anytime later by clicking on the to-dos in the other accounts at the bottom of the **Home** page or by selecting the other account from the top right of the page.

---
*Source: [Contact settings (login, notify, email sync, signatory)](https://help.taxdome.com/article/127-multiple-logins-profile-access) — official TaxDome documentation.*
