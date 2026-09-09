# Scenario: Botium Toys

This scenario is adapted from the Google Cybersecurity Professional Certificate's "Conduct a Security Audit" course activity. Botium Toys is a fictional small toy company created for that exercise; it does not represent a real business.

Botium Toys sells products both in-store and online, with a warehouse attached to its retail location. The company's IT department manages a mix of on-premises equipment, employee devices, internal networks, retail and inventory systems, and a number of legacy, end-of-life systems that still require manual monitoring.

An internal risk assessment was conducted to evaluate Botium Toys' overall security posture. The assessment found inadequate asset management overall, along with a number of specific gaps across access control, data protection, and operational security. The report rated the company's overall risk fairly high, largely due to how many of these gaps existed at once and how little formal governance sat behind the controls that did exist.

## Key Findings from the Original Assessment

- All employees currently have access to internally stored data, including cardholder data and customer PII/SPII, with no least privilege or separation of duties controls in place.
- Credit card information is accepted, processed, transmitted, and stored without encryption.
- A password policy exists, but its requirements are minimal and don't meet standard complexity expectations, and there is no centralized system enforcing it.
- No intrusion detection system has been installed.
- No disaster recovery plan exists, and the company does not maintain backups of critical data.
- Legacy, end-of-life systems are monitored, but with no defined schedule and unclear intervention procedures.
- The company has an EU customer base and has a plan in place to notify EU customers within 72 hours of a security breach.
- A firewall with appropriately tuned rules is in place, and antivirus software is installed and monitored.
- The physical location has adequate locks, up-to-date CCTV, and functioning fire detection and prevention systems.

## Why This Project Exists

This repository re-does the underlying exercise using the official NIST CSF 2.0 Organizational Profile Template, treating the findings above as the basis for a real gap assessment rather than a training checklist. See README.md for the completed deliverables.
