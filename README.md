# 🔐 Defender + Cost Insights Project
Provisioned Microsoft Defender for Cloud and set up Cost Management tools using Bicep and secure deployment practices.

## 📌 Overview
- Provisioned infrastructure using Bicep templates
- Authenticated via Service Principal from PowerShell
- Connected GitHub Actions for automated deployment
- Enabled Microsoft Defender for Cloud for threat detection
- Configured Cost Management + Budgeting for spend tracking

## 🛠️ Tech Stack
- **Bicep** - ARM deployments
- **Azure Resource Manager** - infrastructure provisioning
- **Microsoft Defender for Cloud** - security posture
- **Azure Cost Management** - budgeting and analysis
- **PowerShell** 
- **GitHub Actions** - CI/CD pipeline

## ✅ Tasks Completed
### Infrastructure

- Wrote modular main.bicep to deploy Defender plans and Cost tools
- Deployed from PowerShell, authenticated with a Service Principal
- Created Service Principal using:

```
az ad sp create-for-rbac `
  --name "gh-bicep-deploy" `
  --role contributor `
  --scopes /subscriptions/<your-sub-id>/resourceGroups/azure-bicep `
  --sdk-auth
```
- Exported JSON output to use as a GitHub Actions secret

### Microsoft Defender
- Enabled Microsoft Defender for Cloud with relevant plan toggles
- Verified enablement and pricing tier from Azure Portal
- Validated security recommendations appeared in the dashboard

### Cost Management
- Deployed budget resource with alert thresholds
- Connected to Cost Analysis blades in the portal
- Tagged resources for tracking using Cost Allocation Tags

📁 Structure
azure-defender-cost/
├── bicep/
│ ├── main.bicep
│ └── parameters.json
├── .github/workflows/
│ └── deploy.yml
├── docs/
│ ├── defender.md
│ ├── cost-management.md
│ └── screenshots/
└── README.md

🧭 Documentation Breakdown
📄 defender.md — Defender plan setup, portal validation steps
📄 cost-management.md — Budget setup, threshold logic, cost blade usage
📸 docs/screenshots/ — Portal proof, budget alerts, GitHub deployment logs

🔗 Resources
- Bicep Documentation – Microsoft Learn
- Microsoft Defender for Cloud
- Cost Management + Billing
