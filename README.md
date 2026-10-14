# Assessing Privacy Leakage in Android App Logs: An Empirical Study of Recorded and Real-World Cases

## Overview
This repository contains resources related to the empirical assessment of privacy leakage severity from logs in Android applications.

## Log Dataset

- `logfile.zip`: Raw Android log files collected from 300 apps. The archive is stored using Git LFS.

## RQ1 Folder
This folder contains the filtered Common Vulnerabilities and Exposures (CVE) records that were analyzed as part of RQ1.
- `CVSS.csv`: Filtered Android log-related CVE records with CVSS scores, severity levels, exploitability and impact scores, and CVSS metrics.
- `RQ1_summary.csv`: Manually reviewed RQ1 results identifying the privacy information exposed in each CVE and whether the case contains personally identifiable information (PII).

## RQ2 Folder
This folder contains the RQ2 results, documentation, and prompts:

- `RQ2_Supplementary_Results.pdf`: PDF document accompanying the study.
- `Final-Detection-File-Cases.csv`: Detailed privacy leakage cases retained after the final detection and validation process.
- `Final-Detection-Summary.csv`: Aggregate summary of the final RQ2 detection results.
- `Third-Party-Libraries.csv`: Privacy leakage cases associated with third-party libraries.
- `zero-shot-prompt.txt`: Zero-shot prompt used for the direct privacy detection stage.
- `few-shot-prompt.txt`: Prompt-enhanced template used for the RQ2 privacy detection stage, including known privacy categories and representative value patterns.
