# Project-4---Risk-Definition-for-Risk-Averse-LLC

Overview
--
This project conducts a risk analysis of natural disasters using the FEMA National Risk Index (NRI). The goal is to evaluate whether bias occurs or not in the NRI method by developing an alternative method and comparing the results.
This project was completed for Risk Averse, LLC, a risk analysis consulting group.

---

States Analyzed
-
-Iowa

-Wyoming

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
For this project, we define risk as an equally weight score derived from the average of Expected Annual Loss, Social Vulnerability, and the inverted Community Resilience.
The final risk score is calculated using this formula:

**Risk Score = (EAL Percentile + Social Vulnerability Percentile + (100 - Community Resilience Percentile)) / 3**

---

Contents
-
-
-
-
-

