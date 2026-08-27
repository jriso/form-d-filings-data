# Form D Filings Data

Parsed SEC Form D filings — US private placements, newest first.
One line is one filing — an opening or a later closing on the same offering —
carrying the capital taken in at that entry rather than a running total.

- **Source:** SEC EDGAR Form D structured data (public domain)
- **Coverage:** complete through 2026-06-30; this page holds the most recent
  11,037 entries (from 2025-03-01) of 156,258 in the full dataset
- **Built from:** quarterly Form D ZIPs, amendment chains collapsed, pooled
  funds / Investment Company Act 3(c) vehicles / M&A financings excluded

Single self-contained HTML file, no external requests.

## Known limits

Form D never names the funds on a cap table; investor attribution here is
*inferred* from outside-director board seats and reaches ~18.6% of entries.
The dataset captures roughly 39% of PitchBook-measured US VC dollars — some
large raises (Anthropic, OpenAI, Waymo) file nothing at all, relying on
Section 4(a)(2), which requires no notice.
