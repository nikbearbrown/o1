# Criterion 4: Judging the work of others

## Executive summary

**The criterion.** Judging the work of others, individually or on a panel.

**Why this folder exists.** So agents can look for opportunities for a person to contribute in this one area, and keep the evidence tidy as it appears. A petition needs evidence for at least three of the eight criteria, and the officer then weighs the whole record against the real standard (sustained acclaim, top of the field). This is one of the eight. Nothing in this folder is legal advice; the attorneys decide what goes in a petition.

**State.** Empty. No opportunities have been searched for and no evidence has been logged yet. `opportunities.csv` and `evidence-log.csv` are headers only.

## What counts

Peer review for journals and conferences; conference abstract review; doctoral dissertation committees; government grant review panels.

## What USCIS discounts

An invitation without proof the review was actually completed. Practitioners generally treat judging student work (class projects, student hackathons) as weak. Volume helps at step 1; venue prestige helps at step 2. Repeat invitations from the same venue show sustained recognition.

## What an agent can do

1. Find open calls for reviewers and program-committee members: journal reviewer sign-ups, conference calls for reviewers and area chairs, abstract-review pools, dissertation committee openings, and grant-panel calls.
2. Rank them by venue standing, and say how the standing was established.
3. Draft the volunteer email or profile for a person to send.
4. After each review, make sure the proof of completion is saved: confirmation email, reviewer acknowledgment or portal screenshot, with date.
5. Track repeat invitations by venue.

## What only a person can do

- Volunteer, accept or decline, and do the review themselves.
- Never let an agent write or submit a review that is presented as the person's own.

## Evidence to keep

- Invitation
- Proof the review was completed
- Venue name, type and standing
- Dates
- Any thanks or reviewer-recognition from the venue

## Files

- `opportunities.csv`: one row per opportunity found. Columns: `found_on`, `opportunity`, `type`, `url`, `deadline`, `fit_note`, `status` (open, pursuing, done, dropped), `decided_by`, `evidence_ref`.
- `evidence-log.csv`: one row per piece of evidence, logged when it is created. Columns: `date`, `item`, `proof_file`, `source_url`, `counts_for` (this criterion, or another, or step 2 only), `note`.

See `../AGENTS.md` for the rules every agent follows in this folder (no fabrication, nothing sent or submitted without a person's yes, record every source).
