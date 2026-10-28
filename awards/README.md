# Criterion 1: Prizes and awards

## Executive summary

**The criterion.** Nationally or internationally recognized prizes or awards for excellence in the field.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Awards from well-known national institutions or professional associations; some dissertation awards; awards for presentations at recognized conferences (for example a best-paper award at a recognized venue). Team awards count if the person is a named recipient.

## What USCIS discounts

Awards limited to one locality, employer, or school. USCIS weighs the selection criteria, significance, number of awardees, and who was eligible to compete. An award open across a whole research university or a national professional body can qualify where a department-only award will not.

## What an agent can do

1. Search professional societies, major conferences and national bodies in the person's field for awards the person could be nominated for or could apply to, and list each with eligibility, who judges, how many are given each year, and the deadline.
2. Check each award against the discount list: flag anything local, employer-only or school-only as weak, and say why.
3. For awards already won, collect the proof: selection criteria, applicant pool size, number of winners, who judged, and the announcement.
4. Where an award needs a nominator, find who could nominate and draft the nomination packet for the person to review.
5. Watch deadlines and put them in the opportunities log with a date.

## What only a person can do

- Decide whether to apply or be nominated, and sign every application.
- Ask a nominator; an agent drafts, a person asks.

## Evidence to keep

- Award letter or certificate
- Announcement page (archived copy with date)
- Selection criteria and eligibility rules
- Number of applicants and winners
- Names and standing of the judges

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
