<!-- Source: https://www.thomsonreuters.com/en-us/help/ultratax-cs/1041/filing/prepare-electronic-returns (official UltraTax help page, mirrored 2026-06-06 for KB ingestion) -->

# Prepare electronic returns

Do the following to enter data and create electronic files for 1 or multiple clients.

- Enter the client's tax data. Make sure you follow the guidelines for entering data.

- Open the ELF screen in the **Electronic Filing** folder.

- Enter X in the **File this return electronically** field.

  > **Note:** To request an electronic funds withdrawal to pay a balance due for Form 1041, complete the General Information section on the ELF screen in the **Electronic Filing** folder. Enter the bank account information on the Bank screen in the **General** folder.

- If the **Name control: Calculated** field on the ELF screen is blank, enter information in the **Family name for electronic filing name control** field on the 1041 screen, or enter information in the **Name control: Force** field on the ELF screen.

- If you use a Personal Identification Number (PIN) to sign the return instead of Form 8453-FE, enter PIN information in the 2nd section of the ELF screen.

- Select **View**, then **Diagnostics**. Review the diagnostic messages in the Federal Diagnostics window. Select any item displayed in the window to open the corresponding screen to address the diagnostic message. Clear all Critical and ELF Critical diagnostic messages and review the FYI diagnostic messages, then close the Federal Diagnostics window.

- Select **File**, then **Print Returns**.

  > **Note:**
  > - When you create the federal electronic file, UltraTax CS automatically creates the state electronic file, if necessary. UltraTax CS generates a state FYI diagnostic message that indicates a state electronic file was created. You can file a paper return for the state and suppress the creation of the state electronic file.
  > - By default, the government collation includes only the forms needed to submit by the taxing authority when you file an electronic return. To change these collations, select **Setup**, then **1041 Fiduciary** to open the Product information window. Select the **Federal** or state tab, then **Tax Return** to change the print collation for all electronic returns. We strongly recommend using the default collation.

- Mark the **Government copy** and **Create electronic file** checkboxes.

  > **Note:**
  > - To create the return or check the return for electronic filing errors without printing forms, mark only the **Government copy** and **Create electronic file** checkboxes in the Print Returns window.
  > - To check for errors without create the electronic file, select **Check E-File**.
  > - To check for errors and create the electronic file, select **E-File**.
  > - If you use a 3rd-party application vendor to transmit returns, mark the **Create electronic file (for 3rd Party)** checkbox to create the electronic file. UltraTax CS creates the electronic file without checking for errors. The 3rd-party vendor is responsible for checking for errors.

- Select **Options** and mark the necessary federal and state checkboxes.

  > **Note:** If you're creating the FinCEN Form 114, Report of Foreign Bank and Financial Accounts (FBAR), clear the **Federal** and any state checkboxes. Mark the **FinCEN Form 114** checkbox.

- To create electronic files for multiple clients at the same time, select **Clients**, then select the specific clients.

- Select **Preview** to review the return on screen, or select **Print**. When you select **Preview** or **Print**, UltraTax CS checks for errors in the electronic file.

  > **Note:**
  > - Select **Print** or **E-File** in the Print Returns window to create the electronic file. If you select **Print Preview** on the toolbar or select **Preview** in the Print Returns window, UltraTax CS doesn't generate the electronic file.
  > - When UltraTax CS creates electronic files, it automatically deletes any untransmitted electronic files for a client. UltraTax CS notifies you of the returns it will delete. If you want to stop the creation of the new electronic files and keep the existing files, select **Cancel**. Otherwise, select **OK** to delete the untransmitted electronic files and create new files.
  > - If you use a 3rd-party application vendor to transmit 1041 returns, UltraTax CS places the electronic file in the location you specified in the **Setup**, **User Preferences**, **File Locations** tab.

## This article applies to:

- Product: UltraTax CS
- Return type: 1041 Fiduciary

---
*Source: [Prepare electronic returns (1041)](https://www.thomsonreuters.com/en-us/help/ultratax-cs/1041/filing/prepare-electronic-returns) — official UltraTax documentation.*
