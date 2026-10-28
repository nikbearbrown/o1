# Criterion 5: Original contributions of major significance

## Executive summary

**The criterion.** Original scientific, scholarly, or business-related contributions of major significance.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Citation levels indicative of significance; widespread commentary from others in the field; patents with uptake; commercialization; contributions to software, data, or protocol repositories with documented impact; detailed expert letters corroborated by the record; letters from interested government agencies.

## What USCIS discounts

Work that was merely funded, patented, or published. That shows originality, not significance. This is the hardest criterion and the one most often lost on appeal.

## What an agent can do

1. Track independent citations of each piece of work and separate them from self-citations; flag the ones that build on the work, not just list it.
2. For software and data, collect adoption evidence: downloads, forks, stars, dependent projects, packages that use it, mentions in other people's papers.
3. List authors who built on the work as candidates for independent expert letters, with the paper that connects them. A person makes the approach.
4. Build the exhibit index a letter will point to, so each claim in a letter has an exhibit.
5. Flag claims of significance that have no outside evidence yet, so they are not made.

## What only a person can do

- Say what changed in the field because of the work, in their own words.
- Contact independent experts. Letters must be the expert's own.

## Evidence to keep

- Citation counts by source and date, with self-citations separated
- Adoption data with dates
- Independent commentary
- Commercialisation or licensing records
- Expert letters and the exhibits each cites

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
