<!-- Source: https://www.thomsonreuters.com/en-us/help/ultratax-cs/e-file/fix-efile-errors (official UltraTax help page, mirrored 2026-06-06 for KB ingestion) -->

# Fix electronic file errors

Follow these steps to correct errors in an electronic file.

> **Note:** If you use a third-party vendor for transmission, check their error report and instruction guide first.

1. Check if UltraTax CS detected the errors or if the taxing authority rejected the return.
   - Review error details for UltraTax CS errors: Select **Print Report** in the **E-File Error Report** window. Review the error details. Select **OK**.

     > **Note:** You'll need to fix all errors before UltraTax CS will create the electronic file.
   - For taxing authority rejections: Check the reject codes/business rules. Review your acknowledgment message.
2. In UltraTax CS, correct the errors via the input screens.
3. Recreate the electronic file.
4. If errors persist or the authority rejects the file again, repeat steps 1-3.

> **Important:** The IRS requires specific name control fields for various forms. UltraTax CS calculates these automatically, but you may need to:
>
> - Verify names in the input screens.
> - Override name controls if the IRS database shows different values.
> - Pay special attention to partnership, trust, or corporation names.

> **Tip:** The IRS doesn't accept electronically filed returns under certain conditions. UltraTax CS and other error-checking tools incorporate these guidelines to ensure that UltraTax CS creates electronic files that the IRS accepts. For detailed guidelines, consult:
>
> - **1040**: [IRS Publication 1345, Handbook for Authorized IRS e-file Providers of Individual Income Tax Returns](http://www.irs.gov/pub/irs-pdf/p1345.pdf)
> - **1120, 1065, 1041, 990, and 2290**: [IRS Publication 4163, Modernized e-File Information for Authorized IRS e-file Providers for Business Returns](http://www.irs.gov/pub/irs-pdf/p4163.pdf) and [IRS Publication 4164, Modernized e-File Guide for Software Developers and Transmitters](http://www.irs.gov/pub/irs-pdf/p4164.pdf)
> - **5500**: Refer to [efast.dol.gov](http://www.efast.dol.gov/) for more information.

## This article applies to:

- Product: UltraTax CS
- Return type: 1040 Individual, 1120 Corporation, 1065 Partnership, 1041 Fiduciary, 990 Exempt Organization, 5500 Beneficiary Plan, 2290 Heavy Vehicle Use Tax
- Subject: e-file

---
*Source: [Fix electronic file errors](https://www.thomsonreuters.com/en-us/help/ultratax-cs/e-file/fix-efile-errors) — official UltraTax documentation.*
