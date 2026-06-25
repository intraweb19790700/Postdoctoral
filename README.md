# Replication data for the postdoctoral policy computability manuscript

This folder contains the data files used by the manuscript:

`When Policy Growth Does Not Become Evaluable Rules: Measuring Policy Computability in Chinese Postdoctoral Governance, 1986-2026`.

## Folder structure

```text
data_for_github/
  raw/
    postdoctoral_policies_20240229.xlsx
    supplemental_policies_2024_2026_filtered.csv
  audit/
    excluded_invalid_dates.csv
  processed/
    document_digital_twin_scores.csv
    clause_evidence_units.csv
    stage_pdti_summary.csv
    topic_labels.csv
    validation_summary.json
```

## Files

- `raw/postdoctoral_policies_20240229.xlsx`: Original user-provided Chinese postdoctoral policy dataset, containing 239 records.
- `raw/supplemental_policies_2024_2026_filtered.csv`: Supplemental official-channel records added for the 2024-2026 extension, containing 31 records.
- `audit/excluded_invalid_dates.csv`: One record excluded from the analytical corpus because its date could not be parsed.
- `processed/document_digital_twin_scores.csv`: Final document-level analytical table used for PDTI, topic posterior, entropy, readiness, stage and validation analyses.
- `processed/clause_evidence_units.csv`: Final clause-level analytical table containing 10,875 clause evidence units and actor, instrument, object and rubric tags.
- `processed/stage_pdti_summary.csv`: Stage-level summary statistics reported in the manuscript.
- `processed/topic_labels.csv`: Eight-topic semantic policy twin labels, keyword signals, mean posterior intensities and primary-topic shares.
- `processed/validation_summary.json`: Summary of validation statistics, including five-fold AUC and corpus-level means.

## Analytical corpus

The final analytical corpus contains 260 dated policy and governance records after title-date deduplication and exclusion of one invalid-date record. The date range is 1986-10-27 to 2026-05-29.

## Notes

The corpus should be described as curated policy and governance records, not as an exhaustive collection of all Chinese postdoctoral regulations. Some original records do not contain a URL field, while the supplemental records were collected from official postdoctoral information channels.
