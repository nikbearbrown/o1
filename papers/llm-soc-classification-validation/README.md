# LLM-Based Occupational Classification of Job Listings for Sponsorship Opportunity Detection: A Validation Study

## Executive summary

**About.** A pipeline that assigns 2018 SOC codes to job listings from the full listing text (not the title alone), validated against about 1,800 stratified certified LCA records from DOL disclosure data, for finding roles relevant to international workers on F-1/OPT status.

**Status.** Draft shell, 3,436 words, 47 open TO DO markers; the accuracy numbers are blank. A separate methods write-up (1,885 words) is more complete than the paper shell.

**Blocks.** No validation run is recorded in the files I read. Whether the LCA ground truth can be trusted is itself a question: employer-filed SOC codes are self-reported (see the H-1B misclassification paper).

**Next.** Run the validation, fill the accuracy figures, and report how the ground truth's own error rate bounds the result.

## Where the material is

- Paper shell: books/the-reallocation-engine-fresh/archive/Projects/soc_classification_draft.md
- Methods: books/the-reallocation-engine-fresh/archive/Projects/soc_classification_methods.md
- Reallocation Engine evaluation folder (not read for this survey): books/the-reallocation-engine-fresh/eval/

## Related

`../h1b-misclassification-detection/` and `../cognitive-tier-of-startup-hiring/` both depend on this classifier.
