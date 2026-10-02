# Coherent WDM-OFDM neighbor-monitor response–information-age data

This archive contains 13 unchanged files from the frozen V4.2 figure and supplementary source packets. It contains four figure plotting CSVs and nine supporting CSV/JSON files. The analysis concerns a simulated system, a retrospective post-SC-DBP residual proxy, one fixed three-lag ridge estimator, and two held-out paired realizations (A and B). These files do not establish detector/ADC performance, physical bandwidth or latency limits, compensation benefit, or BER/Q outcomes.

## Contents

- `data/plotting/Data_File_1_Fig2_matrix.csv`: 24 matrix cells for Fig. 2.
- `data/plotting/Data_File_2_Fig3_age_zero.csv`: eight age-zero cells and stored response contrasts for Fig. 3.
- `data/plotting/Data_File_3_Fig4_information_age.csv`: six unfiltered cells and stored age contrasts for Fig. 4.
- `data/plotting/Data_File_4_Fig5_criteria_retention.csv`: all 24 cells with frozen predicates and stored VR ratios for Fig. 5.
- `data/supporting/cell_metrics.csv`: complete frozen cell scores and predicates (24 rows).
- `data/supporting/control_metrics.csv`: association-shift and negative-feature controls (336 rows).
- `data/supporting/predictions.csv`: 101 scored target/prediction rows for each of 24 cells (2424 rows).
- `data/supporting/contrasts.json`: stored prespecified contrasts.
- `data/supporting/finite_record_spectrum.csv`: eight report-only digital spectrum rows.
- `data/supporting/response_qualification.csv` and `response_curve_samples.csv`: deterministic response qualification and sampled curves (3 and 4503 rows).
- `data/supporting/e145_comparators.csv` and `e145_spectral_checks.csv`: preliminary protocol context (5 and 8 rows); these are separate from the primary A/B matrix.

The four plotting CSVs select or copy existing frozen values as strings; they do not refit models or recalculate scientific metrics. The nine supporting files are byte-identical to the checked Supplement V2 typeset packet. `manifest.json` gives byte sizes, SHA-256 hashes and CSV data-row counts. No simulated raw waveforms or complete analysis environment are included in this archive; those remain available from the authors on reasonable request, subject to the final Data Availability statement.

The 13 data files and this metadata are offered under the Creative Commons CC0 1.0 Universal public-domain dedication (https://creativecommons.org/publicdomain/zero/1.0/). Cite the versioned dataset and associated article where practical. The source manuscript, figures, and Supplement are separate submission assets.
