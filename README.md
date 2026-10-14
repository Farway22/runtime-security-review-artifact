# Runtime-security review: supplementary materials

This repository provides the standalone supplementary materials for the systematic review of runtime threat propagation in autonomous LLM agent frameworks (229 primary studies).

## Download

**[Download the reviewer supplement ZIP](https://github.com/Farway22/runtime-security-review-artifact/raw/refs/heads/main/reviewer_supplement_only.zip)**

No GitHub account or Git installation is needed. Extract the archive and open `ReviewerSupplement/REVIEWER_GUIDE.md` for the evidence navigation and reproduction instructions.

## Included

- Final study-level data, descriptive extraction and reviewed-source/version index.
- Search and selection records, coding methods and field-level evidence/adjudication notes.
- Source-page evidence supporting the central comparative insights.
- Read-only numerical replay and traceability scripts, recorded outputs and file hashes.

The attachment **does not contain the manuscript PDF, LaTeX source, bibliography, manuscript figures, compilation dependencies, original-paper full texts or private working files**. This repository has a separate, supplement-only history; it is not a copy of the manuscript repository.

## Reproduce

Node.js 20+ is sufficient; no third-party packages are required. Run from the extracted `ReviewerSupplement` directory:

```sh
node scripts/reproduce_statistics.mjs
node scripts/check_review_traceability.mjs
node scripts/analyze_route_selection_2026-10-12.mjs --summary
node scripts/analyze_recorded_disagreements_2026-10-12.mjs --summary
```

The reviewer guide states the evidence coverage and interpretation boundaries. These checks reproduce the specified calculations and verify recorded values and references, not the semantic correctness of every coding judgment or the experiments of the original studies.

## Version and integrity

Data snapshot: 2026-10-12. Supplement export: 2026-10-14. SHA-256 of the archive is recorded in [SHA256SUMS.txt](SHA256SUMS.txt); the archive also contains a manifest with hashes of its component files.

Linked papers and third-party artifacts remain subject to their respective access conditions and rights. Original source documents are not redistributed.
