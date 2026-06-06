<!-- Source: https://support.cch.com/kb/solution.aspx/sw7305 (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# What are the status codes and their descriptions in the Electronic Filing Status System

When electronically filing a return, the following statuses can display on the Electronic Filing Status System (EFS) website.

## Category: Not Released

- **Ready to Release by Customer.** The return was uploaded and is ready to be released to the IRS or DOL.
- **Upload Failed, please re-process.** The file upload process failed to complete and the return must be re-uploaded.
- **Upload Canceled.** The file upload process has been canceled and the return must be re-uploaded.
- **Upload Started.** The file has been queued for upload to the server. This status should only take a few seconds; if it takes longer, re-upload the return.

## Category: Released

- **Released for Transmission - Validation in Progress.** The return has been released for transmission to the IRS or DOL and is being validated. Later verify if the return receives an Accepted status.
- **Ready to Transmit - Validation Complete.** The return has been released and validated and is in the transmission process to the IRS or DOL.
- **Transmitted.** The return has been transmitted and is awaiting acknowledgments from the IRS or DOL.
- **Holding for Transmission - No Action Required by Customer.** (Individual returns only) The return is being held for legislature extensions or until the time transmission is allowed.

## Category: Not Accepted

### Sub-Category: Rejected

- **Rejected.** The IRS or DOL has rejected the return for processing. See the Viewing the Rejected Returns Report in EFS for more information. Make any necessary corrections, and then recalculate, re-upload, and re-transmit the return.
- **Rejected by Federal, State Not Submitted.** The return was rejected at the federal level with no state level return being submitted.
- **Amendment Required – Timely filed.** The Foreign Bank Account Report (FBAR) has been accepted as timely filed with the Department of the Treasury; however, additional information must be provided by the preparer to the Department of the Treasury within 30 days in order for the return to remain timely filed.

### Sub-Category: Stopped - Action Required

- **Paper Filing Required.** If a return was rejected, you can change the status of the return to Paper Filed from the Change Status window or in the Rejection Report. This section allows you to indicate which taxing authority returns you will paper file.
- **Stopped by Customer.** If you stopped transmission of a return on the Change Status tab, the Stopped by Customer status will display. You may also receive this status for one of the following reasons: if the state record is too large, because of a multi-state extension, a state schema version change, or an incomplete transmission.
- **Stopped for IRS Schema Change.** The return was stopped because IRS pre-defined rules have changed. Recalculate the return on the newest version and re-upload the return.
- **Stopped by Support at Customer Request.** The return was stopped because a client was not able to do so.
- **Stopped: Recalc and Resubmit State-Only.** The return was stopped because of a calculation problem. Recalculate the return and submit it as a state-only record.
- **State Record is too Large, Resend as Federal Only.** Processing was stopped due to the excessive size of the state record. Reprocess only the federal return.
- **Stopped for State Schema Change.** Processing of the return was stopped for a change to the state schema.
- **Stopped: Please Recalculate on Latest Release.** The return was stopped and must be reprocessed on the latest release.
- **Transmission incomplete, please re-process.** Transmission of the return failed to complete. Reprocess the return.
- **Duplicate or Incorrect SSN, Correct and Resubmit.** The return was stopped due to either a duplicate or incorrect social security number. Correct the SSN and resubmit the return.
- **Incorrect EIN, Correct and Resubmit.** The return was stopped due to either a duplicate or incorrect employer identification number. Correct the EIN and resubmit the return.
- **Missing and Incorrect EFIN, Correct and Resubmit.** The return was stopped due to either a duplicate or incorrect EFIN. Correct the number and resubmit the return.
- **Return Canceled - Upload of Updated Return Failed from Tax.** The previous upload of a return was not released and a subsequent attempt to upload the same return has failed.
- **Disqualified or Not Yet Available for Filing.** This return was exported with a state that was disqualified or not approved. Resubmit the state only return when ready to electronically file. This status is also available under category: Paper filed/Not e-filed.
- **EFIN Disallowed for e-filing.** The EFIN utilized has not been provided to Wolters Kluwer, has been deleted, is marked inactive, or a VCN has not been created.
- **EFIN Mismatch with VCN on File.** The EFIN utilized is missing, does not match the EFIN in EFIN Manager, or does not match the provided VCN.

### Sub-Category: Stopped - CCH Reviewing

- **Stopped for CCH review.** The return is being reviewed by Wolters Kluwer. After you receive the review notification, re-upload the return.
- **Byte Count Error.** The return was stopped for review by Wolters Kluwer because of an incorrect byte count. Recalculate, re-upload, and re-transmit the return.
- **Blank Form Error, PDF Error, Schema Validation Error, Missing State Information, Missing or Incorrect ProSystem fx Account Number, Previous Upload in Process.**

## Category: Accepted

- **Accepted.** The return has been accepted by the IRS or DOL for processing.
- **Conditional Acceptance.** (Individual returns; certain states) When a state issues a conditional acceptance, it allows the state additional time to do further processing to determine if additional information is required. The state will sometimes send letters or notifications to ask taxpayers for additional information. Once that additional information is supplied on paper by the preparer/taxpayer, the state is able to officially accept the return and issue a new acceptance acknowledgment.
- **State Notification - Additional Info Required.** (Individual returns; certain states) For states that issue a notification of missing information, such as Forms W-2, 1099 and 8453, the return will not be processed by the state until the missing information is received.
- **Imperfect Return - Fix for Next Year.** (Individual returns) The IRS will accept a previously rejected return that has been rejected for Reject Code 501 or 504 (rejections for the dependent Social Security Number) if the General > Electronic Filing worksheet is marked. This alerts the IRS when they are processing the return the second time that the taxpayer knows the SSN is incorrect, but wants to file electronically anyway. The IRS will accept these returns, but they will display a status code of Imperfect Return. These returns will go through additional checks at the IRS and the IRS may disallow the EIC credit or dependent exemption for the dependent whose SSN is in question. Returns with this status will take additional processing time with the IRS, causing the refund for the taxpayer to be delayed up to four to six weeks.
- **Return Delivery Receipt.** For certain Michigan and Ohio cities, a receipt of delivery of the return to the city is received. This is not an official e-file acknowledgment. An alert will be provided, containing a link to contact information for obtaining an official city acknowledgment. For additional information, refer to the following articles:
  - Contact information for Michigan cities
  - Contact information for Ohio cities

## Category: Paper Filed/Not e-Filed

- **Paper Filed by Customer.** The return must be paper filed. This status will prevent seeing previous rejections.
- **Status Set to Paper Filed, as Customer Request.** The return had its status set to paper filing per the customer's request. This status will prevent seeing previous rejections.
- **Extension Stopped - Return Already Accepted.** The return has been accepted, but the extension has not been sent.
- **Return Canceled at Customer Request.** The return has been canceled by Wolters Kluwer at the customer's request and the return will not be uploaded to the server.
- **Disqualified or Not Yet Available for Filing.** The return was exported with a state that was disqualified or not approved. Resubmit the state only return when ready to electronically file. This status is also available under category: Not Accepted > Stopped - Action Required.

---
*Source: [What are the status codes and their descriptions in the Electronic Filing Status System](https://support.cch.com/kb/solution.aspx/sw7305) — official CCH (Wolters Kluwer) support documentation.*
