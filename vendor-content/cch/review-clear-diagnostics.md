<!-- Source: https://support.cch.com/kb/solution/How-do-I-review-clear-and-sign-off-on-diagnostics-in-CCH-Axcess-Tax-and-CCH-ProSystem-fx-Tax (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I review, clear, and sign off on diagnostics in CCH Axcess Tax and ProSystem fx

The video below explains how to view a return's diagnostics, what they mean, if they require action, and helpful hints on how to clear and resolve them.

## Reviewing Diagnostics

Diagnostics display information about invalid or missing return data that can affect whether a return will be accepted by the tax authority when filed. Diagnostics can be informational, or they can prevent the return from being electronically filed. To view the most up-to-date diagnostics for a return, calculate the return on the newest version of the Tax program that is available.

To review a return's diagnostics, do the following:

- **CCH Axcess Tax.** Click on the Quick Access Toolbar or click the Review tab on the ribbon, and then click **Diagnostics**.
- **CCH ProSystem fx Tax.** Click on the toolbar, or click **Review > Interactive Diagnostics**.

Each diagnostic lists the form, schedule, section, line, or box causing the diagnostic. The diagnostic typically gives an explanation of what has caused the diagnostic to be issued, and points you in a direction of what data to check or enter in the return. At the end of the diagnostic text, a diagnostic code is given. The first digit of this code is dependent on the type of diagnostic that has been issued. You can also use these codes to search our Knowledge Base for additional information about the diagnostic.

Diagnostics are organized in the following categories and are listed in the Diagnostics report in the following order:

| Diagnostic Type | Code Starts with | Action Required | Disqualifies for Electronic Filing | Additional Information |
| --- | --- | --- | --- | --- |
| Electronic Filing Diagnostics | 6 | Must be cleared to file federal or state forms. | Yes | Main federal and state forms |
| | 5 | Diagnostics must be cleared to file secondary forms or extensions. | Yes | Secondary or extension forms<br><br>Example: Form 114, NY 204-LL |
| | 4 | Diagnostics must be cleared. | Yes | Main federal and state forms |
| Warning Diagnostics | 1 | Diagnostics should be cleared. | No, but typically causes electronic filing diagnostics. | |
| Cautionary Diagnostics | 2 | Review | No | |
| Informational Diagnostics | 3 | Review | No | Some informational diagnostics cannot be cleared. |

## Clearing Diagnostics

Some diagnostics are interactive. Interactive diagnostics have a symbol next to them showing that they are interactive.

- **CCH Axcess Tax.** Interactive diagnostics have a next to the diagnostic.
- **CCH ProSystem fx Tax.** Interactive diagnostics have a > symbol next to the diagnostic.

Clicking on the interactive diagnostic link takes you to the specific input location that is causing the diagnostic. After editing the return to clear the diagnostic, recalculate the return, and then view the return's diagnostics again.

### Helpful Tips and Tricks to Clear Diagnostics

- Calculate the return on the latest version of the Tax program.
- Use the diagnostic text as instructions to clear the diagnostic.
- Search our Knowledge Base for the diagnostic code if you need additional information. We continually add new diagnostics information to the Knowledge Base along with updating existing articles with new information.
- After editing the return to clear the diagnostic, recalculate it.

## Signing-Off Diagnostics

Diagnostics have a status of Open or Signed-off. You can sign-off diagnostics that you do not want to show in the Open view. This allows you to focus on diagnostics that may require further input. Select All, Open, or Signed off at the top of the report to change the view, if needed.

Select Sign-off below non-severe diagnostics and diagnostics that are not related to electronic filing input or extension/FBAR disqualification. Your user ID, the current date, and current time display next to the Sign-off field and the diagnostic is removed from the Open view.

### Notes

- You can also clear the Sign-off field to return a diagnostic to the Open status. This removes the user ID and date associated with the sign-off and shows the diagnostic in the Open view.
- The Signed-off state is assigned to the diagnostic for the open return and will remain signed-off unless it is cleared. The diagnostic will show as signed-off for other staff working in the return.
- You can set the default to print only open diagnostics in User Options > Tax > Print Options and in Return Configuration Sets > Print Options.
- The checkbox to sign-off on diagnostics will not be available if return is locked.

---
*Source: [How do I review, clear, and sign off on diagnostics in CCH Axcess Tax and ProSystem fx](https://support.cch.com/kb/solution/How-do-I-review-clear-and-sign-off-on-diagnostics-in-CCH-Axcess-Tax-and-CCH-ProSystem-fx-Tax) — official CCH (Wolters Kluwer) support documentation.*
