# dfir-lab

Hands-on **Digital Forensics & Incident Response** work: labs, case investigations, reference notes and the scripts that come out of them.

> Status: actively updated

## Structure

```
dfir-lab/
├── 00-foundations/     Linux, networking, Windows internals, scripting
├── 01-windows-artifacts/  Registry, Prefetch, Amcache, ShellBags, LNK, Jump Lists, Event Logs
├── 02-memory/          Volatility 3 workflows and plugin notes
├── 03-disk/            File systems (NTFS, ext4), carving, timelines
├── 04-incident-response/  Triage, log analysis, playbooks
├── 05-detection/       Sigma / YARA rules I write and test
├── writeups/           Case write-ups from CTFs and labs (one folder per case)
├── cheatsheets/        Quick references
└── scripts/            Python / Bash tools built along the way
```

## Write-up format

Each case in `writeups/` follows the same template:

1. **Scenario**: what was given (image, logs, PCAP) and the question to answer
2. **Evidence & tools**: hashes of the evidence, tools and versions used
3. **Analysis**: steps taken, with the commands and the reasoning behind each
4. **Timeline**: reconstructed sequence of events
5. **Findings & IOCs**: answers, indicators of compromise, MITRE ATT&CK mapping
6. **Lessons learned**: what I'd do differently

## Progress

| Phase | Topic | Status |
|---|---|---|
| 0 | Foundations: Linux, networking, Windows | In progress |
| 1 | Windows artifacts | Pending |
| 2 | Memory forensics | Pending |
| 3 | Disk forensics & timelines | Pending |
| 4 | Incident response & log analysis | Pending |
| 5 | Detection engineering | Pending |

## Ethics

All analysis here is done on intentionally vulnerable labs, public CTF challenges or images I created myself. No real-world victim data.
