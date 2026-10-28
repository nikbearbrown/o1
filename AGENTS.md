# Rules for agents working in o1/

These apply to every folder here: the eight criterion folders (`awards`, `membership`, `press`, `judging`, `original-contributions`, `authorship`, `critical-role`, `salary`) and `papers/`.

## The job

Find opportunities for a person to contribute in each of the eight O-1A areas, keep the evidence as it is created, and report honestly what exists and what is missing. Agents find, track and draft. People decide, ask, send and sign.

## Hard stops

1. **Never fabricate or embellish evidence.** No invented citations, awards, memberships, press, reviews, pay figures or quotes. If a fact has no source, it is a to-do, not evidence.
2. **Nothing goes out without a person's explicit yes.** An agent drafts emails, nominations, pitches, reviewer volunteering and applications. A person sends or submits them. An agent never contacts a journalist, editor, nominator, recommender or officer on its own.
3. **Never write a review, letter or statement that will be presented as someone else's own.** Expert letters are written by the expert. Reviews are done by the reviewer.
4. **Record where every item came from:** URL, date retrieved, and an archived copy when the page might change. Log it when found, not at filing.
5. **Say what is weak.** Mark local awards, dues-based memberships, self-generated press, paid placements, unselective venues and passing mentions as weak, with the reason.
6. **Do not give legal advice.** The attorneys decide which criteria to claim and how to argue step 2. Do not state that a person "meets" a criterion.
7. **Keep personal data out of public files.** Names, pay, immigration status, and case strategy stay in the git-ignored `PRIVATE/` folder, not in the READMEs or CSVs that may be published.
8. **The 2026 policy details in `README.md` are unverified by the agent that wrote them.** Re-check against USCIS pages before relying on them.

## How to log

- Opportunities go in the folder's `opportunities.csv`. Evidence goes in its `evidence-log.csv`. Keep one row per item. Never delete a row; change `status` instead.
- Avoid double-counting: if one project is the source of the press, the talk and the critical-role letter, say so in `note`, so the case spreads across distinct accomplishments.
- Keep two lists in mind for every item: does it count at step 1 (falls within the criterion), and does it help at step 2 (shows sustained acclaim at the top of the field).

## Reporting

When you finish a task, report what you found, what you could not verify, and what a person must decide. Give absolute paths to any file you wrote.
