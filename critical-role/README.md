# Criterion 7: Critical or essential employment

## Executive summary

**The criterion.** Employment in a critical or essential capacity for organizations with a distinguished reputation.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Research roles in distinguished departments or institutions; named investigator on merit-based grants (including SBIR); founder of a well-funded startup; a key supporting role explained in detail by the director or principal investigator.

## What USCIS discounts

Titles without substance. USCIS evaluates duties and performance, not the job title. The organization must separately be shown to be distinguished. Both halves must be proved: the role was critical or essential, and the organisation (or the specific division) has a distinguished reputation.

## What an agent can do

1. For each organisation the person has worked for, collect reputation evidence: national rankings, research classification (for example Carnegie R1/R2), government grants, funding commensurate with stage and industry, media coverage.
2. For each role, collect evidence of what the person did and what changed because of it: duties, outcomes, project records, and records made at the time.
3. Find merit-based grant opportunities where the person could be a named investigator, including SBIR, and list deadlines.
4. Prepare the outline of the letter from the director or principal investigator: what the role was, why it mattered relative to others in similar positions. The letter itself is written by that person.
5. Flag a small or young organisation whose distinguished reputation would be hard to prove.

## What only a person can do

- Obtain the letter from the director or principal investigator.
- Apply for grants and sign them.

## Evidence to keep

- Job description and offer letters
- Organisation reputation evidence
- Records made at the time of the work
- Letter from the director or principal investigator
- Grant award notices naming the person

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
