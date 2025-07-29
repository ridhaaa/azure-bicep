# 🔐 Defender + Cost management Project
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

- `deployment.md` – Bicep deployment process and GitHub Actions workflow
- `cost-management.md` – Budget setup, alert rules, and cost analysis 
- `defender.md` – Defender plan configuration and security recommendations
- `docs/screenshots/` – Screenshots 

## 🔗 Resources
- Bicep Documentation – Microsoft Learn
- Microsoft Defender for Cloud
- Cost Management + Billing
