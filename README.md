# BC Hydro Supply Chain Risk Dashboard (Hackathon MVP)

## Overview  
This dashboard was built for a beedie buainess analytics hackathon as an internship-level analytical prototype using available category-level procurement and supply chain data. The goal is to identify categories most vulnerable to operational disruption due to long supplier lead times, limited inventory buffers, variable vendor performance, and exposure to external tariff risk.

This prioritization tool is not a predictive model. Rather, it is a structured framework designed to surface where supply chain resources and mitigation efforts should be focused first.

---

## Data Scope  
This MVP focuses on a high-priority subset of procurement categories (~$605M annual spend), selected based on risk tolerance and operational impact. Categories with missing or incomplete operational data (e.g., unavailable lead times) are excluded from the vulnerability ranking.

## Vulnerability Scoring Framework  
A composite vulnerability score (0–100) was developed:

- Lead Time Risk (30%)
- Inventory Buffer Risk (25%)
- Risk Tolerance Criticality (20%)
- Vendor Performance Signal (15%)
- Tariff Exposure Context (10%)

Higher scores indicate greater disruption vulnerability.

---

## Dashboard Preview  

## Dashboard Preview  

### Portfolio Overview  
![Portfolio Overview](https://raw.githubusercontent.com/meharpreetkaur-tech/bc-hydro-supply-chain-risk-dashboard/main/screenshots/portfolio-overview.png)

### Lead Time vs Inventory Buffer  
![Lead Time Analysis](https://raw.githubusercontent.com/meharpreetkaur-tech/bc-hydro-supply-chain-risk-dashboard/main/screenshots/lead-time-analysis.png)

### Tariff Exposure Scenario  
![Tariff Exposure](https://raw.githubusercontent.com/meharpreetkaur-tech/bc-hydro-supply-chain-risk-dashboard/main/screenshots/tariff-exposure.png)

### Executive Summary  
![Executive Summary](https://raw.githubusercontent.com/meharpreetkaur-tech/bc-hydro-supply-chain-risk-dashboard/main/screenshots/executive-summary.png)

---

## Key Insights  
- Major Equipment contains the highest concentration of disruption-sensitive categories  
- Switchgear shows extreme lead times (>800 days) and low risk tolerance  
- Tariff shocks disproportionately impact cross-border dependent components  

---

## Recommendations  
- Supplier diversification review for top-ranked categories  
- Safety stock planning for long-lead-time items  
- Expand model coverage across additional procurement portfolios  

---

## Skills Demonstrated  
- Supply chain risk analytics  
- Dashboard development & KPI design  
- Scenario-based disruption assessment  
- Executive-level insight communication  
