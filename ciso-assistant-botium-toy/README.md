# Botium Toys: CISO Assistant GRC Platform Project

*Botium Toys is a fictional company used in the Google Cybersecurity Professional Certificate's "Conduct a security audit" activity.*

This project builds on the completed [Botium Toys NIST CSF 2.0 GRC Gap Assessment](../botium-toys-nist-csf-assessment) by applying the same findings inside a self-hosted GRC platform (Docker, Community Edition): [CISO Assistant](https://intuitem.com/ciso-assistant/), an open-source compliance and risk management tool from intuitem.

## Purpose

The original assessment showed I could analyze NIST CSF 2.0 controls on paper. This project tests whether that analysis holds up inside a tool a GRC team would actually use day to day: standing up the platform, structuring assets and domains, running a compliance audit, and building a risk register. Same findings, different skill on display.

## What was built

**Compliance Assessment:** The 12 completed NIST CSF 2.0 findings from the original gap assessment were entered into a Compliance Assessment audit against the NIST CSF 2.0 framework, scoped to a Botium Toys domain with 7 defined assets: internal database, e-commerce/payment platform, employee devices, internal network, legacy systems, accounting/inventory systems, and the physical facility.

**Risk Register:** Three of the highest-priority findings were developed into full risk scenarios, new analytical work beyond the original assessment:

- Unrestricted employee access to cardholder data and customer PII (PR.AA-05)
- Unencrypted cardholder data at rest (PR.DS-01)
- Weak password complexity requirements (PR.AA-03)

Each scenario includes a risk origin and threat classification, a current likelihood/impact rating, a planned Applied Control as treatment, and a residual likelihood/impact rating reflecting the risk level once that control is implemented.

## Exports

- `Audit-Posture-Report.pdf` - full compliance assessment results, scores, and observations
- `Executive-Summary.docx` - cover page, spider chart, and framework tree summary
- `Risk-Report.pdf` - risk scenarios with current and residual risk matrices
- `Controls-Workbook.xlsx` - applied controls tied to both the audit and risk register
