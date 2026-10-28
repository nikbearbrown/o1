# Criterion 6: Authorship of scholarly articles

## Executive summary

**The criterion.** Authorship of scholarly articles in professional journals or other major media.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Being a listed author (not necessarily first or sole); peer-reviewed published conference proceedings. Listed authorship alone satisfies the criterion at step 1.

## What USCIS discounts

Venue quality is judged later, in the totality review. A pay-to-publish journal meets the plain wording but does not necessarily support a finding of acclaim. Papers produced to hit a count, in weak venues, can erode credibility.

## What an agent can do

1. The papers themselves live in `../papers/`, one folder per paper. This folder is for the venue side.
2. For each paper in `../papers/`, find venues that fit, and document each venue's selectivity: acceptance rate, impact factor or field ranking, and whether it is peer reviewed.
3. Flag pay-to-publish or unselective venues. Paying an open-access fee at a selective journal does not count against a paper.
4. Track calls for papers and deadlines, and match them to drafts that could realistically be ready.
5. Keep each paper's status current (drafted, shell, design only, material only) and list what blocks it.

## What only a person can do

- Choose the venue, submit, and sign the author agreement.
- Settle authorship order with co-authors.

## Evidence to keep

- Published article or proceedings entry (with DOI)
- Venue selectivity evidence
- Author list and the person's position in it
- Peer-review statement

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
