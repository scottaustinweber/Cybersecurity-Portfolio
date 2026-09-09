# Botium Toys — NIST CSF 2.0 GRC Gap Assessment

A redo of the Google Cybersecurity Certificate's Botium Toys security audit exercise, using the official NIST CSF 2.0 Organizational Profile Template to conduct a real gap assessment rather than just the original training checklist.

- [`scenario.md`](scenario.md) — background on Botium Toys and the original assessment findings

## Contents
- `NIST_CSF_Gap_Assessment.xlsx` / `.pdf` — the completed gap assessment (12 findings, current and target state, tier justification)
- `recommendations-memo.docx` — prioritized findings and recommendations
- `policies/` — governance policy drafts addressing the highest-priority findings, adapted from SANS Institute's free policy templates

Policies are adapted from SANS Institute's free Information Security Policy Templates (sans.org/information-security-policy), tailored to this assessment's specific findings.

## Scope and Exclusions

The other frameworks (GDPR and SOC 2) were left out because they were out of the scope of this project, which focused on the NIST guidelines to strengthen the security posture for this company. The changes made from NIST also generally satisfied the requirements from the other frameworks, but didn't seem relevant to this focused summary and policies guided by NIST.

GDPR applies to Botium Toys but the 72-hour EU breach notification plan was already in place in the source report, so no NIST-driven recommendation was needed for it. The unencrypted cardholder data finding directly ties to PCI DSS, so that framework is cited specifically within the assessment. 
