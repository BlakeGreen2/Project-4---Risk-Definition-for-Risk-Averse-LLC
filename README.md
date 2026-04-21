# Project-4---Risk-Definition-for-Risk-Averse-LLC

Overview
--
This project conducts a risk analysis of natural disasters using the FEMA National Risk Index (NRI). The goal is to evaluate whether bias occurs or not in the NRI method by developing an alternative method and comparing the results.
This project was completed for Risk Averse, LLC, a risk analysis consulting group.

---

States Analyzed
-
-Iowa

-Wisconsin

These states were selected due to having similar exposure to hazards/risks.

---

Data Sources
-
-FEMA National Risk Index (NRI) - Census tract-level

-CDC/ASTDR Social Vulnerability Index (SVI)

-FEMA Hazard Mapping Tool

---

NRI Definition of Risk
-
The National Risk Index (NRI) defines risk as a combination of Expected Annual Loss, Social Vulnerability, and Community Resilience. These are combined to get percentile rankings for each Census tract and are then given qualitative ratings from "Very Low" to "Very High".

---

Proposed Risk Definition
-
For this project, we define risk as an weighted score derived from the average of Expected Annual Loss, Social Vulnerability, and the inverted Community Resilience.
The final risk score is calculated using this formula:

Hazard Score - Average of the lightning and drought NRI risk scores with a weight of 50%

Social Vulnerability - SOVI Score with a weight of 30%

Inverse Community Resilience - 100 minus the resilience score with a weight of 20%

**Risk Score = (0.5 * Hazard Score) + (0.3 * SOVI Score) + (0.2 * (100 - Community Resilience Score))**

---

Contents
- Scope of Work
- Gantt Chart
- Annotated Code Document
- Engineering Timesheet
- Written Report
- Raw Data Files
- Python Code File

