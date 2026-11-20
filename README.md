# TASK3# API Security Risk Analysis

An analysis of a sample API covering authentication and authorization, data exposure, rate limiting, input validation, and error handling. Findings are explained in business-friendly language with practical remediation steps.

## Contents
- `API_SECURITY_RISK_ANALYSIS_REPORT.md`: Full report with findings, Postman test steps, and remediation
- `README.md`: Project overview

## Tools
- Postman / Insomnia
- Browser DevTools
- OWASP crAPI (test environment)
- Google Docs / MS Word / PDF

## Skills Demonstrated
- API security analysis
- Authentication and authorization assessment
- Risk identification
- Security documentation
- SaaS security fundamentals

## Test Environment (crAPI)
Run locally with Docker:
```bash
git clone https://github.com/OWASP/crAPI.git
cd crAPI/deploy/docker
docker compose -f docker-compose.yml --compatibility up -d
```

## Disclaimer
Only test APIs you own or have written permission to assess. crAPI is intentionally vulnerable and intended for local learning use.
