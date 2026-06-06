<!-- Source: https://help.taxdome.com/article/137-documents-explained (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# Document and folder permissions

## Permission levels

TaxDome offers three permission levels for document management:

- **None** - hides the item from the team member or client
- **View** - allows viewing but prevents editing, deleting, or uploading to folders
- **Edit** - permits editing, deleting, and uploading items to folders

## Permission inheritance

Access to a top-level folder automatically extends to all subfolders and documents within it. When documents move to different folders, they adopt the new folder's permissions. Individual permissions override default settings and enable customized access per document or folder for specific users.

## Where to find permissions information

View document permissions in these locations:

- **Documents > Client Docs > Docs**
- **Clients > Accounts > Docs**

The interface displays an **Individual permissions** column alongside the default access level.

### Icon meanings

- Individual permissions icon appears when default permissions have been modified
- Client can view and edit icon indicates shared folders with full client access
- Client can view icon shows read-only access for clients
- Private icon indicates folders hidden from clients

## Default permissions

Default access depends on folder structure and account assignments:

### Clients' default permissions

Client access is determined by the top-level folder type containing documents. Admins and owners with **Manage documents** rights can create folders, apply templates, and move documents to control client access.

> **Important:** Each client account requires at least one "Client uploaded documents" folder with edit access. This folder cannot be deleted, only renamed.

### Team members' default permissions

- Owners and admins have full access to all folders and documents
- Team members with no special permissions view only assigned clients' documents
- **Manage documents** permission allows folder creation and file uploads for assigned clients
- **View all accounts** permission enables document management across all clients
- **Assign team members** permission allows delegating client access

## Individual permissions

Individual permissions provide granular control:

- Grant access to specific documents regardless of folder structure
- Restrict access to single documents even in viewable folders
- Share private folder documents with clients without moving them

### How to grant individual permissions

1. Navigate to the **Docs** section (from Clients or Documents menu)
2. Click the three dots next to the document/folder
3. Select **Manage permissions**
4. Switch to the appropriate tab (team members or client)
5. Select the person and choose the access level: **View**, **Edit**, or **None**
6. Click **Save**

For Windows app uploads, click **Manage access** in file actions to set individual permissions in your browser.

### How to revoke individual permissions

1. Go to the **Docs** section
2. Click the three dots next to the document/folder
3. Select **Manage permissions**
4. Switch to the appropriate tab
5. Select the person whose permissions you want to revoke
6. Choose **Reset to default**
7. Click **Save**

---
*Source: [Document and folder permissions](https://help.taxdome.com/article/137-documents-explained) — official TaxDome documentation.*
