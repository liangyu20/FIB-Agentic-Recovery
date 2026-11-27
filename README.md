# Supplementary Data

This package accompanies the manuscript and Supplementary Information. Paths below are relative to this directory.

- `tables/`: Supplementary Tables S1–S5 and scenario/seed index.
- `cohort/`: seed-level results for the comparison strategies and reviewed-experience runs. The depth fixed-process retry is recorded separately in `analysis/fixed_process_retry_depth.csv`. First-fault image hashes permit checking seed pairing without bundling all images.
- `plan_validation/`: the 128 recorded plan-check calls for the no-experience agent group.
- `experience/`: 16 approved past-recovery records with source, plan, outcome, and expert-review decisions; source index, review record, and review-interface image. Linked image artifacts are omitted.
- `mesh_readback/`: numerical depth readbacks and local profiles used for Table S3 and Fig. 3.
- `analysis/`: numerical inputs for the call score, depth comparison, and fixed process retry.
- `representative_simulation/`: four selected simulation cases (probe, marker, depth, and specimen detachment). `case_index.csv` links each case to its plans, validation records, and selected images in the corresponding case folder.
- `physical_cases/`: for each real-instrument case, the proposed action plan, plan-check decisions, and an ordered image sequence with beam and field width.
