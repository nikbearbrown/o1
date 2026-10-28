# Criterion 8: High salary or remuneration

## Executive summary

**The criterion.** High salary or remuneration for services, past or prospective.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Pay records, tax returns, offer letters, compared against occupation- and location-specific wage data (BLS, CareerOneStop).

## What USCIS discounts

Broad wage categories spanning unrelated jobs, unreliable self-reported salary sites, foreign salaries simply converted to dollars. Highly valued startup equity can be comparable evidence for a founder, if the reason the criterion does not fit is explained.

## What an agent can do

1. Find the right occupation code and the right metro for the person's job, and pull the official wage data (BLS, CareerOneStop) at the relevant percentiles.
2. Put the person's pay next to it and say where it falls. Say plainly if it does not clear the bar.
3. List opportunities that would raise pay in the field of acclaim honestly (roles, consulting, advisory), without inflating figures.
4. Check that every pay figure has a document behind it.

## What only a person can do

- Supply pay records and tax documents; they are private.
- Never let an agent estimate or round up a person's pay.

## Evidence to keep

- Pay stubs, tax returns, offer letters
- Official wage data for the occupation and location, with the date it was pulled
- Comparison table
- Equity valuation, if used

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
