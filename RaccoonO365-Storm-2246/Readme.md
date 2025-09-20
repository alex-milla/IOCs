# RaccoonO365-Storm-2246 — Malware Hashes (IOCs)

This repository contains a collection of malware hashes related to the RaccoonO365 phishing-as-a-service platform and associated Storm-2246 campaigns. The indicators are curated for rapid integration into security controls and threat intelligence workflows by the community.

## Contents

- `RaccoonO365-Storm-2246_hashes_MD5.txt` — MD5 hashes of malicious files
- `RaccoonO365-Storm-2246_hashes_SHA1.txt` — SHA-1 hashes (if available)
- `RaccoonO365-Storm-2246_hashes_SHA256.txt` — SHA-256 hashes (if available)

Each file consists of plain text hashes, one per line, ready for copy-paste, scripting, or direct SIEM/EDR ingestion.

## Usage

- Search for the presence of these hashes on endpoints, servers, forensic images, or sandbox reports.
- Block file transfers and quarantine threats in EDR/XDR and mail gateways.
- Enrich threat intelligence systems and accelerate incident response.

## References

- [More info Microsoft](https://blogs.microsoft.com/on-the-issues/2025/09/16/microsoft-seizes-338-websites-to-disrupt-rapidly-growing-raccoono365-phishing-service/)
- [More info Cloudflare](https://www.cloudflare.com/threat-intelligence/research/report/cloudflare-participates-in-global-operation-to-disrupt-raccoono365/#indicators-of-compromise-iocs)
- [IOC Collection by Alex Milla](https://github.com/alex-milla/IOCs/tree/main/RaccoonO365-Storm-2246)

---

_Disclaimer: These IOCs are provided strictly for defensive, educational, and research purposes. Always validate in your environment before operational deployment._
