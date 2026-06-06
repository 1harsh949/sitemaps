<!-- Source: https://help.taxdome.com/article/173-integration-with-quickbooks (official TaxDome help page, mirrored 2026-06-06 for KB ingestion) -->

# QuickBooks integration for billing explained

The QuickBooks integration for billing links TaxDome to your QuickBooks Online account so payments, invoices and services from TaxDome appear in QuickBooks automatically. The integration is most useful for firms that invoice clients only or mostly in TaxDome.

**Note:** This integration is for client billing and payments. For bookkeeping transactions integration, refer to our article on processing bookkeeping transactions.

## QuickBooks integration at a glance

The QuickBooks integration mainly works one way: invoices and payments are sent from TaxDome to QuickBooks, not backward. If you prefer to invoice clients initially in QuickBooks, you'd have to manually duplicate records from QuickBooks in TaxDome.

Here is what you can do with the QuickBooks integration:

- **Sync client accounts**: link TaxDome accounts with QuickBooks customers and track sync statuses from your account list
- **Sync invoices and payments**: transfer invoices and payments to QuickBooks automatically, sync offline payments and match invoice numbers
- **Sync services**: keep TaxDome service-specific data (services, rates, quantities and categories) aligned with QuickBooks
- **Send sales tax**: match your invoice tax rates to QuickBooks' Automated Sales Tax, or include tax in the payment total

## How data synchronization works

Synchronization between TaxDome and QuickBooks runs on demand, not on a schedule:

- **TaxDome to QuickBooks**: sync is triggered the moment an entity is created, updated, or deleted in TaxDome — either by a user action or by a system event
- **QuickBooks to TaxDome**: data is pulled from QuickBooks when TaxDome needs it for a specific request. For example, when you open the invoice form, TaxDome requests the current list of classes and locations from QuickBooks and displays it in the dropdown.

## Access and permissions

Check the required permissions for different actions:

| Action | Permission level |
|--------|------------------|
| Connect/disconnect QuickBooks | Firm owner |
| Update synchronization settings | Firm owner/Admin |
| Sync account manually | Firm owner/Admin |
| Unsync/resync account | Firm owner/Admin |
| Sync invoices/payments manually | Firm owner/Admin |
| Handle the sync errors | Firm owner/Admin |

Ready to start? Then, learn how to set up QuickBooks Online integration.

---
*Source: [QuickBooks integration for billing explained](https://help.taxdome.com/article/173-integration-with-quickbooks) — official TaxDome documentation.*
