# Phishing Email Analysis Templates

This repository contains a sample phishing email (from CanIPhish) and a small set of analysis documents and templates useful for performing hands-on email threat analysis.

## Contents
- `sample_email.txt` — the sample phishing email (Payoneer account verification) used for analysis.
- `analysis/report.md` — a detailed analysis of the sample email, listing the phishing traits found.
- `analysis/header_analysis_instructions.md` — step-by-step instructions for analyzing raw email headers (SPF/DKIM/DMARC, Received chain).
- `analysis/indicators_checklist.csv` — quick checklist for automated/manual triage.
- `analysis/remediation_advice.md` — recommended actions for recipients and admins.
- `templates/header-paste-template.txt` — template to paste raw headers into when asking for help or using an analyzer.

## How to use
1. Clone the repo.
2. Open `sample_email.txt` and `analysis/report.md` to review the findings.
3. If you receive a suspicious email, export its raw headers (instructions in `analysis/header_analysis_instructions.md`) and paste them into `templates/header-paste-template.txt` before submitting to an analyzer.

## License
This repo is provided for training and awareness. No malicious code is included. Use responsibly.
