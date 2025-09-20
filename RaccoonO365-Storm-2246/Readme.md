# RaccoonO365-Storm-2246 — IOCs Collection

This repository contains a collection of Indicators of Compromise (IOCs) related to the RaccoonO365 phishing-as-a-service platform and associated Storm-2246 campaigns. All indicators are curated for rapid integration and threat intelligence sharing by the security community.

## Contents

- `domains.txt` — Malicious and C2 domains used in campaigns
- `SHA256.txt` — SHA-256 hashes of malicious samples
- `Email_Detection_Fingerprints.txt` — Email subject/fingerprint patterns for detection
- `cryptocurrency-addresses.txt` — Cryptocurrency wallets linked to the actors

Each file contains plain text data, one indicator per line, for easy copy-paste or automation in security solutions.

## Usage

- Block or monitor the domains in firewalls, proxies, or DNS security tools
- Use the SHA-256 hashes for malware hunting on endpoints, sandboxes, or threat feeds
- Apply email fingerprints to improve phishing detection and mailbox rules
- Track and flag listed cryptocurrency wallet transactions for further investigation

## References

- [More info Microsoft](https://blogs.microsoft.com/on-the-issues/2025/09/16/microsoft-seizes-338-websites-to-disrupt-rapidly-growing-raccoono365-phishing-service/)
- [More info Cloudflare](https://www.cloudflare.com/threat-intelligence/research/report/cloudflare-participates-in-global-operation-to-disrupt-raccoono365/#indicators-of-compromise-iocs)
- [IOC Collection by Alex Milla](https://github.com/alex-milla/IOCs/tree/main/RaccoonO365-Storm-2246)

---

_Disclaimer: These IOCs are provided strictly for defensive, educational, and research purposes. Always validate them in your environment before using in production._
