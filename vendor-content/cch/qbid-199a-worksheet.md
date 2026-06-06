<!-- Source: https://support.cch.com/kb/solution/000177648 (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I prepare the QBID (199A) worksheet using worksheet view

How do I prepare the QBID (199A) worksheet in a 1040, 1041, 1065, 1120, or 1120S return using worksheet view in CCH Axcess™ Tax and CCH® ProSystem fx® Tax?

## Objectives

Learn how to prepare the QBID (199A) worksheet in a 1040, 1041, 1065, 1120, or 1120S return using worksheet view in CCH Axcess™ Tax and CCH® ProSystem fx® Tax.

## Environment

- CCH Axcess Tax
- CCH ProSystem fx Tax
- 1040
- 1041
- 1065
- 1120
- 1120S
- Worksheet

## Procedure

The following inputs will generate the QBID (199A) worksheets. The first worksheet listed in the grids, per product, are the return level overrides. The worksheets following are the activity level entries.

| Return Type | Worksheet | Section(s) |
| --- | --- | --- |
| 1040 | Deductions > 8995/8995-A - Qualified Business Income (Section 199A) | 1 - General<br>2 - Total Overrides and Other Information |
| | Income > Schedule C - Business | 15 - Qualified Business Income |
| | Income > Sch E, p 1 - Rent and Royalty | 17 - Qualified Business Income |
| | Income > Sch E, p 2 - Fiduciary Passthrough (K-1 1041) | 4 - Qualified Business Income |
| | Income > Sch E, p 2 - Partnership Passthrough (K-1 1065) | 5 - Qualified Business Income |
| | Income > Sch E, p 2 - S Corporation Passthrough (K-1 1120S) | 5 - Qualified Business Income |
| | Income Sch F / 4835 - Farm | 12 - Qualified Business Income |
| 1041 | Deductions > 8995/8995-A - Qualified Business Income (Section 199A) | 1 - General<br>2 - Total Overrides and Other Information |
| | Income > Schedule C - Business | 14 - Qualified Business Income |
| | Income > Sch E, p 1 - Rent and Royalty | 14 - Qualified Business Income |
| | Income > Sch E, p 2 - Fiduciary Passthrough (K-1 1041) | 4 - Qualified Business Income |
| | Income > Sch E, p 2 - Partnership Passthrough (K-1 1065) | 5 - Qualified Business Income |
| | Income > Sch E, p 2 - S Corporation Passthrough (K-1 1120S) | 5 - Qualified Business Income |
| | Income Sch F / 4835 - Farm | 9 - Qualified Business Income |
| 1065 | Income / Deductions > Section 199A - Qualified Business Income | 1 - General<br>2 - Total Overrides and Other Information |
| | Income / Deductions > Business | 13 - Qualified Business Income |
| | Income / Deductions > Rent and Royalty | 6 - Qualified Business Income |
| | Income / Deductions > Depletion | 6 - Qualified Business Income |
| | Income / Deductions > Sch F/4835 - Farm | 5 - Qualified Business Income |
| | Income / Deductions > Fiduciary Passthrough (K-1 1041) | 6 - Qualified Business Income |
| | Income > Partnership Passthrough (K-1 1065) | 7 - Qualified Business Income |
| 1120 | Income / Deductions > Qualified Business Income (Section 199A) | 1 - General<br>2 - Total Overrides and Other Information |
| | Income / Deductions > Business | 14 - Qualified Business Income |
| | Income / Deductions > Farm / 4835 - Farm and Farm Rental | 8 - Qualified Business Income |
| | Income / Deductions > Rent and Royalty | 8 - Qualified Business Income |
| | Income / Deductions > Fiduciary Passthrough (K-1 1041) | 9 - Passthrough Section 199A |
| | Income / Deductions > Partnership Passthrough (K-1 1065) | 10 - Passthrough Section 199A |
| | Income / Deductions > Depletion | 5 - Qualified Business Income |
| 1120S | Income / Deductions > Qualified Business Income (Section 199A) | 1 - General<br>2 - Total Overrides and Other Information |
| | Income / Deductions > Business | 12 - Qualified Business Income |
| | Income / Deductions > Farm / 4835 - Farm and Farm Rental | 8 - Qualified Business Income |
| | Income / Deductions > 8825 / Other - Rent and Royalty | 9 - Qualified Business Income |
| | Income / Deductions > Fiduciary Passthrough (K-1 1041) | 8 - Passthrough Section 199A |
| | Income / Deductions > Partnership Passthrough (K-1 1065) | 9 - Passthrough Section 199A |
| | Income / Deductions > Depletion | 5 - Qualified Business Income |

### Notes

- An entry in the Qualified option in the Qualified Business Income section of the worksheets is mandatory to include that activity, using it's entity type and it's entity number in the calculation.
- For return types 1065, 1120, and 1120S, an entry for the Code to print QBI schedule is used to produce the 199A output worksheet(s) by labeling an income producing activity/entity as Qualified Business or Qualified Service activity. It is assumed that the return already has complete entries for business, rental, farm, depletion, and/or passthrough K-1s received for the QBID (199A) worksheet(s) to calculate.

---
*Source: [How do I prepare the QBID (199A) worksheet using worksheet view](https://support.cch.com/kb/solution/000177648) — official CCH (Wolters Kluwer) support documentation.*
