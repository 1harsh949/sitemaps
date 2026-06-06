<!-- Source: https://support.cch.com/kb/solution/How-do-I-enter-Section-754-depreciation-and-amortization-in-a-1065-return-using-worksheet-view-in-CCH-Axcess-Tax-and-CCH-ProSystem-fx-Tax (official CCH Wolters Kluwer support article, rendered + mirrored 2026-06-06 for KB ingestion; source site is reCAPTCHA-gated and not directly crawlable) -->

# How do I enter Section 754 depreciation and amortization in a 1065 return using worksheet view

Section 754 depreciation and amortization can be entered using the following methods:

- Method 1: Detail Depreciation Input
- Method 2: Totals Depreciation Input
- Method 3: Totals Override Input

## Method 1: Detail Depreciation Input

1. Go to the **Income/Deductions > [Entity/Activity]** worksheet.
   - Select the section for **Depreciation and Amortization**.
   - Click **Detail** located in the upper left corner of the grid.
   - Select **Section 1 - General**.
   - In **Line 55 - Ratio ID for Special allocation or 754 - 1065 ONLY**, enter a unique ratio ID.
2. Go to the **Special Allocations > Special Allocations** worksheet.
   - Select **Section 3 - Ratio Allocation**.
   - In **Line 1 - Ratio ID number**, enter the same ratio ID number as entered in Line 55 above.
   - In **Line 11 - Ratio Allocation** (grid), enter the following:
     - In **Partner Number** (column), enter the partner number.
     - In **Ratio 1** (column), enter the amount or percentage to be allocated.
3. Calculate the return.

## Method 2: Total Depreciation Input

1. Go to the **Income/Deductions > [Entity/Activity]** worksheet.
   - Select the section for **Depreciation and Amortization**.
   - Click **Totals** (tab) located at the top of the section next to the section name.
   - Select **Section 5 - Tax Adjustment and Preference Items**.
   - In **Line 4 - Section 754 depreciation - 1065 only**, enter amount.

   **Note:** Repeat this step for additional business entities / activities.
2. Go to the **Special Allocations > Special Allocations** worksheet.
   - Select **Section 2 - Special Allocation Detail**.
   - In **Line 1 - Code Lookup - Federal**, use the drop-down to select the applicable code.
     - Code 5207 - 13zz: Section 754 depreciation - Trade or Business
     - Code 7609 - 13zz: Section 754 depreciation attached to Trade or Business activity
     - Code 7603 - 13zz: Section 754 depreciation attached to Rental Real Estate activity
     - Code 7605 - 13zz: Section 754 depreciation attached to Other Rental activity
     - Code 7607 - 13zz: Section 754 depreciation attached to Portfolio
     - Code 5213 - 13zz: Section 754 amortization
   - In **Line 4 - Special Allocation Detail** grid, enter the following:
     - In **Partner Number** (column), enter the partner number.
     - In **Allocation** (column), enter the amount or percent to be allocated.
3. Calculate the return.

## Method 3: Totals Override Input

**Note:** Using this method will override all other 754 depreciation for each income property activity.

- For Trade or Business activities, do the following:
  1. Go to the **Income/Deductions > Business** worksheet.
     - Select **Section 7 - Deductions**.
     - In **Line 10 - Depreciation - Section 754 - override**, enter the total amount for business property.

     Repeat this step for any additional business entities and activities.
  2. Calculate the return.

- For Rent or Royalty activities, do the following:
  1. Go to **Income/Deductions > Rent and Royalty** worksheet.
     - Select **Section 3 - Expenses**.
     - In **Line 14 - Depreciation - Section 754 - override**, enter the total for this Rental property.
  2. Calculate the return.

- For Schedule K activities, do the following:
  1. Go to the **Income/Deductions > Schedule K - Other Income/Deductions** worksheet.
     - Select **Section 3 - Schedule K - Other Deductions**.
     - Click **Detail** located in the upper left corner of the grid.
     - In **Line 1 - Description**, enter the description.
     - In **Line 3 - Amount**, enter the amount.
     - To allocate the Section 754 amount, do one of the following:
       - To allocate using Partner Numbers, in **Line 4 - Partner Number**, enter the partner number. Or,
       - To allocate using a Ratio ID number, in **Line 5 - Ratio ID**, enter a unique ratio ID number.
  2. Go to the **Special Allocations > Special Allocations** worksheet.
     - Select **Section 3 - Ratio Allocation**.
     - In **Line 1 - Ratio ID number**, enter the same ratio ID number as entered in Line 5.
     - In **Line 11 - Ratio Allocation** grid, enter the following:
       - In **Partner Number** (column), enter the partner number.
       - In **Ratio 1** (column), enter the amount or percentage to be allocated.
  3. Calculate the return.

---
*Source: [How do I enter Section 754 depreciation and amortization in a 1065 return using worksheet view](https://support.cch.com/kb/solution/How-do-I-enter-Section-754-depreciation-and-amortization-in-a-1065-return-using-worksheet-view-in-CCH-Axcess-Tax-and-CCH-ProSystem-fx-Tax) — official CCH (Wolters Kluwer) support documentation.*
