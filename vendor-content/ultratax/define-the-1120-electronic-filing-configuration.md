<!-- Source: https://www.thomsonreuters.com/en-us/help/ultratax-cs/e-file/define-the-1120-electronic-filing-configuration (official UltraTax help page, mirrored 2026-06-06 for KB ingestion) -->

# Define the 1120 electronic filing configuration

To configure UltraTax CS to file 1120 returns electronically, you'll first need to set options for all clients in the **Setup**, **Office Configuration**, then the **E-Filing** tab. The options you set in this tab apply to all clients and include options for Electronic Filing Identification Numbers (EFINs), state electronic files, and alternate Electronic Return Originator (ERO) information.

The 1st time you open UltraTax CS, you'll need to enter your EFIN and ERO information for UltraTax CS/1120.

The following steps help you do the following:

- Determine whether you'll file all returns using a single EFIN or several EFINs.
- Determine suppression options for the creation of state returns.
- Enter ERO information if you want to use alternate information for the ERO instead of the licensed firm information.
- Set print options for the facsimile of Form 9325.
- Set options to file the return electronically.
- Set email notification options.

## Steps

1. Select **Setup**, then **Office Configuration**.

   > Note: Depending on your security configuration, you may need to enter the master password before you can open the Office Configuration window. The master password is specified in **Setup**, then **Security**.

2. Select the **E-Filing** tab.

3. Select 1 of the following options in the EFIN (Electronic Filing Identification Number) section.

   - If you're filing electronic returns using only 1 EFIN, select **All returns in this office will file using EFIN** and enter the 6-digit, IRS-assigned EFIN in the field.

   - If you're using different EFINs, select **Several EFINs are being used**. After you select this option, you'll need to assign EFINs to each preparer in the Preparers tab. To do so, select the **Preparers** tab, select **Add** or **Edit** for each preparer, enter the EFIN in the **Preparer EFIN** field, then select **OK** to save the information.

   > Important: For UltraTax CS to assign this EFIN in the electronic file for each client properly, you'll need to select the preparer from the **Preparer** field in the **File**, then **Client Properties** window before you mark the **File this return electronically** field in the ELF screen.

4. Select **States**. If you haven't received the necessary approval from a state, or if you want to suppress the creation of all electronic files for a given state, clear the checkbox next to the state.

   > Note: The options set in this window affect electronic returns for all entities. UltraTax CS gives several options for suppressing state electronic returns.

5. Select **Done** to close the States window.

6. Select **ERO** to open the Electronic Return Originator (ERO) window. UltraTax CS uses the licensed firm information as the default for the ERO information. To enter alternate information for the ERO rather than use the licensed firm information, select **Use alternate ERO information** in the Electronic Return Originator (ERO) information to Electronic Filing Signature Form section, then complete all of the fields for the alternate ERO.

7. Select **Done** to close the Electronic Return Originator (ERO) window.

8. Select **Done** to close the Office Configuration window.

9. Select **Setup**, then **1120 Corporation**.

10. Select **Other Return Options**. UltraTax CS automatically proformas the **File this return electronically** checkbox to the current-year's return for clients for whom you filed electronic returns last year. If you don't want this checkbox proforma'd, clear the **File the return electronically (Screen ELF)** checkbox in the **Proforma** tab of the Other Return Options window. You'll then need to mark the **File this return electronically** checkbox in the ELF screen for each client you want to file electronically.

11. To mark the **File this return electronically** checkbox automatically for proforma'd clients on the 1st time in the client, mark the **File the return electronically if not marked for e-file in the prior year (Screen ELF)** checkbox in the **Other** tab.

12. In accordance with the IRS form design, the taxpayer's address is right-aligned when the facsimile of Form 9325 prints. To have the taxpayer's address print left-aligned on the facsimile of Form 9325, mark the **Print Form 9325 taxpayer mailing address left-justified** checkbox in the Other section of the **Return Presentation** tab.

13. Select **OK** to close the Other Return Options window.

14. Select **New Client Options**. Mark the **File the return electronically (Screen ELF)** checkbox in the Other section to mark the **File this return electronically** checkbox automatically in the ELF screen for new clients. If you don't want this checkbox marked automatically, clear the **File the return electronically (Screen ELF)** checkbox. You'll then need to mark the **File this return electronically** checkbox in the ELF screen for each client you want to file electronically.

15. Select **OK** to close the New Client Options window.

## Additional Information

- Thomson Reuters can send the client an email notification on your behalf when the federal and state returns and extensions are accepted. You'll need to select this option in the client's return before creating the electronic file.

- The steps to complete your electronic filing configuration vary depending on whether you're using CS Connect or a 3rd-party application vendor to transmit the returns.

  - If you use CS Connect, your electronic filing configuration is complete. Select **OK** to close the 1120 Product Information window and enter data for the return.

  - If you're licensed to file electronically using both the Electronic Filing tool and a 3rd-party application vendor, you'll need to set related user preference options in UltraTax CS.

---
*Source: [Define the 1120 electronic filing configuration](https://www.thomsonreuters.com/en-us/help/ultratax-cs/e-file/define-the-1120-electronic-filing-configuration) — official UltraTax documentation.*
