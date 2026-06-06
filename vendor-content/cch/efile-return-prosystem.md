<!-- Source: https://support.cch.com/kb/solution/sw7803 (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I electronically file a return using CCH ProSystem fx Tax

- Check the return's diagnostics and make sure that it is qualified to be electronically filed.
  - Troubleshooting diagnostics in CCH Axcess Tax and CCH ProSystem fx Tax.

- Click **File > Export > Electronic Filing > Return**.
  - Select returns (Federal and/or State) for export, and then click **Export**.

- Choose your print options and click **OK**.
  - Export to electronic filing only
  - Export to electronic filing and print

- In the **Upload Returns** window, select the appropriate upload option.
  - **Upload and hold**. Uploads the return to the Electronic Filing Status site, but does not release it to the taxing authority.
  - **Upload and release to tax authority**. Uploads the return to the Electronic Filing Status site and releases it to the taxing authority.
    - Users do not have this right by default. This right can be given to users in **Office Manager > Configure Staff**.

- Click **Start** to upload the return.

- When the return has been uploaded, "Upload Successful" will appear.

- If you selected to **Upload and hold**, use the Electronic Filing Status site to release the return to the taxing authority.
  - Click here for instructions on how to release returns to the taxing authority from the Electronic Filing Status.

## Notes

- If a return has hard override entries (pink numbers on the Government Forms), the return will be disqualified for electronic filing.
- Before exporting a return, clear all diagnostics. If filing an extension, go to Interview Form **EF-1 - Electronic Filing**, box **32 - Electronically file extension**, and enter **Y**.
- If the return is a Consolidated return, on Interview Form **1 - Basic Data**, box **90 - Code for consolidated return**, only one return can have a **C** and one with a **P**. All others should be marked **S**.
- If it is a stand-alone state return that was part of a consolidated for federal purposes, Interview Form **1 - Basic Data**, boxes **90 - 92** must be blank.

---
*Source: [How do I electronically file a return using CCH ProSystem fx Tax](https://support.cch.com/kb/solution/sw7803) — official CCH (Wolters Kluwer) support documentation.*
