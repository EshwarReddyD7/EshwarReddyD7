# Hi, I'm Eshwar Reddy

Cybersecurity engineer building real defensive and offensive tools.

## Currently

Shipping a 10-project cybersecurity portfolio: packet analysis, intrusion detection, threat intelligence, mini-SIEM, phishing detection, cloud security audit, web vuln scanning, recon, educational C2, and adversary emulation. All open source, all tested, all deployable with one command.

## Tech stack

| Domain | Tools |
|---|---|
| Languages | Python, JavaScript, TypeScript |
| Security | Scapy, scikit-learn, MITRE ATT&CK, Sigma, STIX |
| Backend | FastAPI, SQLite, asyncio, httpx |
| Frontend | React, Streamlit, Chrome MV3 |
| Infrastructure | Docker, AWS, GCP, GitHub Actions |

## Featured projects

### Blue team

[**packetsleuth**](https://github.com/EshwarReddyD7/packetsleuth) — Wireshark-style web packet analyzer with port-scan and DNS-tunnel anomaly detection.

[**sentinelids**](https://github.com/EshwarReddyD7/sentinelids) — Hybrid signature + IsolationForest intrusion detection. MITRE ATT&CK tagged.

[**threatlens**](https://github.com/EshwarReddyD7/threatlens) — Multi-source threat intel aggregator (AbuseIPDB, OTX, VirusTotal, URLhaus). STIX 2.1 export.

[**logforge**](https://github.com/EshwarReddyD7/logforge) — Mini SIEM with Sigma-style YAML rules over Sysmon, auditd, and CloudTrail.

[**phishguard**](https://github.com/EshwarReddyD7/phishguard) — ML phishing URL detector with gradient-boosted model and Chrome MV3 extension.

[**cloudaudit**](https://github.com/EshwarReddyD7/cloudaudit) — AWS/GCP misconfiguration scanner mapped to CIS Benchmarks and NIST 800-53.

### Red / purple team (authorized lab use only)

[**reconx**](https://github.com/EshwarReddyD7/reconx) — Automated recon framework with strict scope allowlist enforcement.

[**webpwn-lab**](https://github.com/EshwarReddyD7/webpwn-lab) — Web vulnerability scanner for DVWA / Juice Shop. SQLi, XSS, CSRF, IDOR.

[**c2edu**](https://github.com/EshwarReddyD7/c2edu) — Educational C2 framework that ships with the Sigma rules it triggers.

[**purplerange**](https://github.com/EshwarReddyD7/purplerange) — Adversary emulation with detection-coverage scoring against your SIEM.

## How to try them

Every project ships with a Streamlit GUI. Clone, install, run:

```bash
pip install -r requirements.txt
streamlit run gui.py
```

No CLI required. Tests, Docker setup, and architecture diagrams included in each repo.

## Get in touch

Email: jayanthreddy268.jr@gmail.com
