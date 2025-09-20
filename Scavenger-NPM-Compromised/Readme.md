# Scavenger-NPM-Compromised — IOCs Collection

This repository contains a collection of Indicators of Compromise (IOCs) related to the Scavenger-NPM compromised package campaign. Curated by Alex Milla, this dataset is intended for defenders and threat researchers for swift ingestion and analysis.

## Contents

- `Scavenger-NPM-Compromised_domains.txt` — Malicious or suspicious domains observed in the campaign
- `Scavenger-NPM-Compromised_sha256.txt` — SHA-256 hashes of compromised or malicious artifacts

All files are in plain text, one indicator per line, for straightforward automation or integration with SOC/EDR/SIEM workflows.

## Usage

- Block or monitor the listed domains in web gateways, DNS, or proxy solutions.
- Use the SHA-256 hashes for detection and hunting on endpoints, sandboxes, or threat intelligence platforms.

## References

- [Technical Analysis — cyberintelligence.dev](https://www.cyberintelligence.dev/npm-package-supply-chain-attacks/)
- [CrowdStrike analysis — crowdstrike.com](https://www.crowdstrike.com/en-us/blog/crowdstrike-falcon-prevents-npm-package-supply-chain-attacks/)
- [IOC Collection by Alex Milla](https://github.com/alex-milla/IOCs/tree/main/Scavenger-NPM-Compromised)

---

_Disclaimer: These IOCs are provided solely for defensive, research, and educational use. Always validate in your own environment before operational deployment._
