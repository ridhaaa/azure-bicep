# 🔐 Defender + Cost Insights Project
Provisioned Microsoft Defender for Cloud and set up Cost Management tools using Bicep and secure deployment practices.

## 📌 Overview
- Provisioned infrastructure using Bicep templates
- Authenticated via Service Principal from PowerShell
- Connected GitHub Actions for automated deployment
- Enabled Microsoft Defender for Cloud for threat detection
- Configured Cost Management + Budgeting for spend tracking

## 📁 Structure
```
azure-defender-cost/
├── bicep/
  └── main.bicep
├── .github/workflows/
  └── deploy.yml
├── docs/
│ ├── deployment.md
│ ├── cost-management.md
| ├── defender.md
│ └── screenshots/
└── README.md
```

## 🧭 Documentation Breakdown

- deployment.md - bicep and github actions file
- cost-management.md — Budget setup, threshold logic, cost blade usage
- defender.md — Defender plan setup, portal validation steps
- docs/screenshots/ — Portal proof, budget alerts, GitHub deployment logs

## 🔗 Resources
- Bicep Documentation – Microsoft Learn
- Microsoft Defender for Cloud
- Cost Management + Billing
