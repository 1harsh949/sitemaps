<!-- Source: https://support.cch.com/kb/solution.aspx/sw44769 (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I turn electronic filing on or off for a return in CCH Axcess Tax

Electronic Filing can be enabled or disabled at a return configuration set level or on a return-by-return basis. Enabling electronic filing generates electronic filing diagnostics to help you qualify the tax return for electronic filing. Once the return is qualified, you can export it for electronic filing.

- For more information, go to our article on configuring electronic filing at the return configuration set level in Dashboard.

Many of the settings that you configure in Dashboard for electronic filing can also be configured in a single return. To turn electronic filing on or off in a tax return, do the following:

1. Open a return.
2. Go to the General > Electronic Filing worksheet.
3. Click the corresponding section shown in the table below for the return type that you are editing.
4. In Line 1, select Yes to enable electronic filing or No to disable it.
5. Calculate the return.

The table below shows the tax products, worksheets, sections, and line numbers where you can turn electronic filing on or off in the return. Entries in these lines override the corresponding entries in the return configuration set.

| Tax Product | Worksheet | Section | Line 1 |
| --- | --- | --- | --- |
| Corporation - 1120 | General > Electronic Filing | General | Electronically file |
| Employee Benefit Plan - 5500 | General > Electronic Filing | Electronic Filing | Electronic filing |
| Exempt Organization - 990 | General > Electronic Filing | General | Electronically file |
| Fiduciary - 1041 | General > Electronic Filing | General | Electronically file |
| Individual - 1040 | General > Electronic Filing | General | Electronically file |
| Partnership - 1065 | General > Electronic Filing | General | Electronically file |
| S Corporation - 1120S | General > Electronic Filing | General | Electronically file return |

If you select Yes to enable electronic filing, diagnostics tell you if the return is qualified for electronic filing. Diagnostics explain the reasons for disqualification and resolutions for qualification. To view diagnostics, do the following:

1. Click Diagnostics in the Reports group on the Review ribbon.
2. Review and correct disqualifying diagnostics in the Electronic Filing Diagnostics section.
3. Calculate the return.
4. Click Diagnostics on the ribbon again to verify that all electronic filing diagnostics are cleared and that the return is qualified for electronic filing.

**Notes:**

- We recommend clearing all diagnostics in the Warning Diagnostics section before filing the return.
- If you are electronically filing a consolidated return, all returns in the return group must qualify.

---
*Source: [How do I turn electronic filing on or off for a return in CCH Axcess Tax](https://support.cch.com/kb/solution.aspx/sw44769) — official CCH (Wolters Kluwer) support documentation.*
