# TrashBeta: Closing Nigeria's Waste Reporting Gap with Citizen Data & GovTech Analytics

## How 301 citizen reports and social media mining exposed systemic waste failures across 25 states during the 2025 festive season.

---
<img width="985" height="569" alt="Screenshot_1-6-2026_132950_" src="https://github.com/user-attachments/assets/8c5ed03f-de70-4779-bd64-a2af214b65e1" />



## The Problem

Nigeria generates approximately **32 million metric tons of solid waste annually**, yet reporting channels remain fragmented, informal collection coverage is low, and citizens rarely receive acknowledgment — let alone resolution — when they report issues.

This creates what TrashBeta calls the **"Silence Gap"** :

- Complaints go unacknowledged.
- Authorities lack centralized situational awareness.
- Private sector operators (PSPs) operate without verifiable performance metrics.
- No feedback loop exists to track resolution progress.

---

## Project Objectives

Over a **13-day beta** (Dec 19–31, 2025), TrashBeta set out to:

- Validate demand for a nationwide waste reporting platform.
- Cover at least 10 states (achieved 25).
- Collect at least 300 verified reports (achieved 301).
- Measure user engagement (photo willingness, app interest, contact sharing).
- Identify waste hotspots and systemic failure patterns via citizen and social media data.

---

## Data Collection

**Primary Source:**
- Structured Google Forms survey distributed via WhatsApp, Twitter/X, and university networks
- Total verified reports: 301

**Secondary Source:**
- Social media mining and news scraping
- 100+ verified hotspot logs

**Core data dimensions captured:**
- Waste type, state, LGA, landmark, report date
- Issue duration, urgency (1–5)
- Community impacts (multi-select)
- Previous report status and action taken
- Photo willingness, contact info, update preference

---
<img width="978" height="569" alt="Screenshot_1-6-2026_133413_" src="https://github.com/user-attachments/assets/637ae9a1-d126-40d2-a6a6-26dc6e7c4d45" />



## Key Features (Operational Significance)

- **Landmark (text field):** Dispatch-ready location when GPS unavailable.
- **Issue duration:** Performance indicator — 34% reported over 1 month, indicating systemic neglect.
- **Previous report + action taken:** Quantifies institutional accountability.
- **Multi-select community impact:** Enables harm-weighted prioritization.

---

## Methods

- Survey design and digital ethnography for triangulation.
- Data cleaning, validation, and feature engineering (landmark normalization, urgency clustering).
- Exploratory data analysis and geospatial hotspot mapping.
- Dashboard development for operational and policy audiences.
- Stakeholder-oriented storytelling and recommendations.

---

## Results & Key Metrics

**Overall Performance:**
- Verified reports: 301 (target was 300)
- States covered: 25 (target was 10)
- Photo willingness: 42.5%
- App interest: 82.1%
- Contact info provided: 16.6% (target was 30%)

**Key Findings:**
- Lagos concentration: Approximately 72% of all reports.
- Primary hotspot: Alimosho LGA.
- Chronic incidents: 34% of reports indicated issues lasting over one month.
- High urgency: 59% of reports rated urgency 4 or 5 out of 5.

---

## Principal Insights

- **Festive Failure:** Missed collections spiked noticeably during December 24–28.
- **Alimosho:** Structural mismatch between service capacity and population makes this a priority intervention zone.
- **Illegal dumping:** Often intentional and time-patterned, occurring at night or early morning.
- **Channel preference:** Strong appetite for WhatsApp and SMS updates over email.
- **"Nothing Happened" syndrome:** Prior reporting often resulted in no action or only temporary fixes.

---

<img width="977" height="556" alt="Screenshot_1-6-2026_133613_" src="https://github.com/user-attachments/assets/f50fc340-252e-46e1-b4c5-d49a915c54f7" />


## Dataset Download

The anonymized dataset used for this analysis is available for research, replication, and educational purposes.

**File Details:**
- Format: CSV (cleaned and validated)
- Rows: 301 verified reports
- Columns include: Waste type, state, LGA, landmark, report date, issue duration, urgency score, community impacts, previous report status, action taken, photo willingness, contact preference, update channel preference

**Download link:**
- [TrashBeta_Dataset_Dec2025.csv](./data/TrashBeta_Dataset_Dec2025.csv)
- [PowerBI Report](https://drive.google.com/drive/folders/13_PlesXm-fBipq1FuBNkVLJ1rDuoz44n?usp=drive_link)
- [Technical Report](https://docs.google.com/document/d/1OisE4XUVN39wlZLU3wKPOJBWqUZpnVQw-yFcWYcR6G4/edit?usp=drive_link)


**Access Notes:**
- All personally identifiable information has been removed.
- Location data has been generalized to LGA and landmark level.
- The dataset is licensed for academic and non-commercial use.
- For full access to geospatial shapefiles and raw social media logs, contact the project maintainer.

---

## Actionable Recommendations

**Operational:**
- Provide LAWMA and PSPs with a "Critical Strike List" (Urgency 5) plus daily heatmaps for dispatch.

**Product:**
- Integrate WhatsApp and SMS APIs.
- Require photo evidence for report verification.
- Introduce airtime or data incentives to increase engagement.

**Policy:**
- Use timestamped reports for SLA-style policy enforcement.
- Consider service credits or tax rebates if waste collection failures persist beyond 14 days.

**Infrastructure:**
- Target median strips and known dumping landmarks.
- Deploy smart bins and schedule high-frequency patrols.

**Communication:**
- Build a public-facing status tracker with clear stages: Reported → Assigned → In Progress → Resolved.

---

## Limitations & Biases

- **Digital access bias:** The data underrepresents low-income and low-connectivity communities, including informal settlements.
- **Temporal bias:** The 13-day festive snapshot may overstate failure frequency compared to normal seasons.
- **Image constraint:** Google Forms prevented file uploads during the beta; this was mitigated by measuring photo willingness and using social media photos as secondary evidence.
- **Location precision:** Approximately 8% of reports contained vague locations; the landmark field was retained as the primary dispatch asset.

---

## Technical Stack

**Data Collection:**
- Google Forms
- Social media scraping tools

**Data Processing and Analysis:**
- Pandas
- GeoPandas
- Jupyter notebooks
- Python

**Visualization:**
- Plotly and Dash
- Power BI or Tableau (exports available)

**Geospatial:**
- Folium and Leaflet
- GIS exports for heatmaps


## Impact Statement

TrashBeta translated citizen complaints into **quantifiable, operational intelligence** for LAWMA, PSPs, and policymakers. The project validated strong citizen demand for a reporting app and delivered a practical roadmap for:

- Product features (WhatsApp and SMS integration, photo verification, status tracking)
- Policy advocacy (SLA enforcement, service credits)
- Operational prioritization (hotspot dispatch, chronic failure flags)

## Connect with Me

- **Email:** [deborahadebiyi093@gmail.com](mailto:deborahadebiyi093@gmail.com)
- **LinkedIn:** [Connect with me](https://linkedin.com/in/deborahadebiyi)
