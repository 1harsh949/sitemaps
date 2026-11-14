# Sitemap cleanup, 2026-11

Branch `cleanup/dupes-and-dead-2026-11`. Not merged; needs owner review. CustomGPT will drop removed pages on its next crawl after merge.

## Totals
- Entries before: 7328 across 62 XML files (6332 unique URLs)
- In-file exact duplicates removed: 122
- Confirmed-dead entries removed (404/410 on both attempts): 873 entries (870 unique URLs)
- Inconclusive entries kept: 2175 (counted per file, after dedupe)
- Entries after: 6333
- Cross-file duplicates (same URL in 2+ files): 756 unique URLs; left in place by design.

## Coverage gap: Cornell not checked
All 936 www.law.cornell.edu URLs were NOT checked. Connections to that host hang (SYN_SENT, host appears to block this machine), so they are recorded as SKIPPED and kept. They may contain dead links; re-check from another network.

## Method
1. Exact duplicates: within each file, `<loc>` compared after html-unescaping and trimming; first occurrence kept. Other formatting untouched.
2. Dead links: every unique URL checked once (concurrency 8, 15s timeout, browser User-Agent). HEAD first, GET fallback on any non-200. Non-200 results were retried once after 5s. A URL was removed only if both attempts returned 404 or 410.
3. Inconclusive (kept): 403 (397 URLs), 429 (281), connection/timeout errors (63), 302/308 final redirects (26), 401 (3), Cornell skipped (936). Soft-404s were not checked.
4. All 62 XML files pass `xmllint --noout`.
5. Note: a bug in a helper copy of the checker initially returned no result for 202 URLs; those were re-run with the same logic before any removal.

Removed URLs with reasons and status codes: `CLEANUP-2026-11-removed.tsv`.

## Per-file counts
| File | Before | Dupes removed | Dead removed | Inconclusive kept | After |
|---|---|---|---|---|---|
| added from audit 0424026 Alabama.xml | 42 | 0 | 10 | 0 | 32 |
| added from audit 0424026 Alaska.xml | 44 | 0 | 10 | 3 | 34 |
| added from audit 0424026 Arizona.xml | 95 | 0 | 44 | 1 | 51 |
| added from audit 0424026 Arkansas.xml | 28 | 0 | 2 | 0 | 26 |
| added from audit 0424026 California.xml | 335 | 6 | 85 | 39 | 244 |
| added from audit 0424026 Colorado.xml | 69 | 0 | 0 | 69 | 69 |
| added from audit 0424026 Connecticut.xml | 55 | 0 | 0 | 0 | 55 |
| added from audit 0424026 Delaware.xml | 68 | 0 | 10 | 0 | 58 |
| added from audit 0424026 District of Columbia.xml | 64 | 0 | 33 | 10 | 31 |
| added from audit 0424026 Florida.xml | 68 | 0 | 21 | 2 | 47 |
| added from audit 0424026 Georgia.xml | 52 | 0 | 17 | 0 | 35 |
| added from audit 0424026 Hawaii.xml | 48 | 0 | 0 | 47 | 48 |
| added from audit 0424026 IRS.xml | 1484 | 18 | 15 | 438 | 1451 |
| added from audit 0424026 Idaho.xml | 47 | 0 | 8 | 0 | 39 |
| added from audit 0424026 Illinois.xml | 91 | 0 | 35 | 0 | 56 |
| added from audit 0424026 Indiana.xml | 62 | 0 | 0 | 4 | 62 |
| added from audit 0424026 Iowa.xml | 49 | 0 | 27 | 1 | 22 |
| added from audit 0424026 Kansas.xml | 36 | 0 | 0 | 0 | 36 |
| added from audit 0424026 Kentucky.xml | 53 | 0 | 15 | 1 | 38 |
| added from audit 0424026 Louisiana.xml | 56 | 0 | 10 | 0 | 46 |
| added from audit 0424026 Maine.xml | 29 | 0 | 3 | 0 | 26 |
| added from audit 0424026 Maryland.xml | 55 | 0 | 35 | 0 | 20 |
| added from audit 0424026 Massachusetts.xml | 51 | 0 | 0 | 49 | 51 |
| added from audit 0424026 Michigan.xml | 40 | 0 | 5 | 0 | 35 |
| added from audit 0424026 Minnesota.xml | 61 | 0 | 19 | 1 | 42 |
| added from audit 0424026 Mississippi.xml | 59 | 0 | 16 | 0 | 43 |
| added from audit 0424026 Missouri.xml | 48 | 0 | 13 | 0 | 35 |
| added from audit 0424026 Montana.xml | 33 | 0 | 19 | 2 | 14 |
| added from audit 0424026 Nebraska.xml | 34 | 0 | 14 | 0 | 20 |
| added from audit 0424026 Nevada.xml | 64 | 0 | 0 | 2 | 64 |
| added from audit 0424026 New Hampshire.xml | 49 | 0 | 0 | 47 | 49 |
| added from audit 0424026 New Jersey.xml | 92 | 0 | 11 | 1 | 81 |
| added from audit 0424026 New Mexico.xml | 45 | 0 | 17 | 0 | 28 |
| added from audit 0424026 New York.xml | 177 | 5 | 68 | 9 | 104 |
| added from audit 0424026 North Carolina.xml | 80 | 0 | 24 | 0 | 56 |
| added from audit 0424026 North Dakota.xml | 29 | 0 | 0 | 2 | 29 |
| added from audit 0424026 Ohio.xml | 56 | 0 | 2 | 0 | 54 |
| added from audit 0424026 Oklahoma.xml | 31 | 0 | 3 | 0 | 28 |
| added from audit 0424026 Oregon.xml | 46 | 0 | 17 | 0 | 29 |
| added from audit 0424026 Pennsylvania.xml | 75 | 0 | 1 | 21 | 74 |
| added from audit 0424026 Rhode Island.xml | 34 | 0 | 0 | 31 | 34 |
| added from audit 0424026 Software (Lacerte, UltraTax, ProConnect).xml | 16 | 0 | 0 | 11 | 16 |
| added from audit 0424026 Software CCH.xml | 21 | 0 | 0 | 1 | 21 |
| added from audit 0424026 Software Drake.xml | 41 | 0 | 0 | 0 | 41 |
| added from audit 0424026 Software Lacerte.xml | 36 | 0 | 7 | 0 | 29 |
| added from audit 0424026 Software ProConnect.xml | 27 | 0 | 7 | 0 | 20 |
| added from audit 0424026 Software TaxDome.xml | 22 | 0 | 0 | 4 | 22 |
| added from audit 0424026 Software UltraTax.xml | 34 | 0 | 0 | 0 | 34 |
| added from audit 0424026 South Carolina.xml | 77 | 0 | 26 | 7 | 51 |
| added from audit 0424026 South Dakota.xml | 38 | 0 | 14 | 0 | 24 |
| added from audit 0424026 Tax Law and Court Cases.xml | 1628 | 93 | 8 | 1122 | 1527 |
| added from audit 0424026 Tennessee.xml | 48 | 0 | 3 | 4 | 45 |
| added from audit 0424026 Texas.xml | 92 | 0 | 38 | 0 | 54 |
| added from audit 0424026 Utah.xml | 70 | 0 | 7 | 3 | 63 |
| added from audit 0424026 Vermont.xml | 61 | 0 | 15 | 1 | 46 |
| added from audit 0424026 Virginia.xml | 47 | 0 | 19 | 0 | 28 |
| added from audit 0424026 Washington.xml | 97 | 0 | 27 | 1 | 70 |
| added from audit 0424026 West Virginia.xml | 48 | 0 | 16 | 0 | 32 |
| added from audit 0424026 Wisconsin.xml | 61 | 0 | 42 | 0 | 19 |
| added from audit 0424026 Wyoming.xml | 65 | 0 | 25 | 6 | 40 |
| added from audit 0424026 cross-cutting.xml | 765 | 0 | 10 | 235 | 755 |
| added from audit 0424026 sitemap-index.xml | 0 | 0 | 0 | 0 | 0 |
