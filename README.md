# Contact Network Matcher

A single-page, browser-only tool that matches your LinkedIn connections against a list of target companies and shows where your network has reach.

## What it does

1. **Load a company list** — upload a `.txt`/`.csv`, paste names one per line, or use the built-in ACLI insurer roster.
2. **Load your LinkedIn connections** — the `Connections.csv` from LinkedIn's data export.
3. **See your matches** — every 1st-degree contact who works at a company on your list, fuzzy-matched so "MassMutual" maps to "Massachusetts Mutual Life Insurance Company." Sortable, filterable, with a confidence score and a strictness slider.
4. **Spot-check 2nd-degree** — a coverage map of which companies you reach vs. gaps, plus one-click LinkedIn searches pre-filtered to 2nd-degree people at any company you pick.

## Privacy

Everything runs locally in your browser. No file is uploaded anywhere, and there is no server or backend. Your connections data never leaves your machine.

## How to get your LinkedIn connections file

On desktop: **Me → Settings & Privacy → Data privacy → Get a copy of your data → Connections → Request archive.** LinkedIn emails a download link, usually within ~20 minutes. Unzip it and use `Connections.csv`.

## Running it

Just open `index.html` in any modern browser. No build step, no dependencies.
