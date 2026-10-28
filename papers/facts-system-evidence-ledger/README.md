# The Facts System: An Evidence-Provenance Ledger for LLM-Authored Content

## Executive summary

**About.** A JSON ledger where every claim carries evidence for and against it, each piece tagged with source, publisher, trust tier, a verbatim quote and a verdict (SUPPORTS or REFUTES). Status is computed from evidence: two independent supports from different publishers give agreement, a refute against a support goes to a human queue, and a claim made only by a named model sits in a lowest "model-asserted" tier that can never reach agreement on its own. The core line: "true because a model said so" is the weakest possible provenance.

**Status.** Design document only, 986 words, dated 2026-07-28. It reads as the specification, not a paper. The figure-validation paper calls itself a companion to it and refers to a "Who Checks the Checker?" result that I did not locate.

**Blocks.** No evaluation: how often does the ledger prevent a wrong claim from shipping? Needs counts from real use, a comparison to existing fact-checking and claim-verification systems, and the missing result.

**Next.** Find the "Who Checks the Checker?" result, pull counts from the ledger as used in the books, and decide whether this is one paper with the figure-validation work or two.

## Where the material is

- Design doc: books/facts/FACTS-SYSTEM.md
- Panel material: books/facts/panel/
- Companion paper: `../validating-generative-scientific-figures/`
- Same stance applied to skills: `../skills-lexicon/`
