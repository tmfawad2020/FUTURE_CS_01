# FUTURE_CS_01 — Vulnerability Assessment Report

## Target
`http://testphp.vulnweb.com/` — intentionally vulnerable Acunetix training application.

## Scope
Read-only/passive assessment only. No exploitation, brute force, login bypass, or DoS.

## Deliverables
- `Vulnerability_Assessment_Report.pdf`
- `Vulnerability_Assessment_Report.md`
- `evidence/`

## Evidence note
The prepared report is based on the Future Interns task requirements, public documentation, and public observations. A fresh local Nmap/OWASP ZAP scan was not executed in this environment. Do not claim those tools were run unless you add genuine screenshots/outputs from your own run.

## Key findings
- Unencrypted HTTP / lack of HTTPS: High
- Missing X-Frame-Options: Low
- Missing Content-Security-Policy: Low
- SQL injection and XSS are publicly documented for the intentionally vulnerable training target: High

## Official task
https://futureinterns.com/cyber-security-task-1-2026/