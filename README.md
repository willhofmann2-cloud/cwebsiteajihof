# New money: federal contract leads

Finds companies getting their first contract from a federal agency, using public data from USAspending.gov.

In a Claude Code session on this repository, type: `Use the new-money skill for` and the agency on your beat, such as the Department of Agriculture or USDA.

Claude runs a ready-made script, shows you the results as a private page in your Claude session and saves them here:

- **index.html**: the results page Claude shows you
- **leads.md**: the same leads, readable right on GitHub
- **leads.csv**: the same rows, for a spreadsheet

These are leads to check, not findings.

# Public Assistance Explorer: FEMA disaster aid data

`fema-pa/index.html` is a search tool for every FEMA Public Assistance dataset on OpenFEMA. It asks FEMA's public API directly from your browser, so the numbers are always current. No key, no server.

**To use it:** download `fema-pa/index.html` and open it in your browser. Or turn on GitHub Pages for this repository (Settings → Pages → deploy from your branch) and open `/fema-pa/`.

It covers all six Public Assistance datasets, and any new one FEMA adds shows up automatically:

- **Funded projects**: every obligated project worksheet, with cost and federal share
- **Grant awards**: each obligation on a project, version by version
- **Applicant totals**: projects and federal dollars per applicant per disaster
- **Program delivery**: where each applicant stands in the process
- **Applicants**: who applied, with mailing address
- **Second appeals**: appeals decided at FEMA headquarters

What you can do:

- Search names and titles, filter by disaster number, state, date and dollar range, and add a condition on any field.
- Sort by any column and choose which columns to show.
- Click a row to see the whole record, then jump to the same disaster or the same applicant in the other datasets.
- **Add it up**: total dollars (or count records) grouped by state, county, applicant or any other field, across every match. Click a bar to filter to it.
- **Download CSV** of all matches (up to 100,000 rows), or copy the exact API link for the search.
- The address bar keeps your search, so you can bookmark or share it.

FEMA's text search matches exact letter case, so the tool tries what you typed, ALL CAPS, lowercase and Title Case. These are FEMA's figures as reported. Check a record before you rely on it.
