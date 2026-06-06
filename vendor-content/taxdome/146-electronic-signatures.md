<!-- Source: https://help.taxdome.com/article/146-electronic-signatures (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Request e-signatures from clients

**Tip:** When requesting e-signatures on completed tax returns, you can use [tax return delivery](https://help.taxdome.com/article/tax-return-delivery) to combine document review, signatures, and payment in one guided client flow.

## Before you start

To proceed with the signature request:

- Make sure your document is a **PDF** file.
- Make sure the doc has **Client can view** permission level. If it hasn't, [move the document](https://help.taxdome.com/article/145-how-to-move-documents#1) to the folder with **Client can view** permission level or grant the client [individual permissions](https://help.taxdome.com/article/137-documents-explained/).
- Decide whether you want to allow your clients to sign documents without logging in. If yes, disable the **Require login for e-signature** toggle. Those who don't use the client portal can sign docs per your request, regardless of this setting.

## Request e-signatures from clients

To request an e-signature from a client, follow these steps:

**Web Desktop**

You can request e-signatures either directly from the document viewer or from the document list. To request it from the document viewer, click the **Request signature** icon in the top-right corner, or select **Request signature** from the three-dot menu.

To request it from the document list:

1. Click the three dots to the far right of the document name, then select **Request signature**.
2. Choose the signer in the **Signers** list or apply a [signature template](https://help.taxdome.com/article/537-signature-templates). You can select any contacts linked to the account or [add a third-party signer](#request-e-signatures-from-third-parties).
3. Drag and drop the e-signature field. If needed, hover over one of the field corners and resize the signature field.
4. Click **Send.** For details on the signature request menu, go to the subsection below.

After sending the signature request, you can open the document to view where the signature fields have been placed.

After uploading a document via the [Windows app](https://help.taxdome.com/article/728-windows-app-download-install), click **Request e-signatures** in the [file actions menu](https://help.taxdome.com/article/windows-app-interface#web-actions). This will open the signature editor in your browser, where you can place signature fields and send to the client.

**Note:** This action is visible for documents in folders with the **Client can view** access level.

## Signature request menu

You have various options when requesting an e-signature, which we'll describe in more detail below:

**a. Require KBA / QES/AdES:** add the [KBA](https://help.taxdome.com/article/287-knowledge-based-authentication-kba) authentication method (for your US clients only) or [QES/AdES](https://help.taxdome.com/article/1328-signatures-advanced-qualified-electronic-signature-qes) signature (for your EU clients only). If QES/AdES is selected, the following flow differs as described in the [detailed article](https://help.taxdome.com/article/1328-signatures-advanced-qualified-electronic-signature-qes).

**b. Template:** if you've created [signature templates](https://help.taxdome.com/article/537-signature-templates) to save time with frequently used forms, here is where you can select one.

**c. Signers:** select a signer for whom you want to add signature fields.

Click a signer name, then drag and drop the signature fields below.

- Click **X** to the right to delete a signer.
- To add a field for a firm rep, select the **Me** option (details below).
- Change the [default signing order](https://help.taxdome.com/article/565-edit-signers-list).

**d. Add signer:** select the account's contacts to sign the document or [add a new signer using their email address](#request-e-signatures-from-third-parties).

**e. Signature fields:**

- **Signature:** use this for an e-signature by a client or firm representative. Each signature field contains the signature, date and time of signing.
- **Initials:** use this whenever you need the client or firm representative to add their initials.
- **Date signed:** this field is populated when the client signs the document, and the firm representative will see it in the TaxDome server timezone. In the firm representative fields, dates appear when documents are sent to clients. Dates cannot be edited.
- **Text:** request or add extra information:
  - To request additional data, place the field where you want it to be, then click on it to edit.
  - To add info, place the prefilled field where you want it to be, then click on it to edit.

**Note:** The appearance of content inside fields (such as signatures, initials, dates, and text) can't be customized. Only the size can be adjusted by dragging the field corners.

**f. Date format:** select the date format for e-signatures. If not set manually, the [default date format](https://help.taxdome.com/article/935-settings-basic-change-your-default-date-format-for-e-signatures) is used.

**g. Reminders:** toggle this on if you want an email notification to be automatically sent to the client if they don't sign on time (details below). Reminders will include text from the next field—**Message for client**.

**h. Message for client:** This message will replace the default text in the email system notification sent along with the signature request. This email won't be accessible to you after you send the request. To reuse it, consider adding it to the [signature template](https://help.taxdome.com/article/537-signature-templates).

**i. Add shortcode:** these are codes that are automatically replaced with key information in the **Message for client** field, such as the recipient's name, address, account name or date (read more about [shortcodes](https://help.taxdome.com/article/594-shortcodes-basic-applying-shortcodes)).

**j. Send:** click here when the document is ready to be signed.

**k. Save:** save your changes without sending the document: all added fields are saved, and the document is visible under the **Docs** tab in the **Signatures** section. You'll still be able to review the document and add or delete fields. The document isn't visible to the client until you hit **Send**.

## Request e-signatures from third parties

If your client doesn't use the client portal, or if you need someone else (e.g., someone with a power of attorney) to sign the document, requesting their signature is also possible. When you need to add signers, follow these steps:

1. Click **Add signer** under the **Signers** list. Select **New signer**.
2. Enter their **First name, Last name** (optional) and **Email address**.
3. (optional). If they need portal access later, enable the **Create new contact** toggle. If you want to add any contact details, expand the **Contact info** section and fill in the field you need.
4. Click **Confirm**. This will add them to the **Signers** list. Request their signature as if they were just another contact linked to the account.

When you request a signature from a non-client, the signer receives a unique link via email. The link will be valid for 7 days. They will be able to sign by clicking it, no authorization is needed.

## Add firm representative's e-signature

Most documents need to be signed by one or more tax preparers. If you need several company reps to sign, add fields for them and edit them indicating each team member's name.

When requesting an e-signature from a team member, select **Me** in the **Choose signer** drop-down. The available fields are:

- **Signature:** Your name appears by default, but you can change it. If you need more signature fields for firm reps, add more, then edit the names.
- **Initials:** By default, the selected initials appear, but you can edit the field as needed.
- **Date:** This field is automatically populated when the document is sent to the client.
- **Text:** Add your firm's name, address or any other necessary details.

**Tips:**

- If you need to change your name or initials, click and edit the field.
- If a signature field is added for a firm rep, and the document hasn't been sent to the client, the field can be edited or deleted by any team member with access to the client's account documents.
- Once you send the document to the client, the document is considered signed by your firm, and the client can see this (excluding [QES/AdES](https://help.taxdome.com/article/1328-signatures-advanced-qualified-electronic-signature-qes) signatures).
- If signature fields for firm reps are added, and the document hasn't been signed by the client yet, you still have time to [cancel the e-signature request](https://help.taxdome.com/article/552-e-signature-requests-how-to-view-and-cancel#10) if needed.
- The document's audit trail shows who created each firm rep's signature field in the document.

## Set up e-signature reminders

[Reminders](/article/119-automatic-reminders) are automatic follow-up emails that nudge clients who haven't signed a document yet.

**Note:** The email link in a signature request expires in 7 days. Reminders help you nudge clients before the link goes stale. If the client misses the email window, they can still sign through the client portal — no expiration there.

To turn them on, toggle on **Reminders** when requesting an e-signature, then set:

- **Days until next reminder** — how often the reminder repeats (default: 3)
- **Number of reminders** — how many reminders to send in total (default: 1)

You can update these settings later by opening the pending document in the client account's **Docs > Signatures** subtab — even after one signer has e-signed it.

To resend a signature request manually at any time, click the three dots to the right of the document and select **Resend**. You can also resend from the document viewer using the **Resend signature request** icon in the top-right corner.

**Tip:** More on [reminders](/article/reminders-reference) — exact field defaults, stop conditions, and the menu action for each manual resend.

## Client view

If [notifications](https://help.taxdome.com/article/127-multiple-logins-profile-access#5) for the client are on, they are informed on receiving a signature request. Your clients can see and open signature requests in different ways:

- **From the client portal or mobile app:** Click the notification under the **Home** page tasks list or in the **Waiting for action** section. They can also open it directly from the **Documents** page.
- **From the email notification:** Click **Review & sign** in the email.

If signers can [sign the document without logging in](#request-e-signatures-from-third-parties), the email link will be valid seven days after it's sent.

When you request an e-signature from more than one user for an account (e.g., spouses), each user will see only their own e-signature field. The document remains in **Pending E-Signature** [status](https://help.taxdome.com/article/552-e-signature-requests-how-to-view-and-cancel#2) in the **Signatures subtab** until both parties have signed it.

When a client receives a signature request for the first time, they will be prompted to read the **Electronic Signatures Disclosure** and agree to use e-signatures.

To see the sent signature request from the client's perspective, access the [read-only view](https://help.taxdome.com/article/221-access-the-read-only-view-of-client-account).

---
*Source: [Request e-signatures from clients](https://help.taxdome.com/article/146-electronic-signatures) — official TaxDome documentation.*
