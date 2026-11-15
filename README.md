# Reinforcement Learning for Optimal Sensor Placement in Water Distribution Networks: A Systematic Literature Review

**Status:** Public reproducibility repository  
**Repository scope:** Supporting research materials only. The EMS journal-submission manuscript, working drafts and journal supplementary submission files are maintained separately and are not included.

## Purpose
This repository documents the methods, search strategies, screening provenance, included-study register, evidence synthesis, data-extraction records and methodological appraisal for the systematic literature review (SLR).

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
- `04_included_studies/` — included-study register and evidence-audit materials.
- `05_data_extraction/` — original Covidence extraction CSV, organised Excel extraction register, extraction provenance and limitations, evidence-gap reconciliation, and manuscript-derived study synthesis.
- `06_methodological_appraisal/` — descriptive appraisal matrix and rating guide.
- `08_manuscript_and_reporting/` — author-declaration and Zenodo metadata planning documents; not the journal-submission manuscript.
- `09_provenance_and_checksums/` — provenance and package-integrity documentation.
- `10_pending_author_exports/` — documentation of source exports that remain unavailable or incomplete.
- `11_zenodo_archival/` — Zenodo archival and release-preparation notes.

## Important provenance distinctions
1. Covidence dates in the import history are reference-import dates, not necessarily exact database query execution dates.
2. Covidence review settings record 12 November 2026 as the date of last search. Individual source import dates remain separately documented.
3. The publication-year limit of 2000–2026 was confirmed for all seven sources.
4. ScienceDirect notes record an earlier count of 34 retrieved and 27 after document-type filtering, whereas Covidence records 56 imported across three batches. The PRISMA totals use the Covidence import history; the discrepancy is retained transparently.
5. IEEE Xplore had primary and secondary search expressions, but the Covidence import history does not identify which records came from each query.
6. The adapted ten-criterion appraisal is descriptive, not a validated standardised instrument; no overall quality score was used.
7. Screening and extraction were configured for one reviewer. Covidence screenshots of the individual study pages showed all four included-study records marked “You completed extraction”, while the aggregate dashboard separately displayed 3 In progress and 1 Complete. The reason for this difference is unknown; see `03_screening_and_PRISMA/Covidence_Extraction_Workflow_Status_Verification.txt` and `05_data_extraction/Extraction_Export_Provenance_and_Limitations.txt`.

## Data-extraction materials and limitations
The `05_data_extraction/` folder contains the original single-sheet Covidence CSV export dated 15 November 2026 and an organised Excel workbook. The source export contains five data records across 59 columns: four individual reviewer extraction records covering the four included studies, plus one additional consensus record for Covidence study #7. The workbook separates individual and consensus records and preserves the source export in its `Original_Export` sheet.

Two source fields are blank and remain unaltered: Ettyem et al. (#286), “Network or benchmark name”; and Sukya et al. (Bayesian optimisation, #7), “Possible conflicts of interest for study authors”. The separate `Evidence_Gap_Reconciliation.csv` documents evidence-based interpretations without silently changing the source fields. See the extraction README and provenance note for details.

The complete decision-level export for all 377 title/abstract records was not recovered. Any partial title/abstract records must not be treated as a complete screening register. Screening and extraction were conducted by one reviewer.

## Public distribution and copyright
Publisher-formatted full-text PDFs and full extracted article texts are excluded because redistribution rights have not been established. Consult the included-study register for bibliographic details and DOI information, and obtain publications through publishers or institutional access. The submission manuscript, working drafts and journal supplementary submission files are not part of this public repository.

## Citation and DOI
The first archived release is published on Zenodo as version `v1.0.0` (version DOI: [10.5281/zenodo.24235527](https://doi.org/10.5281/zenodo.24235527)). The concept DOI for citing the record across versions is [10.5281/zenodo.24235526](https://doi.org/10.5281/zenodo.24235526). Cite the version DOI when referring specifically to the v1.0.0 deposit. Subsequent published versions will have their own version-specific DOIs; the concept DOI remains associated with the record across versions.

## Licensing
The repository's original materials, to the extent the listed authors hold the necessary rights, are licensed under the MIT License (see the root `LICENSE` file). Third-party copyrighted content, publisher materials, and materials governed by separate terms are excluded from this licence. Users must respect the original rights and terms applicable to those materials.
