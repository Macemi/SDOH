# SDOH
Leveraging Social Determinants of Health (SDOH) Analytics to Address Healthcare Disparities

## Table of Contents
- [Project Overview](#project-overview)
- [Business Challenge](#business-challenge)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [EDA](#eda)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)

  ## Project Overview
**HealthLink Analytics** is a healthcare solutions provider dedicated to tackling **healthcare disparities** by integrating and analyzing **Social Determinants of Health (SDOH)** alongside clinical and socioeconomic data. The goal is to allocate resources effectively and improve health outcomes, particularly in **underserved communities**.

This project demonstrates how **data-driven approaches** can:
- Identify gaps in healthcare access and outcomes  
- Inform targeted interventions and policy decisions  
- Improve **health equity** for vulnerable populations

  <img width="1326" height="739" alt="Screenshot 2025-11-13 155405" src="https://github.com/user-attachments/assets/228b7b8c-1abc-44ea-a1a9-57f8fa790e74" />
<img width="1318" height="736" alt="Screenshot 2025-11-13 155416" src="https://github.com/user-attachments/assets/d0ad1363-41b8-4903-8b1c-7cfad2e2db43" />


**Geographic Focus**: The Gambia (regional geospatial analysis)

## Business Challenge
HealthLink Analytics faces critical operational and analytical challenges:

- **Fragmented data across sources**  
- **Manual data processing delays**  
- **Lack of real-time insights**  
- **Missing geospatial context**  

These barriers hinder timely decision-making and effective intervention planning in underserved regions.

## Data Sources
- **Microsoft Forms** – Real-time population health surveys  
- **Excel Online** – Dynamic data input from field teams  
- **Regional health records** – Chronic disease prevalence, hospital admissions  
- **Socioeconomic indicators** – Income levels, education, housing stability  
- **Transport access data** – Infrastructure and mobility barriers  
- **Demographic data** – Age, gender, ethnicity, employment status

## Tools
- **Microsoft Excel** – Data storage and initial structuring  
- **Power BI** – Interactive dashboards with geospatial mapping and trend analysis
- **Power Bi Service** - For collaboration and schduled refresh
- **Power Automate** – Workflow automation, data sync, real-time notifications  
- **Microsoft Forms** – Real-time data collection from communities


## EDA
*(Exploratory Data Analysis inferred from insights and visualizations)*

- Analyzed **chronic disease prevalence** by region, demographics, and SDOH factors  
- Explored correlations between **health outcomes** and:
  - Health literacy
  - Income levels
  - Transport access
  -  Housing stability
  - Education level
  - Conducted **geospatial segmentation** across Gambian regions (Basse, Kerewan, Janjanbureh, etc.)  
  - Identified **root causes** of disparities using multi-dimensional filtering

  ## Data Analysis
### Automated Data Pipeline
- **Microsoft Forms** → triggers **Power Automate** workflows  
- New data in **Excel Online** → auto-synced to **Power BI dashboard**  
- Real-time **stakeholder notifications** on key metric changes  
- **Anomaly detection** for disease spikes or admission surges


### Interactive Power BI Dashboards
- **Geospatial heatmaps** of disease prevalence and social risk  
- **Trend analysis** of hospital admissions vs. care access  
- **Demographic breakdowns** (age, gender, ethnicity, income)  
- **SDOH factor impact scoring** (transport, education, housing)
- **Parameters to make Dashboard dynamic**

## Results and Findings

### Key Insights / Root Cause Analysis

#### Disease Prevalence & Demographics
- **Malaria** = most prevalent chronic disease  
  → Driven by **lack of education, low income, poor transport**  
  → Highest in **rural areas** (low health literacy, inadequate transport)  
- **Tuberculosis** = lowest prevalence but concentrated in **urban areas**  
  → Linked to **high population density, unstable housing, low education**  
- **Health literacy rate**: **40.6%** (critically low)  
- **Moderate to high-income earners** still affected → underinvestment in infrastructure  

#### Regional Performance
- **Basse**: Highest admission rate (**65.9%**)  
- **Kerewan**: Lowest admission rate (**59.6%**)  
- **Janjanbureh**: Highest malaria burden (**225 cases**)  

#### SDOH Impact on Malaria (Most Affected Groups)
| Factor | Count | Insight |
|-------|-------|--------|
| Adults | 1,079 | Most affected age group |
| Primary education | 627 | Limited health knowledge |
| Employed | 990 | Income insufficient for prevention |
| Mandinka ethnicity | 429 | Cultural or access barriers |
| Female | 771 | Gender disparities in care access |
| Low health literacy | 614 | Lack of awareness campaigns |
| Poor transport access | 530 | Major barrier to care |
| Moderate income | 655 | Resources stretched thin |
| Stable housing | 898 | Housing not the issue  **transport & education are** |

**Critical Insight**: Stable housing does **not** protect against malaria if **transport** and **education** are deficient.

---

## Recommendations

### 1. **Policy, System, and Environmental (PSE) Changes**
- Invest in **affordable housing, safe neighborhoods, quality education**  
- Expand **medical insurance (NHS)** and **subsidize transportation**

### 2. **Deploy Predictive Analytics Models**
- Use **predictive risk scoring** for social vulnerability (housing, income, transport)  
- **Geospatial prioritization**: Overlay health + SDOH to identify hot zones  
- Automate **targeted outreach** to at-risk patients

### 3. **Trigger Targeted Interventions**
- Set **rule-based alerts** (e.g., housing instability >30% → deploy community health workers)  
- Launch **policy briefs** and **mobile clinics** in high-risk regions  
- Track intervention ROI and feed results back into dashboard

### 4. **Train Staff in Equity-Centered Care**
- Ongoing training in **cultural humility** and **bias-free resource allocation**  
- Use **teach-back methods** to improve patient understanding

### 5. **Engage Community Stakeholders Early**
- Partner with **local leaders, schools, faith groups, nonprofits**  
- Use **town halls, surveys, focus groups** to capture lived experiences  
- Launch **health literacy campaigns** in local languages  
- Train **community health workers** to build trust and access  
- **Eradicate Malaria Initiative**: Education + mosquito net distribution + transport solutions

> **Automation in Action**: Daily dashboard triggers deployment when hospital admissions spike in a region.









