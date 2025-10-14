# 🏙️ Zaya DLD – Real Estate Analytics Dashboard (Power BI)

This repository hosts an interactive **Power BI Report (.PBIX)** analyzing **Dubai Land Department (DLD)** property transactions — focusing on pricing dynamics, transaction volumes, property segmentation, and future supply.

All visuals, slicers, DAX measures, and interactivity are preserved.  
The data model has been trimmed to remove confidential or unnecessary content, reducing file size while keeping every page fully functional.

---

## 📊 Overview

**Zaya DLD** provides a comprehensive analytical framework for exploring Dubai’s real-estate market.  
The dashboard combines trend, composition, and performance analyses across multiple property dimensions.

**Main report pages**
1. **Key Metrics** – Executive KPIs: total transactions, price per sqft, acceleration, and growth.  
2. **Trend Insights** – Monthly time-series with dynamic metric selector and segmentation.  
3. **Top 10 % Transactions** – Premium market overview with a dedicated tooltip page.  
4. **Beds Insights** – Price and volume breakdown by bedroom count.  
5. **Villa vs Apartment** – Comparative performance between product categories.  
6. **Future Supply** – Pipeline and new-project analysis vs recent demand.  
7. **Timeframe Insights** – Short- vs long-term comparisons and momentum checks.  
8. **Share of Transactions** – Market share and composition of transaction types.  
---

## 🧱 Data Model & Structure

| Table | Purpose | Example Fields |
|-------|----------|----------------|
| **Fact** | Core transaction facts | `Price per Sqft`, `Trans_Group_En`, `Reg_Type_En`, `Area_Name_En`, `Property_Type_En` |
| **Date** | Calendar dimension | `Date`, `Month`, `Year`, `Quarter` |
| **Yaxis_Selector** | Metric parameter table | `Metric` (Price per Sqft, Transactions, Growth, Acceleration) |

Model follows a **star schema** with explicit DAX measures for performance and transparency.

---

## 🚀 How to Use

1. **Download** the `.pbix` file  
   ```bash
   git clone https://github.com/<ArashSaraee>/Zaya-DLD-PowerBI.git
