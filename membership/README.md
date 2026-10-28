# Criterion 2: Membership in selective associations

## Executive summary

**The criterion.** Membership in associations that require outstanding achievement, as judged by recognized experts.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Fellow-level grades where experts judge nominees. The Policy Manual's own examples are IEEE Fellow and AAAI Fellow.

## What USCIS discounts

Membership based on a degree, years of experience, paying dues, subscribing to publications, or job requirements. Ordinary IEEE or ACM membership does nothing. Board or committee service at an organisation does not satisfy this criterion.

## What an agent can do

1. List associations in the person's field that have an expert-judged grade, with the nomination rules, who may nominate, how many references are needed, typical timeline, and how the grade is judged.
2. Mark each association as qualifying or not: dues-based, degree-based or experience-based grades go in the 'does not count' list so no exhibit is wasted on them.
3. Work out the prerequisites for each qualifying grade (years of membership, sponsors, a record of achievement) and what the person is missing.
4. Prepare a nomination timeline, working backward from the next cycle.

## What only a person can do

- Decide whether to pursue a grade.
- Ask the sponsors and nominators; an agent does not.

## Evidence to keep

- Bylaws or page showing the achievement requirement
- Statement of who judges nominees
- Membership certificate or letter
- Date of admission

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
