# Validating Generative Scientific Figures: A Failure Taxonomy and a Reference-Adjudicated Model Panel

## Executive summary

**About.** A generated figure can render, pass every automated gate and still be false. The paper sorts failures by how hard they are to catch (self-announcing blanks versus plausible-but-false figures, the latter in four sub-types from internally contradictory to chemically plausible with wrong connectivity) and argues that on the hard failures a consensus of confident models is not evidence; an authoritative reference (PDB, UniProt, a canonical structure) is.

**Status.** Drafted, 1,477 words, dated 2026-07-29, with a results section from an inspection pass over one unaudited generation run of 302 figure objects. Four proposed measures (ship-through rate averted, false-confidence rate and others) are listed; I did not check which have been computed.

**Blocks.** The panel's headline rates need to be computed over the full 302 and reproduced; the reference-adjudication step depends on an image-evidence collector whose spec exists but whose run status I did not check.

**Next.** Compute the measures, decide the baseline (the binary "did it render" gate), and sample-check the human judgments.

## Where the material is

- Draft: books/illustrae-pipeline/FIGURE-VALIDATION-PAPER.md
- Evidence report and specs: books/illustrae-pipeline/EVIDENCE-REPORT.md, IMAGE-EVIDENCE-SPEC.md, IMAGE-COLLECTOR-SPEC.md, OBJECT-INVENTORY.md
- Companion: `../facts-system-evidence-ledger/`
