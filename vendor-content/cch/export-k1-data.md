<!-- Source: https://support.cch.com/kb/solution/000038583 (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I export K-1 data from a business return to another return

How do I export K-1 data from a business return to another return using worksheet view in CCH Axcess™ Tax or CCH® ProSystem fx® Tax?

The export process is completed using three steps:

- Step 1: Setup The Export In The Source Return
- Step 2: Export The Data
- Step 3: Open The Target Return

**Note:** If the source return is passing multiple activity information to the target return, use the Other > Export translation of activity numbers worksheet to maintain the multiple activity status in the export file. Enter the source return activity number, the partner/shareholder/beneficiary number, and the partner's/shareholder/beneficiaries' target return activity number.

**\*\*\*NOTE - IF THE RETURNS ARE PASSWORD PROTECTED, THEY WILL NOT EXPORT OR IMPORT THE K-1S. YOU MUST REMOVE THE PASSWORD BEFORE EXPORTING/IMPORTING.**

## Step 1: Setup The Export In The Source Return

Based on the return type, do one of the following:

### For a Partnership 1065 Return

- Go to the General > Return Options worksheet.
- Select Section 7 - Export Options.
  - In Lines 1-3 - Export Options, enter the applicable export information.
- Go to the Partners > Partner Information worksheet.
- Click Detail.
- Select Section 6 - Export Partner Information to 1040 / 1041 / 1065 / 1120 / 1120S.
  - In Lines 1-4 - Export Partner Information to 1040 / 1041 / 1065 / 1120 / 1120S, enter the applicable export information.
- Calculate the return.

### For an S Corporation 1120S Return

- Go to the General > Return Options worksheet.
- Select Section 7 - Export Options.
  - In Lines 1-3 - Export Options, enter the applicable export information.
- Go to the Shareholders > Shareholders Information worksheet.
- Click Detail.
- Select Section 4 - K-1 Export Options.
  - In Lines 1-4 - K-1 Export Options, enter the applicable export information.
- Calculate the return.

### For a Fiduciary 1041 Return

- Go to the Beneficiaries > All Beneficiary or Grantor Options worksheet.
- Select Section 1 - All Beneficiary or Grantor Options.
  - In Lines 12-13 - Export options, enter the applicable export information.
- Go to the Beneficiaries > Beneficiary Information worksheet.
- Click Detail.
- Select Section 3 - Export Beneficiary Information to 1040 / 1041 / 1065 / 1120 / 1120S.
  - In Lines 1-5 - Export Beneficiary Information to 1040 / 1041 / 1065 / 1120 / 1120S, enter the applicable export information.
- Calculate the return.

**Note:** Grantor trusts are not able to use this option as Form K-1 is not generated.

## Step 2: Export The Data

### Option 1: Manually Create the K-1 Export File.

- For CCH Axcess™ Tax.
  - On the Ribbon, Go to Import / Export tab.
  - In the Export section, Click K-1 Data > K-1 Data to Other Returns.
- For CCH® ProSystem fx® Tax.
  - On the Menu Bar, Go to File > Export > K-1 Data to Other Returns.

### Option 2: Create the K-1 Export File During Calculation.

- Go to the General > Return Options worksheet.
- Select Section 7 - Export Options.
  - In Line 2 - Create Schedule K-1 export files during calculation, use the lookup value (double click or press F4) to select Yes.
- Calculate the return.

**Note:** This option is only available for Partnership 1065 and S Corporation 1120S returns.

## Step 3: Open The Target Return

Once the export files have been created, open the target return to begin the import process.

- On the Import K-1 Files into the return window, select items in the Import files pane and click Add.
- Once all the desired import files are added to the Files selected for import pane, click OK.
- On the K-1 Import File Log window, review the log to verify the K-1s imported and see any import errors.
- Click Print or Close to exit the log report.

## Additional Information

- For steps on how to export K-1 data in Interview, see our solution: How do I export K-1 data from a business return to another return using interview forms in CCH® ProSystem fx® Tax?

---
*Source: [How do I export K-1 data from a business return to another return](https://support.cch.com/kb/solution/000038583) — official CCH (Wolters Kluwer) support documentation.*
