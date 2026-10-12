# Threat Modeling Suite

STRIDE and PASTA threat modeling tool with DFD builder, risk assessment matrix, threat tree visualization, and architecture review templates for security-by-design.

## Features

- DFD Builder: Drag-and-drop data flow diagram construction
- STRIDE Analysis: Systematic threat enumeration
- Risk Scoring: Likelihood x Impact matrix
- Control Mapping: Threat -> Control recommendation linking
- Threat Tree Visualization: Attack path visualization
- Architecture Review: Compliance framework mapping (GDPR, ISO27001)
- Export: PDF reports and compliance documentation

## Quick Start

```bash
git clone https://github.com/Korir555/threat-modeling-suite.git
cd threat-modeling-suite
pip install -r requirements.txt
flask run
```

Access: http://localhost:5000

## Threat Categories (STRIDE)

- S - Spoofing: Authentication & identity
- T - Tampering: Data integrity & validation
- R - Repudiation: Accountability & logging
- I - Information Disclosure: Encryption & privacy
- D - Denial of Service: Availability & resilience
- E - Elevation of Privilege: Authorization & access control

## Technologies

Python 3.9+ | Flask | D3.js (visualization) | STRIDE/PASTA methodologies

## Hiring Relevance

- Security architecture and design review
- Threat modeling and risk assessment
- Enterprise architecture security
- Product security engineering

## Documentation

Full methodology and case studies: Case Study

## License

MIT License
