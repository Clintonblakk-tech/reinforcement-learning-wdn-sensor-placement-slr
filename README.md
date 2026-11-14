# Reinforcement Learning for Optimal Sensor Placement in Water Distribution Networks: A Systematic Literature Review

**Status:** Public reproducibility repository  
**Repository scope:** Supporting research materials only. The EMS journal-submission manuscript is maintained separately and is not included.

## Purpose
This repository documents the methods, search strategies, screening provenance, included-study register, evidence synthesis and methodological appraisal for the systematic literature review (SLR).

## Review flow
- Records imported into Covidence: 417
- Duplicates removed: 40
- Records screened at title/abstract: 377
- Title/abstract exclusions: 336
- Full-text reports assessed: 41
- Full-text exclusions: 37 (27 wrong intervention; 6 wrong study type; 4 wrong population)
- Studies included in qualitative synthesis: 4

## Information sources
Web of Science, Google Scholar, ScienceDirect, Engineering Village, Springer Nature, IEEE Xplore, and Scopus. The publication-year filter was 2000–2026 across all seven sources.

## Protocol and review management
The review was configured in Covidence as a systematic review. Eligibility criteria were established using the PICOS framework. Covidence settings show one reviewer required for title/abstract screening, full-text review and data extraction. Extraction 2 (mapping and describing the evidence) was selected. The protocol was not separately registered in an external public prospective review registry. See `01_protocol_and_methods/Covidence_PICOS_Protocol_and_Eligibility.md`.

## Repository structure
- `01_protocol_and_methods/` — review scope, protocol development, PICOS criteria and methods.
- `02_search_strategies/` — database-specific search expressions and search/import provenance notes.
- `03_screening_and_PRISMA/` — Covidence import history, PRISMA counts, full-text exclusion register and workflow-status verification.
- `04_included_studies/` — included-study register and evidence-audit report.
- `05_data_extraction/` — manuscript-derived synthesis, evidence-gap reconciliation and extraction workflow documentation.
- `06_methodological_appraisal/` — descriptive appraisal matrix and rating guide.
- `07_figures_and_supplementary/` — PRISMA figure and supplementary materials.
- `10_pending_author_exports/` — outstanding source exports and provenance limitations.

## Important provenance distinctions
1. Covidence dates in the import history are reference-import dates, not necessarily exact database query execution dates.
2. Covidence review settings record 12 November 2026 as the date of last search. Individual source import dates remain separately documented.
3. The publication-year limit of 2000–2026 was confirmed for all seven sources.
4. ScienceDirect notes record an earlier count of 34 retrieved and 27 after document-type filtering, whereas Covidence records 56 imported across three batches. The PRISMA totals use the Covidence import history; the discrepancy is retained transparently.
5. IEEE Xplore had primary and secondary search expressions, but the Covidence import history does not identify which records came from each query.
6. The adapted ten-criterion appraisal is descriptive, not a validated standardised instrument; no overall quality score was used.
7. Screening and extraction were configured for one reviewer. Individual study pages show completed extraction for all four included studies, while the aggregate dashboard displayed 3 In progress and 1 Complete. The reason for this difference is unknown; see `03_screening_and_PRISMA/Covidence_Extraction_Workflow_Status_Verification.txt`.

## Recovered screening and extraction materials
The repository includes the 37-record full-text exclusion register and the evidence-gap reconciliation. The complete decision-level export for all 377 title/abstract records was not recovered. Any partial title/abstract records must not be treated as a complete screening register. The complete four-study extraction workbook and source CSV exports are being prepared for the archival supplement; see the local Zenodo deposit package.

## Public distribution and copyright
Publisher-formatted full-text PDFs and full extracted article texts are excluded because redistribution rights have not been established. Consult the included-study register for bibliographic details and DOI information, and obtain publications through publishers or institutional access. The submission manuscript and working drafts are not part of this public repository.

## Citation and DOI
The GitHub repository is the public working source. Zenodo integration and the first archival release are pending. A DOI must not be cited until Zenodo has processed and published the release. Each subsequent GitHub release will receive its own version DOI; Zenodo also provides a concept DOI for the record across versions.

## Licensing
The repository's original materials, to the extent the listed authors hold the necessary rights, are licensed under the MIT License (see the root `LICENSE` file). Third-party copyrighted content, publisher materials, and materials governed by separate terms are excluded from this licence. Users must respect the original rights and terms applicable to those materials.
