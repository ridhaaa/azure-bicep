# 💸 Azure Cost Management Setup

Integrated Azure Cost Management to monitor and control resource spending within the deployment project. Configured a budget and explored cost breakdown using native Azure tools.

---

## 📊 Budget Configuration

Created a monthly budget to receive alerts when cost thresholds are breached. This helps ensure that infrastructure remains within defined spending limits.

- **Budget Name:** Azure Bicep Budget
- **Scope:** Subscription (218c7651-2e81-4365-a60f-bae54d8b138f)
- **Amount:** ₹100 INR
- **Reset Period:** Monthly
- **Alert Threshold:** 90%

### 🔧 Budget Creation Screenshot

![budget-creation](screenshots/cost-budget-create.png)

---

## 📈 Cost Analysis

Utilized **Cost Analysis** under Azure Cost Management to view the current cost usage by service/resource group. This provided insights into what services consumed budget and when.

### 🔍 Filtered by Resource Group

- **Filter:** Resource Group `azure-bicep`
- **Group By:** Service name or resource

### 📸 Cost Analysis Screenshot

![cost-analysis](screenshots/cost-analysis-breakdown.png)

---

## 💡 Azure Advisor (Optional)

Reviewed cost optimization recommendations from Azure Advisor. These tips help reduce unnecessary spending by right-sizing resources and identifying unused services.

### 📸 Cost Recommendations Screenshot

![advisor-cost-recommendations](screenshots/advisor-cost.png)

---

## ✅ Outcome

- Budget alert configured successfully.
- Able to view real-time cost analysis.
- Advisor suggestions used for cost optimization planning.

---

## 🗂️ File Structure

